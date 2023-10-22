# Desafio Transformando dados DIO

## Etapas de Transformação:
## Alteração de tipos:
- Alterei o tipo dos valores da coluna `salary` em `employee` para decimal fixo, já que estamos nos referindo a dinheiro

## Inconsistências
- Notei que na coluna `hours` em `works_on` que relaciona cada funcionário a um projeto em que ele esteja trabalhando havia valores 0, então apenas os substitui para fazerem mais sentido e terem um signficado.

## Adições
Em employee avaliei a necessidade de criar uma nova coluna `departament` que se refere ao departamento de cada funciónario associada ao devido colaborador.
