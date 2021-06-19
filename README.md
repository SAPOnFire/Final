# Desafio Final - Academia Accenture SAP BW - Turma01 - Grupo 04 (SAP ON FIRE) 

### Equipe:

DANIEL GUEDES<br/>
GENESIO PEREIRA<br/>
HIGOR MELO<br/>
LAERSON CASTRO<br/>
MARCUS FERNANDES<br/>
RORRAS NEVES<br/>


### Visão Geral:

Uma empresa que comercializa réplicas de veículos em tamanho miniaturizados está contratando uma consultoria para construção de um modelo analítico que permita visualizar os dados de uma forma ampla e com capacidade de analisar o histórico de vendas dessa empresa, uma vez que o banco de dados atual não consegue oferecer uma performance satisfatória nem é capaz de organizar os dados de uma forma que atenda as necessidades da alta gestão.


### Linha do tempo:

**- ANÁLISE ESTRATÉGICA:** Identificação, compreensão e seleção dos processos relevantes para o  negócio. <br/>
**- CRIAÇÃO DO MODELO DE NEGÓCIO:** Levantamento de requisitos; Definição da granularidade; Definição dos metadados. <br/>
**- DOCUMENTAÇÃO DOS METADADOS:** Criação da documentação dos metados; Criação do Modelo Dimensional. <br/>
**- CRIAÇÃO DO MODELO FÍSICO:** Criação do Cubo analítico; Dimensões e Fatos; Inserção dos objetos. <br/>
**- IMPORTAÇÃO DOS DADOS:** ETL.<br/>


### Solicitações do cliente e atributos necessários para apoiar as tomadas de decisão:

**- Qual modelo mais vendido?** productCode, quantityOrdered.<br/>
**- Qual volume total de vendas da empresa?** quantityOrdered, priceEach.<br/>
**- Qual vendedor fez mais vendas?** email, quantityOrdered, priceEach.<br/>
**- Qual a quantidade de vendas por localização?** city, state, country, quantityOrdered, priceEach.<br/>
**- Quais os 5 maiores clientes?** quantityOrdered, priceEach, customerNumber.<br/>

### Arquivos anexados:
[Modelagem Dimensional](https://github.com/SAPOnFire/Final/blob/main/Docs/ModelagemDimensional.pdf)<br/>
[Modelo de Negócio](https://github.com/SAPOnFire/Final/blob/main/Docs/Modelo%20de%20Negocio.xlsx)<br/>
[CSV do banco de dados relacional](https://github.com/SAPOnFire/Final/blob/main/Docs/VendaProdutosClassicModels.csv)<br/>
