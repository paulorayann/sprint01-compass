# Desafio Sprint 01 - Compass.UOL <img src="https://logospng.org/download/uol/logo-uol-icon-1024.png" style="zoom:5%;" />

## Paulo Rayann :man_technologist:

#### 1- Para que serve o método Scrum? 

> O Scrum é uma metodologia ágil que objetiva o trabalho em grupo, de modo que todos envolvidos no time são igualmente responsáveis pelo sucesso ou fracasso do projeto. 

------



#### 2- Como funciona o método Scrum? 

> O Scrum é organizado dentro das chamadas "Sprints", que são time-boxes (caixas de tempo com duração definida), objetivando a gerência de projetos de forma ágil, através da definição de objetivos e prazos estabelecidos.

------



#### 3- O que é Git? 

> Git é um sistema de versionamento de arquivos que possibilita que diversas pessoas possam trabalhar em conjunto em um mesmo projeto/código sem riscos de sobrescrever alterações anteriores.

------



#### 4- O que é um scrum Product Owner? 

> O Product Owner (P.O), é o representante do cliente dentro de um time do Scrum. Ele que capta as opiniões dos clientes que façam sentido para os negócios do projeto. Objetivando agregar o máximo de valor, a cada Sprint ele ouve tanto os Clientes quanto o time de desenvolvimento, porém, a palavra final sobre a lista de prioridades do Product Backlog é dele.

------



#### 5- Qual o comando para criação de um novo repositório no Git? 

> O comando para criação de um novo repositório no Git é:

```bash
git init
```

------



#### 6- O que é o HTTP? 

> O HTTP é um protocolo que define regras de comunicação entre cliente e servidor na internet. 

------



#### 7- Como funciona o HTTP? 

> O HTTP é baseado em texto sem conexão que funciona sem criptografia, quando uma é enviada, é feito uma chamada de mensagem, havendo uma solicitação feita pelo cliente para o servidor, e uma resposta do servidor para o cliente.

------



#### 8- Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando? 

```bash
git add < nomeArquivo>
```

------



#### 9- O que é a Branch master e para que serve? 

> A Branch master é a branch "padrão" quando se cria um repositório, ela serve como a branch base/principal do projeto. As próximas branches criadas serão secundárias, chamadas também de ramos.

------



#### 10- Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo? 

```bash
- Para atualizar um repositório local:
git pull
Caso esteja utilizando mais de um ambiente remoto configurado, precisará especificar qual ambiente será utilizado com o git pull <nomeRemoto>

- Para fazer merge de um outro branch ao seu branch ativo
git merge <nomeBranch>
```

------



#### 11- Pensando em Bases de dados, sendo elas, Relacionais (SQL) e Não Relacionais (NoSQL). Quais alternativas abaixo estão corretas? 

- [ ] ##### a. MySQL = MongoDB 

- [ ] #####   	b. PostgreSQL = Redis 

- [ ] #####   	c. Oracle = CouchDB  

- [x] #####   	d. Todas as alternativas estão corretas.  `Correto`

------



#### 12- O que é MongoDB? 

> MongoDB é um SGBD não relacional orientado a documentos. Ele possui alta flexibilidade e escabilidade.

------



#### 13- O que é o MySQL? 

> MySQL é um SGBD relacional orientado a tabelas. Ele possui um modelo cliente-servidor em que o servidor amarzena os dados e para acessar esses dados o cliente faz uma solicitação.

------



#### 14- Qual a diferença entre git e github? 

> O git é um sistema de controle de versão de arquivos, enquanto que o Github é uma plataforma criada para armazenar estes arquivos/projetos.

------



#### 15- Quais os dois verbos http que podemos utiizar para realizar um update? Explique a diferença entre eles. 

> Os dois métodos utilizados para realizar um update são o PUT e o PATCH. É similar ao método POST, porém o PUT é utilizado para atualizar recursos substituíndo todos estes recursos. Ele também pode ser usado para criar recursos.
> O método PATCH também é utilizado para realizar um update, mas ao invés de substituir recursos, ele apenas modifica o conteúdo deste recurso.

------



#### 16- Qual o status code que pode ser usado na criação de um novo usuário? 

> O status code 201 denominado de "Created". Ele informa que a solicitação foi bem sucedida e o novo recurso foi criado.

------



#### 17- Quais são os três status code que podem ser utilizados para realizar o delete? 

> Ao realizar um DELETE, os três status codes que podem aparecer são:
>
> - 200 (OK) caso a operação tenha sido bem sucedida
>
> - 202 (Accepted) operação concluída, porém não foi commitada/submetida ainda
>
> - 204 (No Content) operação processou a solitação, porém não retorna nenhum conteúdo
>

------



#### 18- Qual a extensão ".xxx" contêm as definições da tabela? 

- [x] #####   		a. Commands.myi  `Correto`

- [ ] #####   		b. Commands.frm

- [ ] #####   		c. Commands.myd 

- [ ] #####   		d. {mysqlDirectory}/data 



------



#### 19- A pasta "C:\ProgramData" é uma pasta oculta, portanto, você deve digitá-la no endereço do Windows Explorer para chegar lá. Nessa pasta de dados, quais opções apresentam o caminho correto para acessar os bancos de dados que foram denominados? 

- [ ] #####   	a. /{database_name_folder}/{database_tables_and_files}. 

- [ ] #####   	b. C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.frm

- [x] #####   	c. C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.ibd  `Correta`

- [ ] #####   	d. C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\data-recovery 



------



#### 20- Qual a extensão ".xxx" que contêm os dados da tabela? 

> É a extensão `.ibd`

------



#### 21- Qual comando usa-se para extração de arquivos em MongoDB durante a instalação? 

Na instalação do windows, basta usar o instalador do programa. Caso a instalação esteja sendo feita em Mac ou Linux o comando abaixo pode ser usado:

```bash
tar -zxvf  <nome-do-arquivo-baixado>
```



------



#### 22- Para que usamos o MongoDB? 

> Por ser um banco de dados orientado a documentos, ele oferece alta escabilidade e performance.

------



#### 23- Exemplifique para que serve os metódos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)!

> 1XX -> Respostas de informação
>
> 2XX -> Respostas de sucesso
>
> 3XX -> Mensagem de redirecionamento
>
> 4XX -> Respostas de erro do cliente
>
> 5XX -> Respostas de erro do servidor

------



#### 24- Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa @node.js_mar22 e quais suas expectativas a partir de agora: 

> Está sendo sendo uma experiência única e fenomenal, fico muito feliz de ter essa oportunidade e vou continuar me esforçando pra entregar o melhor de mim para este programa. Me senti muito bem tratado e acolhido por toda a equipe, que está sempre disposta a ajudar. Minhas expectativas atuais se baseiam em buscar absorver experiências, conhecimentos e aplicar elas no Processo.
