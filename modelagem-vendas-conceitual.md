Entidades/Tabelas:

-fabricantes: *id INTEIRO, nome TEXTO(45)
*chave primária, auto incrementado

-produtos: 
*id INTEIRO OBRIGATÓRIO
nome TEXTO(45) OBRIGATÓRIO
preço DECIMAL(8,2) OBRIGATÓRIO
quantidade INTEIRO PEQUENO NÃO É OBRIGATÓRIO
descrição TEXTO(1000) OBRIGATÓRIO
fabricante_id (NÃO PRECISA FAZER AGORA)

*chave primária, auto incrementado


-Relacionamento
Critério: cada fabricante pode possuir diversos produtos













