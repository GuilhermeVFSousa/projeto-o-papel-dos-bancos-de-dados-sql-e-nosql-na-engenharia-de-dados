
## Projeto: O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

Projeto realizado durante o Bootcamp Database Experience da Digital Innovation One (DIO).

## Objetivos


Apresentas as características e diferenças entre Bancos de Dados Relacionais e Não Relacionais. Além desse tema, também será realizada uma breve apresentação e características dos principais SGBDs de cada um dos tipos de bancos de dados.


## O Que são SGBDs?

Data Base Management System ou Sistema de Gerenciamento de Banco de Dados (SGBD) são um conjunto de softwares utilizados para o gerenciamento de uma base de dados, tendo como principal objetivo gerenciar as bases de dados utilizadas por aplicações clientes e remover esta responsabilidade das mesmas.

São responsáveis por controlar, acessar, organizar e proteger as informações de uma aplicação. Os SGBDs são divididos em dois grupos: relacionais (SQL) e não relacionais (No SQL ou Not Only SQL).

## Bancos de Dados Relacionais - SQL
SQL é a sigla para “Structured Query Language” que significa, traduzindo para o português, “Linguagem de Consulta Estruturada”. Trata-se de uma linguagem de consulta a banco de dados relacionais. Com o SQL, você pode executar vários comandos para criar, alterar, gerenciar, consultar, dentre outras informações no seu banco de dados.

Ele é baseado no modelo relacional, uma forma intuitiva e direta de representar os dados em tabelas, que também são chamados de relações. Em resumo: na horizontal, temos as linhas e na vertical as colunas. Cada coluna representa um campo diferente de dados e informações. A maior característica desse modelo é a necessidade da estruturação de esquemas, projetando uma estrutura de relacionamento entre as linhas e colunas para, assim, poder adicionar algum dado.

## Principais SGBDs

### MySQL

O MySQL é um sistema de gerenciamento de banco de dados que utiliza a linguagem SQL como interface. Lançado sobre a licença GPL, atualmente é mantida pela Oracle Corporation. É multiplataforma, ou seja, possui suporte para diferentes sistemas operacionais (Windows, Linux e Mac).

#### Principais características
- É gratuito;
- Open source
- Multiplataforma;
- Possui uma comunidade ativa;
- Pode ser utilizado em qualquer tipo de aplicação (das mais simples às mais robustas);
- Facilidade de programação e aprendizado.


### OracleDB

O mais utilizado em aplicações corporativas, o OracleDB é o SGBD comercializado pela Oracle Corporation, lançado em meados dos anos 70. É multiplataforma e possui licença comercial.

#### Principais características
- Padronização e consistência entre as diferentes versões do Oracle SQL;
- Compartilhamento de recursos;
- Flexibilidade de gerenciamento e contenção de custos;
- Estabilidade;
- Suporte, entre outros.


### SQLServer

Desenvolvido pela Microsoft, o Microsoft SQL Server é o Sistema de Gerenciamento de Banco de Dados desenvolvido para os sistemas operacionais Windows e Linux.

Possui licença proprietária e é um SGBD que atende desde as demandas mais simples até as mais complexas. 

#### Principais características
- Excelente suporte para recuperação de dados;
- Inclui softwares de gestão de banco de dados tanto para nível profissional quanto empresarial;
- Permite a criação de tabelas relacionadas;
- Gerenciamento de buffers;
- Permite que vários clientes usem o mesmo banco de dados simultaneamente;
- Controle de simultaneidade otimista (permite que uma nova versão de uma linha seja criada sempre que a linha é atualizada em vez de sobrescrevê-la).

### PostegreSQL

Open source, sob a licença BSD e multiplataforma, o PostegreSQL é um dos SGBDs mais avançados do mercado.

#### Principais características
- Altamente escalável;
- Possui uma comunidade ativa;
- Suporte a diversas linguagens de programação;
- Robusto;
- Flexibilidade ao utilizar stored procedure;
- Alta performance.


## Banco de Dados Não Relacionais (NoSQL, Not Only SQL)

NoSQL (Not Only SQL) é o termo utilizado para banco de dados não relacionais de alto desempenho, onde geralmente não é utilizado o SQL como linguagem de consulta. O NoSQL foi criado para ter uma performance melhor e uma escalabilidade mais horizontal para suprir necessidades onde os bancos relacionais não são eficazes. No geral, temos 4 tipos de bancos de dados NoSQL:

- Documento – Os dados são armazenados como documentos. Os documentos podem ser descritos como dados no formato de chave-valor, como por exemplo, o padrão JSON. Um exemplo de banco de dados neste formato é o MongoDB;

- Colunas – Os dados são armazenados em linhas particulares de tabela no disco, podendo suportar várias linhas e colunas. Também permitem sub-colunas. Um banco de dados dessa família, por exemplo, é o Cassandra;

- Grafos – Os dados são armazenados na forma de grafos (vértices e arestas). O Neo4j é um banco que utiliza grafos;

- Chave-valor – Esta família de bancos NoSQL é a que aguenta mais carga de dados, pois o conceito dele é que um determinado valor seja acessado através de uma chave identificadora única. Um exemplo é o banco de dados Redis.

No banco de dados não relacional (NoSQL), os esquemas não são necessários. Eles representam qualquer banco ligado à Big Data e não seguem o modelo relacional fornecido pelos sistemas tradicionais de gerenciamento de dados. São diversos tipos, como o key-value stores, graph stores, column stores, document stores, entre outros.


## Principais SGBDs

### MongoDB

De código aberto, multiplataforma e lançado em 2009, o MongoDB é considerado um “líder” no quesito SGBD NoSQL.

É um banco de dados orientado a documentos, baseado no formato JSON (JavaScript Object Notation) e possui uma curva de aprendizagem baixíssima.


#### Principais características

- Totalmente gratuito;
- Possui uma baixa curva de aprendizagem;
- Fácil escalabilidade horizontal;
- Multiplataforma;
- Suporte para transações ACID multi-documento;
- Consultas suportam funções JavaScript personalizadas.


### Cassandra

Desenvolvido em Java, gratuito e multiplataforma, o Cassandra originalmente foi desenvolvido no Facebook, que em 2008 compartilhou seu código-fonte para a comunidade e, agora, é um projeto de sistema de banco de dados mantido pelos desenvolvedores da fundação Apache e por muitas outras empresas que se tornaram colaboradores (Apache Cassandra).

#### Principais características
- Altamente escalável;
- Fornece acesso de baixa latência a clientes;
- Gratuito;
- Orientado por colunas (o que torna um banco de dados mais rápido);
- Possui um modelo distribuído otimizado e descentralizado.

### Redis

Redis é o banco de dados de valores-chave mais popular do mundo, ou seja, seus dados são armazenados em forma de chave valor, que armazenam objetos indexados por chaves e possibilitam a busca por estes objetos a parte das mesmas.

#### Principais características
- Desempenho muito rápido;
- Multiplataforma;
- Estruturas de dados na memória;
- Versatilidade e facilidade de uso;
- Replicação e persistência;
- Compatibilidade com a sua linguagem de desenvolvimento preferencial.

## Conclusão e reflexão
O NoSQL tem muitas vantagens para ser utilizado. Mas não é por isso que devemos utilizá-lo em todas as situações. Em muitos sistemas, você pode (e até deve) usar o modelo relacional. O NoSQL é mais indicado para aqueles sistemas que tenham necessidades maiores de armazenamento e desempenho.

O banco de dados relacional sempre irá fornecer dados íntegros e imutáveis, garantindo um controle transacional consistente. Além disso, seu esquema é rígido, sendo possível atribuir campos e estabelecer se o dado de uma coluna é nulo ou não nulo.

Já o banco de dados não relacional, que representa diversos tipos de bancos de dados, não exige a rigidez de esquemas para armazenar os dados, ou seja, ele não limita os campos, diferente das colunas do SQL. Além disso, é possível adicionar novas propriedades, sem a preocupação com o impacto nas demais informações já armazenadas.

O NoSQL não veio para substituir o SQL, mas sim para oferecer mais uma alternativa de um banco de dados mais flexível no suporte de dados. Sendo assim, pode-se usar ambas as soluções para diferentes casos de uso. Por isso, o mais comum em soluções escalares de sucesso é a utilização de uma arquitetura híbrida, aproveitando o melhor dois dois modelos.

Não existe um modelo que seja melhor do que o outro, pois cada um tem seu ponto forte. Tudo dependerá do contexto e da necessidade do projeto.









## Referências

 - [SQL vs NoSQL, qual usar?](https://www.treinaweb.com.br/blog/sql-vs-nosql-qual-usar)
 - [Os principais SGBDs NoSQL](https://www.treinaweb.com.br/blog/os-principais-sgbds-nosql/)
 - [Os principais SGBDs relacionais](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
 - [Banco de dados: entenda o que é um banco de dados relacional e não relacional](https://www.digitalhouse.com/br/blog/banco-de-dados-relacional-e-nao-relacional/)

