# Códigos GIT, Github & NodeJS

Todos os códigos mais utilizados e importantes para terminal.


## GIT

Todos os comandos principais para se utilizar no terminal sobre o GIT:

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

## Advanced CSS

Alguns CSS avançados para utilizar e para que servem.

```
  page-break-inside: avoid;    ------------------------------------->>>>>> Serve para dar um flex-wrap (quebrar linha quando não couber um determinado item), na tela de impressão, ou seja ele vai ver se cabe na folha a4 senão ele quebra a linha
```

## Docker

Todos os comandos principais para se utilizar no terminal sobre o Docker:

```
  sudo apt update                          : Serve para atualizarmos as pastas docker que temos no nosso computador.
  docker-compose up [OPTIONS] [SERVICE...] : Cria e começa / (starta) nossos containers.

```


### Arquivos GIT

Arquivos importantes de se ter no seu projeto

```
  .gitignore    : Faz o git não importar as pastas / arquivos que estiverem dento desse documento para dentro do github.
  .gitkeep    : Faz o github enxergar uma pasta mesmo que ela esteja vazia.
```


## NodeJS

Todos os comandos principais para se utilizar no terminal sobre o NodeJS

```
npm init -y                        : Serve para instalar o package.json
npm install lite-server            : instala o lite-server o package-lock.json & o node_modules
    * Dentro do package.json alterar a linha escrita 'test' para "start" & 'conteúdo' para 'lite-server'
npm start                          : Starta o lite-server (funciona como a extenção live-server)
npm install express --save         : Instala o Express (biblioteca de arquivos)
npm install nodemon --save-dev     : Faz Instala o Nodemon, que faz atualizações periódicas ao nosso servidor sempre que alterarmos algo, como no lite-server, mas aqui nao precisa parar e startar o server.
npm install sqlite3 sqlite --save  : Instala o SQLite no seu programa.
npm install react-router-dom       : Instala uma biblioteca para adicionarmos navegação ao APP, clicar no botão Voltar e voltar pra página que a gente estava por exemplo.
npm install jsonwebtoken           : Instala uma lib para podermos gerar tokens para que o usuário consiga acessar a conta dele por esse método.
npm install multer                 : Serve para utilizarmos na hora de realizar uploads de arquivos de um computador para dentro da aplicação.
npm install cors                   : É uma lib para compartilhamento de Recursos de Origens diferentes. Habilita que o backend realize as requisições do front end.
npm install axios                  : Biblioteca usada para trabalhar com requisições http.
npm install dotenv --save          : Lib servirá para lidarmos com dados sensíveis, podemos criar variáveis de ambiente e utilizarmos na nossa aplicattion.
```

## Comandos Laravel

Todos os comandos principais para se utilizar no terminal sobre o Laravel;

```
composer create-projext laravel/laravel ariosi ;
php artisan serve ;
php artisan make:controller SiteController -r ;
php artisan make:model Client -m ; Assim o artisan criará uma migration chamada clients e uma model chamada Client;
php artisan key:generate   ==== Caso dê bug ne falta de key;
php artisan rollback       ==== Para dar rollback na minha migration;
composer install       ==== Para instalar as dependências do artisan, pique um npm i, ou um yarn;
```

## Conhecimentos Básicos Laravel

sempre dar um compose install quando iniciar um projeto composer ou for rodar um projeto laravel para baixar as dependências;
a node_modules do laravel é a pasta chamada ./vendor;

## React

Comando para se utilizar no terminal. Relacionados ao REACT

```
npm install react-icons --save
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


## Query Builder

>  #### Query Builder é um Construtor de Consulta
>  #### O Query Builder permite que você construa instruções SQL independente do banco de dados utilizado.
### `Query Builder` `-------->` `Banco de Dados`


## Migrations

>  #### É uma forma de versionar a base de dados.
>  #### Migrations trabalha na manipulação da base de dados: criando, alterando ou removendo.
>  ## Métodos de uma migrations
>  ## UP: método responsável por criar ou alterar algo no banco de dados.
>  ## DOWN: responsável pelo rollback. Ou seja, desfazer as alterações realizadas pela migration.

## NPX
### Package Runner
> ### `NPM`
>  #### Node Package Manager é o gerenciador de pacotes padrão para Node.js.
>  #### Os pacotes e módulos necessários no projeto Node são instalados usando npm.
>  #### E também utilizamos o npm para executar scripts e bibliotecas instaladas.

> ### `NPX`
>  #### O npx significa Node Package Execute e vem com o npm acima da versão 5.2.
>  #### É um executador de pacotes npm que pode executar qualquer pacote que você quiser do registro npm sem sequer instalar esse pacote.

## Manipulando Arquivos
### O módulo fs do Node.js
> #### O módulo *fs* permite trabalhar e manipular os arquivos.
> #### *.rename*: A função .rename serve para renomear ou mover o arquivo, ai passamos 2 informações, onde está o arquivo e para onde quero que ele vá utilizando o path.resolve
> #### *.path.resolve*: Resolver uma sequência de segmento de caminho para um caminho absoluto.
> #### *.stat*: Retorna o status do arquivo.
> #### *.unlink*: Remove um arquivo.

## API RESTful
### API (Aplication Programing Interface)
> #### Interface que disponibiliza um conjunto de funcionalidades para serem utilizadas/consumidas.
### REST (Representational State Transfer)
> #### Transferência Representacional de Estado. É um modelo de arquitetura e não uma linguagem ou tecnologia de programação, que fornece diretrizes para que os sistemas distribuídos se comuniquem usando os princípios e protocolos Web, como por exemplo, o protocolo HTTP.
### API RESTful
> #### É aquela API que cumpre as diretrizes RESTful. (junção da API com o REST)
`Cliente - Server` `O cliente e o servidor deve estar separado.`

`Stateless` `Cada requisição deve ter o necessário para o servidor entender e responder a requisição. O servidor não deve lembrar/armazenar estados.`

`Layered System` `O cliente acessa um endpoint sem precisar saber como é implementada.`

## Hooks
### Permite que você use estados e outros recursos do React sem escrever numa classe. Encapsula funcionalidades e facilita o reaproveitamento da sua lógica.
> #### Exemplos de Hooks
> `useState` `useEffect`
> #### Como escrever os Hooks:
> `use`+`NomeDoHook` -----> `Todo em camelCase e no final fica algo tipo` `useNomeDoHook`

## Estados
### Por que não utilizarmos variáveis comuns ?
> #### Variáveis não persistem entre renderizações.
> ##### Quando o React renderiza o componente uma segunda vez, ele o renderiza do zero. Não considera nenhuma mudança nas variáveis locais. Ou seja, as alterações em variáveis locais não irão acionar renderizações. O React não percebe que precisa renderizar o componente novamente com os novos dados.
> #### Para atualizar um componente com novos dados, duas coisas precisam acontecer:
> ##### 1. Retenha os dados entre as renderizações.
> ##### 2. Acione o React para renderuzar o componente com novos dados (re-renderização).

> #### O useState fornece essas duas coisas:
> ##### 1. Uma variável de estado para reter os dados entre as renderizações.
> ##### 2. Uma função de configuração de estado para atualizar a variável e acionar o React para renderizar o componente novamente.

> ### Em React, useState, assim como qualquer outra função que comece com "use" é chamado de Hook. (Gancho) 
> #### Hooks são funções especiais que só estão disponíveis enquanto o React está renderizando.
> #### Quando você chama o useState, você está dizendo ao React que deseja que este componente se lembre de algo

> ### Recapitulando:
> #### 1. Use uma variável de estado quando um componente precisar "lembrar" alguma informação entre renderizações.
> #### 2. As variáveis de estado são declaradas utilizando o useState.
> #### 3. O useState retorna um par de valores: o estado atual e a função para atualizá-lo
> #### 4. O estado é privado para o componente. Se você renderizar em dois lugares, cada cópia terá seu próprio estado.

## Local Storage
### Permite armazenar informações no navegador do usuário.
> #### Estrutura do Local Storage
> ##### `Local Storage` `Chave` `Valor`
> ##### `Exemplo:`
>```javascript
>localStorage.setItem("user", "Ariosi Lucas");
>```

## useEffect
### O que o useEffect faz ?
> #### Você diz ao React que o componente precisa fazer algo depois da renderização. Isto é, depois que realizar as atualizações do DOM.
### Por que o useEffect é chamado dentro de um componente ?
> #### Colocando useEffect dentro do componente nos permite acessar os estados do componenete.
> > ##### `Exemplo:`
>```javascript
>export function MyComponent(){
>  const [name, serName] = useState("")
>
>  useEffect(() => {
>
>    searchByName()
>
>  }, [name])
>
>  return(
>    // ...
>  )
>
>}
>```

## Renderizações
### Render:
> #### Antes dos seus componentes serem exibidos na tela eles devem ser renderizados pelo React.
> #### Vamos entender as etapas desse processo e do comportamento do React.
### Ilustração
> #### Imagine que seus componentes são conzinheiros na cozinha montando pratos saborosos a partir dos ingredientes.
> `Componente Card` `------>` `Propriedades`
> `Cozinheiro 1` `------>` `Peixe Cozido no Vapor`
> `Component` `------>` `Para fazer um button precisa do Ingrediente Title`

> #### Nesse cenário o React é o garçom que faz os pedidos dos clientes e traz os seus pedidos.
> ##### Esse processo tem 3 etapas:
> `Etapa 1`
> ##### Acionar: Quando o pedido é entregue a cozinha.
> `Etapa 2`
> ##### Renderizar: Quando o prato tá pronto e o Cozinheiro entrega o prato ao Garçom React.
> `Etapa 3`
> ##### Comprometer-se: Quando o garçom entrega o prato para o cliente, já que ele se Comprometeu de voltar a ele com o componente(prato).

### Etapa 1
### Há duas razões para um componente renderizar:
> #### 1. Quando é a renderização inicial do componente.
> ##### Quando o seu aplicativo é iniciado a renderização inicial é acionada.

> #### 2. O estado do componente mudou.
> ##### A atualização do estado do componente emfileira automaticamente uma renderização. Você pode imaginar o cliente do restaurante pedindo mais coisas.
> #### Nesse segundo caso o ato de Re-renderizar é quando o estado é atualizado
> ##### `Atualização do estado` `Gatilho` `Renderizar`

### Etapa 2
### React renderiza seus componentes
> #### Depois de acionar uma renderização o React chama seus componentes para descobrir o que exibir na tela.
> ##### O Rendering é o React chamando seus componentes.
> #### Na renderização inicial, o React chamará o componenete raiz
> #### Para renderizações o React chamará o componente de função cuja atualização de estado acionou a renderização.
> `Esse processo é recursivo. O componente também pode disparar um gatilho para renderizar algo em seguida, e assim por diante.`
> 
> `O processo continuará até que não haja mais componenetes aninhados e o React saiba exatamente oque deve ser exibido na tela.`

### Etapa 3
### Após renderizar (chamar) seus componentes, o React modificará o DOM.
> #### Para a renderização inicial o React usará a API DOM para colocar todos os nós DOM criados na tela.
> #### Para re-renderização o React aplicará as operações mínimas necessárias (calculadas durante a renderização) para fazer o DOM corresponder à saída de renderização mais recente.
### O React só altera os nós DOM se houver uma diferença entre as renderizações.

### Recapitulando
> #### Qualquer atualização de tela em um aplicativo React acontece em três etapas:
> `1. Acionar` `2. Renderizar` `3. Comprometer-se`
> #### O React não toca no DOM se o resultado da renderização for o mesmo da última vez.

## O que é Deploy
### Deploy
> #### O deploy ou deployment significa implantar.
> #### Significa enviar um novo projeto, mudanças ou atualizações para um determinado ambiente.
### Ambientes
> `Desenvolvimento` `Staging ou Teste` `Produção`
### Estratégias
> `Deploy Manual` 
> ### OU
> `Deploy Automatizado`
## Dados sensíveis
### Exemplos de dados sensíveis:
> `senhas` `chaves de serviços ou API` `Tokens, Hash` `Informações do banco de dados` `Etc...`
### Variáveis de Ambiente:
#### .env
> ```javascript
>  APP_NAME=AriosiBLog
>
> SECRET_API=9as1%12#
>
> CPUS=4
>
> # Banco de dados
> DB_NAME=ariosil
> DB_PASS=
> DB_HOST=localhost
>
> # Stack
> STACK=["React Native", "ReactJS", "NodeJS"]
> ```
> ### Padrões para se adotar no .env
> `As chaves são em caixa alta, por padrão, mas não é exigência para que funcione.`
> 
> `As chaves não podem ter espaço.`
> 
> `Os valores podem ser quaisquer tipo, que será retornado sempre uma string.`
> 
> `Pode haver espaçamentos, porém é feito um trim na string. (ignora esse espaço)`
> 
> `Pode existir chave sem valor, que nesse caso retornam uma string vazia.`
### Boas Práticas e cuidados
> #### Por se tratar de informações sensíveis na sua maioria é importante que esses dados só fiquem em seu ambiente de desenvolvimento, então se você pretende compartilhar seu código lembre-se de remover esse arquivo.
> #### Caso utilize o github basta adicionar ao .gitignore o arquivo .env para ele fazer esse trabalho para você.
> #### Uma boa prática também é criar um arquivo de exemplo com as chaves que seu projeto está utilizando, sem os valores sensíveis, assim quem clonar seu repositório ou ter acesso ao seu código fonte não ficará perdido.
> #### Crie um .env.example e deixe apenas informações genéricas como é o caso do APP_NAME.

## Mantendo a API ON
### PM2
> ### PM2 é um gerenciador de processor que irá ajudar a gerenciar e manter a aplicação online 24 horas por dia, 7 dias por semana.
> #### Ele percebe quando nossa API para por algum motivo, como requisição errada enfim. E simplesmente reinicia ela, para que sempre possamos usufruir da nossa API na nossa aplicação.

## Testes
### Permite identificar erros durante o desenvolvimento e assegurar a qualidade e o funcionamento correto da aplicação.
> ### Testes Automatizados
> #### O teste automatizado é a utilização de ferramentas de software para automatizar um processo manual conduzido por humanos de revisão e validação da aplicação. Adoção ampla do método.

### Tipos de Testes
> #### Testes de Unidade
> ##### `Testa unidades individuais do código. Por exemplo, testa uuma função específica da aplicação.`
> #### Testes de Integração
> ##### `Testa as unidades do código trabalhando juntas. Por exemplo, teste de Login que envolve uma série de etapas.`
### Boas Práticas
> #### 1. Simples e Tápido
> Testes simples e rápidos. Isso nos possibilita ter um feedback o mais cedo possível sobre possíveis impactos das modificações feitas no software. Além disso, facilita para podermos rodar os testes várias vezes se necessário e torna mais ágil o debug dos testes, reduzindo o tempo necessário para criar e manter os scripts.
> #### 2. Independentes
> Os testes devem ser independentes entre si. Isso evita que a falha em um teste cause falha em outros testes, o que dificulta e torna bem mais demorada a investigação de problemas. O "você do futuro" vai agradecer muito ao "você do presente" por isso.
> #### 3. Ambiente
> Os testes não devem depender de ambientes ou recursos externos, cmo serviços, API's, banco de dados, etc. O teste deve ser capaz de rodar a qualquer momento e quantas vezes forem necessárias.

## O princípio da Inversão de Dependência
> ### Definição
> #### Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender de abstrações; Abstrações não devem depender de detalhes. Detalhes devem depender de abstrações.
> ### Resumindo o Objetivo
> #### Desacoplar e diminuir a depêndencia entre regra de negócio e infraestrutura.
> ### Controlando o Acoplamento
> #### De maneira geral, será praticamente impossível criar uma aplicação onde a arquitetura seja totalmente desacoplada e abstrata, pois acoplamentos concretos sempre existirão.
> ### O Segredo
> #### O segredo está em saber diferenciar os acoplamentos ruins dos acoplamentos bons, pois assim "modelaremos nossos sistemas fugindo dos 'acoplamentos perigosos'".
> ### Exemplo de Acoplamento
> #### Controller de Cadastrar Usuário
> `Request & Response`
> 
> `Banco de Dados SQLite` `-->` `Dependência`
>
> ### Desacoplando
> #### `Controller que cuida da Requisição e Resposta` `--->` `Informa o Banco` `--->` `Regra de negócio com a lógica do cadastro de usuário`
















