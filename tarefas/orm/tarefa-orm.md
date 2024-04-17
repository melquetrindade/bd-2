# Resumo ODBC

ODBC (Open Database Connectivity) é uma API (Application Programming Interface) que permite que aplicativos acessem e manipulem dados em diferentes bancos de dados, independentemente do sistema de gerenciamento de banco de dados (SGBD) subjacente. Ele fornece uma camada de abstração que permite aos desenvolvedores escreverem código que possa se comunicar com uma variedade de fontes de dados usando um conjunto comum de interfaces. Para utilizar o ODBC em Python, primeiro deve-se estabelecer uma conexão com o banco de dados usando pyodbc.connect(), fornecendo os detalhes de conexão. Em seguida, cria-se um cursor para executar consultas SQL e processar os resultados. Depois de concluir as operações, deve-se confirmar as alterações e fechar a conexão e o cursor.

# Resumo ORM

ORM (Object-Relational Mapping) é uma técnica de programação que mapeia objetos em um sistema orientado a objetos para tabelas em um banco de dados relacional. Isso permite que os desenvolvedores manipulem dados do banco de dados usando objetos e métodos em vez de escrever SQL manualmente.

A biblioteca SQLAlchemy em Python é uma poderosa ferramenta ORM que simplifica o trabalho com bancos de dados relacionais. Com SQLAlchemy, os desenvolvedores podem definir modelos de dados como classes Python e interagir com o banco de dados por meio desses modelos. SQLAlchemy cuida da tradução entre os objetos Python e as instruções SQL necessárias para manipular os dados no banco de dados.

A utilização do ORM com SQLAlchemy envolve definir modelos de dados usando classes, mapear esses modelos para tabelas no banco de dados, realizar consultas, inserções, atualizações e exclusões de dados usando métodos de objeto e expressões SQLAlchemy, e gerenciar transações de forma eficiente. Essa abordagem simplifica o desenvolvimento de aplicativos, aumenta a portabilidade do código e reduz a quantidade de SQL manualmente escrito.

# Links para scripts
