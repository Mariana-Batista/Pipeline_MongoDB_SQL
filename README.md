Este repositório contém um projeto completo de pipeline de dados, que implementa a técnica de ETL (Extract, Transform, Load) utilizando as ferramentas MongoDB, MySQL e a linguagem Python. 
Este projeto tem como objetivo automatizar a coleta, transformação e carregamento de dados.

Ferramentas e Bibliotecas Utilizadas:

MongoDB:
Banco de dados NoSQL utilizado para armazenar dados semi-estruturados e não estruturados.
Realização de conexões para extração de dados das coleções do MongoDB.

MySQL:
Banco de dados relacional utilizado para armazenar dados estruturados.
Criação de esquemas e tabelas para armazenamento dos dados transformados.

Python:
Linguagem principal utilizada no desenvolvimento do pipeline.
Pandas: Biblioteca utilizada para manipulação e transformação dos dados.
Pymongo: Biblioteca utilizada para conectar e interagir com o MongoDB.
mysql-connector-python: Biblioteca utilizada para conectar e interagir com o MySQL.

Etapas do Pipeline de Dados:

Extração de Dados (Extract):
Conexão com o MongoDB para extrair os dados brutos das coleções específicas.
Utilização de queries MongoDB para coletar os dados necessários.

Transformação de Dados (Transform):
Processamento dos dados extraídos utilizando a biblioteca Pandas.
Limpeza e formatação dos dados para garantir consistência e integridade.
Aplicação de transformações adicionais, como agregações, cálculos e conversões de tipos de dados.

Carregamento de Dados (Load):
Conexão com o MySQL para carregar os dados transformados.
Criação de esquemas e tabelas no MySQL para armazenar os dados processados.
Inserção dos dados transformados nas tabelas do MySQL utilizando comandos SQL apropriados.

Benefícios do Projeto:
Automatização: A automação do processo ETL reduz a necessidade de intervenção manual, aumentando a eficiência e a precisão do pipeline de dados.
Escalabilidade: Utilização de MongoDB e MySQL, ferramentas robustas que suportam grandes volumes de dados.
Flexibilidade: Capacidade de integrar e processar dados de diferentes fontes e formatos em um pipeline unificado.
Consistência: Garantia de integridade e consistência dos dados através de etapas bem definidas de transformação e validação.
