# Anotações sobre Git

Listar as configurações <br>
```git config --list```

Configura nome de usuário <br>
```git config --global --add user.name <nome_do_usuario>```

Configura e-mail <br>
```git config --global --add user.email <email>```

Configura o VSCode como editor padrão <br>
`git config --global core.editor vscode`

Exibe o status do repositório <br>
`git status`

Cria um repósitorio local<br>
`git init`

Adicionar arquivos e diretórios para serem comitados <br>
`git add .`
<br> O ponto indica que todos os arquivos e diretórios serão adicionados
<br>

Desfazer mofificação no arquivo<br>
`git checkout -- <nome_do_arquivo>`

Gerando um commit <br>
`git commit -a -m "mensagem"`
+ O -a indica que todos os arquivos serão adicionado ao commit
+ O -m adiciona uma mensagem ao commit, geralmente utilizada para informar as alterações feitas.

Editar commit<br>
`git commit --amend`

Restaurar arquivo deletado<br>
`git restore <Arquivo>`

Logs<br>
```
git log
git shortlog
```

Exibir conexões remotas<br>
`git remote -v`

Conecta ao repositório remoto <br>
`git remote add origin <URL_GitHub>`

Enviar commits para repositorio remoto<br>
`git push -u origin main`

Baixa arquivos do repositorio remoto<br>
`git pull origin main`
