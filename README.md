# Projeto-Final-Soulcode
Trabalho de conclusão do Bootcamp de Analista de Dados com a Soulcode, com 12 semanas de duração. Projeto elaborado por um grupo de 5 elementos.
## Escopo do Projeto
- Etapa 01:
  - Inicialmente o grupo deverá criar um Bucket no Google Cloud Storage e armazenar essa
  base de dados em uma pasta chamada dados brutos. Após isso, o grupo deverá criar uma
  instância de MySQL no Google Cloud SQL e armazenar essa mesma base de dados em um
  banco relacional (é necessário entregar junto com o projeto final a o Modelo Entidade
  Relacionamento dessa base).

- Etapa 02:
  - O grupo deverá criar um colab para extrair, transformar e carregar os dados e deverá
  escolher se faz fará a extração diretamente da Bucket (Google Cloud Storage) ou do banco
  de Dados relacional (Google Cloud SQL), o grupo também poderá fazer a extração pelos
  dois métodos para fins de demonstração de conhecimento das duas ferramentas. é
  Importante que todos os códigos desse colab estejam devidamente comentados para
  entendimento do avaliador.

- Etapa 03:
  - Após todas as transformações necessárias, incluindo a criação de novas colunas e até
  mesmo de novas tabelas (fruto de agrupamentos e agregações da análise exploratória de
  dados) o grupo deverá fazer o carregamento (Load) dos dados tratados no Google Big
  Query e no Google Cloud Storage.

- Etapa 04:
  - O grupo deverá fazer a conexão dos dados tratados com um visualizador de dados e criar o
  relatório final com os dashboards que respondam às perguntas de negócios elaboradas
  pelo grupo. Obs. O grupo deverá obrigatoriamente utilizar Looker Studio ou Power BI e
  opcionalmente Tableau e Oracle Analytics.

## Objetivo do Projeto
  - Gerar insights que auxiliam na tomada de decisões que possam agregar melhorias no Faturamento, Fornecimento e Estoque da Empresa.

## Ferramentas Utilizadas
- [Google Cloud](https://console.cloud.google.com/)
  - Foi criado um novo Projeto dentro do GCP;
  - Criação de Buckets onde foram armazenados os dados Brutos recebidos de uma das empresas parceiras da Soulcode;
  - Power Shell para escrever e executar códigos que possibilitaram a criação de Banco de dados e Tabelas;
  - BigQuery, onde armazenamos os dados depois de serem tratados.

- [Google Colab](https://colab.research.google.com/drive/)
  - Conexão com Google Cloud Platform;
  - Escrevemos códigos em **Python**, usando a biblioteca **Pandas**;
  - Consultas e tratamentos de dados em **SQL**.

- [PowerBI](https://app.powerbi.com/)
  - Obter dados da BigQuery;
  - Criação de **Dashboards**;
  - Power Service para apresentação.
