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
