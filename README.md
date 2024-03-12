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
  git commit --amend -m ""  : Faz você alterar o texto escrito do último commit.
  git reset --soft HEAD~1   : Deleta seu último commit
  git rm  -r --cached	.    : Reseta o cache, possibilitando colocar documentos fora da pasta .gitignore, dentro da mesma.
  git pull		    : Busca por atualizações do código dentro do github, e retorna com o código atualizado no seu VSCode.
```
### Arquivos GIT

Arquivos importantes de se ter no seu projeto

```
  .gitignore    : Faz o git não importar as pastas / arquivos que estiverem dento desse documento para dentro do github.
  .gitkeep    : Faz o github enxergar uma pasta mesmo que ela esteja vazia.
```
## NodeJS

Todos os comandos principais para se utilizar no no terminal sobre o NodeJS

```
npm init -y                        : Serve para instalar o package.json
npm install lite-server            : instala o lite-server o package-lock.json & o node_modules
    * Dentro do package.json alterar a linha escrita 'test' para "start" & 'conteúdo' para 'lite-server'
npm start                          : Starta o lite-server (funciona como a extenção live-server)
npm install express --save         : Instala o Express (biblioteca de arquivos)
npm install nodemon --save-dev     : Faz Instala o Nodemon, que faz atualizações periódicas ao nosso servidor sempre que alterarmos algo, como no lite-server, mas aqui nao precisa parar e startar o server.
npm install sqlite3 sqlite --save  : Instala o SQLite no seu programa.
```

## SQL

Comandos vistos para utilizar com o SQL. (letras minúsculas são as que mudam)

```
CREATE TABLE users (id INTEGER PRIMARY KEY AUTOINCREMENT, name VARCHAR, avatar VARCHAR NULL, created_at TIMESTAMP DEFAULT CURRENT TIMESTAM) : Cria uma tabela com o nome que você colocar no lugar do users.
ALTER TABLE users RENAME TO clients                                       : Altera o nome da tabela "" para o que voce colocar.
ALTER TABLE clients ADD status VARCHAR                                    : Acidiona uma Coluna a uma tabela já existente.
ALTER TABLE users RENAME COLUMN status TO active                          : Renomeia uma coluna que você escolher de uma tabela escolhida.
ALTER TABLE users DROP COLUMN status                                      : Deleta uma coluna.
INSERT INTO users (name, email, password) VALUES ('Ariosi Lucas', 'ariosilucas@gmail.com', '123321') : Adiciona valores aos parâmetros NA MESMA ORDEM que foram inseridos nos parênteses.
SELECT * FROM users                                                       : Mostra todos os detalhes e itens dentro de uma determinada tabela.
UPDATE users SET avatar = 'lucas.png', name = 'Lucas Ariosi' WHERE id = 1 : Faz o update de uma pessoa específica no seu banco de Dados, nesse caso o numero 1, atualizando o avatar e o nome dessa pessoa.
DELETE FROM users WHERE id = 3                                            :
```

## CRUD oque é ?!

Quais são as tags SQL que são utilizadas para cada uma das palavras no termo CRUD.

`C` `-` `Create` `->` `INSERT` |

`R` `-` `Read` `->` `SELECT`ㅤ|

`U` `-` `Update` `->` `UPDATE` |

`D` `-` `Delete` `->` `DELETE` |
