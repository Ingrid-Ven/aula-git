# Comandos Git
Neste arquivo será apresentado os comandos git para uso futuro.

## No primeiro uso em um computador
Para que o GIT avise e saiba quem fez as alterações é necessário configurar o usuário nas configurações globais do git.
```bash
git config --global user.name "Ingrid Venancio"

git config --global user.email "ingrid.venancioo@gmail.com"
```

### Explicandos os comandos do Git
Dentro da pasta que criamos no terminal utilizamos o comando Git init para inicializar. Só utilizamos esse comando 1 vez.
```bash
git init
```
Após inicializar o processo, abrimos o code com o comando e criamos uma pasta onde vamos realizar o projeto
```bash
code ./comandos.md
```
Após criar a pasta no code, voltamos ao terminal e utilizamos o status para ver a situação do repositório. Se estiver vermelho  precisa adicionar arquivo, se estiver verde estão prontos para salvar (commit)
```bash
git status
```
Para adicionar todos os arquivos modificados para serem versionados utilizamos o add
```bash
git add .
```

Para criar uma versão de tudo que foi modificado até aquele momento utilizamos o commit. <br>
**IMPORTANTE** no -m temos que colocar uma mensagem do porque estamos salvando.
```bash
git commit -m  "Porque estou salvando estas alterações"
```

Git push envia os commits do pc para o Github
```bash
git push
```

