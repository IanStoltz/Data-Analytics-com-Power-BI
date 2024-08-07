<p align="center">
<a href="https://www.dio.me/bootcamp/coding-the-future-sysvision-data-analytics" target="_blank" rel="noreferrer">
  <img src="https://hermes.dio.me/tracks/533ac6c6-f653-40e1-8050-da19cd540fa4.png" alt="Data Analytics com Power BI" width="100" height="100"/>
    
### Desafio de projeto: 
#### Criação de modelo Star Schema com base em uma tabela Financial Sample, única.

#### Desenvolvimento
* Foi determinado o interesse central da análise como Vendas e feita a criação da tabela fato F_Vendas.

* Foram criadas e divididas as tabelas dimensões (D_descontos, D_detalhes, D_Produtos, D_Produtos_Detalhes) com base nos produtos, seus detalhes e valores.
    - As tabelas foram criadas por agrupamentos de informações, colunas condicionais e mescla de consultas.
    - As tabelas receberam índices próprios e ID's para futuros relacionamentos.
    
* Foi criada a tabela de dimensão temporal D_calendar para criar o relacionamento temporal.
    - Esta tabela foi criada utilizando DAX e os conceitos de hierarquia e granularidade.
    
* Foram estabelecidos os relacionamentos com base na quantidade de instâncias.

* Foi modelado o Star Schema relacionando as tabelas dimensões com a tabela fato.

## Tecnologias utilizadas
<p align="left"> 
 <a href="https://www.microsoft.com/pt-br/power-platform/products/power-bi" target="_blank" rel="noreferrer"> 
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/New_Power_BI_Logo.svg/600px-New_Power_BI_Logo.svg.png?20210102182532" alt="PowerBI" width="40" height="40"/> </a> &nbsp;
