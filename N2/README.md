# Problema de Análise Preditiva

1. Descrição do Problema

Atualmente, existe uma concentração significativa de veículos elétricos registrados no Washington State Department of Licensing. Com base em informações provenientes de uma grande massa de dados, que abrange diversos modelos e fabricantes de carros elétricos, 
pretendo realizar uma análise abrangente sobre o mercado de veículos elétricos. Isso inclui identificar os carros mais populares em cada região, bem como os menos populares, e também determinar os tipos de baterias mais predominantes no mercado. 
Os dados para essa análise estão disponíveis no período de 10/11/2020 a 15/09/2023.

2. Descrição da Solução

Para abordar esse problema e extrair as informações necessárias, implementarei um processo de Extração, Transformação e Carga (ETL) de dados. Utilizarei as ferramentas do Power BI e Google Big Query para realizar as etapas essenciais desse processo. A seguir, cada uma das fases detalhada:

- Extração: Farei a coleta dos dados diretamente do site catalog.data.gov, através da API de dados disponível. O Power BI será a ferramenta principal para extrair esses dados, garantindo que tenhamos acesso às informações mais atualizadas e abrangentes.
- Transformação: Utilizarei a funcionalidade de transformação de dados no Power BI, especialmente por meio do Power Query. Nesse estágio, aplicaremos diversas operações de limpeza, formatação e agregação de dados. Isso incluirá a identificação dos modelos de carros mais populares em diferentes regiões, a identificação dos carros menos populares e a análise dos tipos de baterias predominantes.
- Carga: Finalmente, carregarei os dados transformados no Google Big Query. A plataforma se comporta como um repositório de data warehouse, permitindo que eu consulte com mais facilidade os dados disposos pelo modelo de transformação.
