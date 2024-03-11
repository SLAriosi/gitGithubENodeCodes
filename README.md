# Códigos GIT, Github & NodeJS

Todos os códigos mais utilizados e importantes para terminal.

## GIT

Todos os comandos principais para se utilizar no no terminal sobre o GIT

```
  git add . 	 	    : Adiciona todas as alterações para que possa ser usado o commit.
  git commit -m "" 	    : Faz um novo commit realizando todas as alterações.
  git push 	 	    : Joga tudo dentro do Repositório Git para o repositório.dentro do GitHub.
  git log -n 3	            : Mostra os últimos 3 commits realizados no projeto.
  git diff	            : Ver alterações nas linhas do código antes do commit.
  git restore .	            : Restaura tudo antes de você ter feito um commit.
  git restore --staged .    : Faz os arquivos voltarem para antes do "git add ." habilitando o "git restore ."
  git commit amend -m ""    : Faz você alterar o texto escrito do último commit.
  git reset --soft HEAD~1   : Deleta seu último commit
  git rm  -r --cached	    : Reseta o cache, possibilitando colocar documentos fora da pasta .gitignore, dentro da mesma.
  git pull		    : Busca por atualizações do código dentro do github, e retorna com o código atualizado no seu VSCode.
```
## NodeJS

Todos os comandos principais para se utilizar no no terminal sobre o NodeJS

```
npm init -y             : Serve para instalar o package.json
npm install lite-server : instala o lite-server o package-lock.json & o node_modules
    * Dentro do package.json alterar a linha escrita 'test' para "start" & 'conteúdo' para 'lite-server'
npm start               : Starta o lite-server (funciona como a extenção live-server)  
```
