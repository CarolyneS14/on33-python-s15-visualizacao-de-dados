# 📈📉📊 Visualização de Dados 

## 📚 Descrição da Atividade

Exercicio para casa semana 15.
**Objetivo:** Escolha a base da Olist ou da Netflix utilizada em módulos anteriores e crie, pelo menos, cinco gráficos de estilos diferentes (por exemplo: um heatmap, um gráfico de barras, um histograma e um gráfico de pizza) indicando quais são suas conclusões obtidas com essa visualização.

  ### 📚 Descrição da Base:

Base tratada na aula da semana 14 [Olist](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/base_vendas_s14_olist.csv) disponivel neste repositório.

Após tratamento minha base de dados ficou assim:

     0   order_id                       
     1   customer_id                    
     2   order_status                   
     3   order_purchase_timestamp       
     4   order_delivered_customer_date 
     5   order_estimated_delivery_date 
     6   order_item_id              
     7   product_id                  
     8   seller_id                   
     9   shipping_limit_date          
     10  price                          
     11  freight_value                 
     12  customer_city                  
     13  customer_state                 
     14  product_category_name         
     15  seller_city                    
     16  seller_state                    


A base original de dados da [Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) é composta por 9 tabelas diferentes, nelas temos informações de:
- pedidos (olist_orders_dataset)
- itens dos pedidos (olist_order_items_dataset)
- review dos usuários sobre os pedidos (olist_order_reviews_dataset)
- detalhes de pagamento dos pedidos (olist_order_payments_dataset)
- detalhes do consumidor que fez os pedidos (olist_customers_dataset)
- detalhes de geolocalização do consumidor (olist_geolocation_dataset)
- detalhes dos produtos (olist_products_dataset)
- detalhes dos vendedores (olist_sellers_dataset)

Dentre os datasets acima optei por trabalhar apenas com estes datasets, o de pedidos (olist_orders_dataset), itens do pedido (olist_order_items_dataset), o de consumidor (olist_customers_dataset), a de produtos (olist_products_dataset) e a de vendedores (olist_sellers_dataset).

## 📈 Dashboard

Link para consulta do dashboard no tableau Public:

[Dashboard Análise OLIST](https://public.tableau.com/app/profile/carolyne.santos.de.oliveira/viz/on33-python-s15-visualizacao-de-dados-Olist-para-casa/Histria1)

## 📋 Passo a Passo

## 🟦 Análises:

Nesta base de dados, estão disponíveis informações sobre as vendas da Olist, coletadas entre setembro de 2016 e agosto de 2018, abrangendo diversas categorias de produtos em todo o território brasileiro. No gráfico "Quantidade de Produtos por Categoria", podemos observar a distribuição de produtos em cada categoria, permitindo uma análise detalhada da variedade ofertada pela empresa.

![Grafico1](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Qtd.%20Produtos%20por%20Categoria.png)

No segundo gráfico, "Categorias Mais Vendidas", é possível visualizar as cinco categorias com maior volume de vendas. Em primeiro lugar, temos 'cama, mesa e banho', seguido por 'beleza e saúde', em terceiro 'esporte e lazer', em quarto 'informática e acessórios' e, por fim, 'móveis e decoração'. Ao comparar com o gráfico anterior, notamos uma discrepância: apesar de 'informática e acessórios' estar entre as cinco categorias mais vendidas, ela não está entre as cinco com maior número de produtos disponíveis na base de dados. Essa observação indica que, em geral, as categorias com maior número de produtos tendem a ser as que mais vendem, mas há exceções, sugerindo que outros fatores, como demanda e popularidade, também influenciam as vendas.

![Grafico2](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Categ.%20Mais%20Vendida.png)

Na terceira análise, "Quantidade de Pedidos por Estado", a tabela mostra a distribuição de pedidos em cada estado. São Paulo (SP) lidera com o maior número de pedidos, seguido pelo Rio de Janeiro (RJ) em segundo lugar, e Minas Gerais (MG) ocupando a terceira posição. Esses três estados concentram a maior quantidade de pedidos registrados na base de dados, refletindo sua relevância no volume de vendas.

![Grafico3](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Qtd.%20Pedidos%20por%20Estado.png)

No gráfico de barras "Quantidade de Vendedores por Estado", é possível visualizar a distribuição de vendedores por estado, com São Paulo (SP) liderando, seguido pelo Paraná (PR) e, em terceiro lugar, Minas Gerais (MG). Ao comparar este gráfico com a tabela anterior sobre a quantidade de pedidos por estado, percebe-se que os estados com o maior número de vendedores não necessariamente correspondem aos que possuem o maior volume de pedidos. Isso sugere que a presença de muitos vendedores em um estado não garante, por si só, uma alta demanda ou número de vendas.

![Grafico4](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Qtd.%20Vendedor%20por%20Estado.png)

No gráfico de barras "Quantidade Total de Pedidos por Ano", é possível observar claramente que 2018 foi o ano com o maior número de vendas, totalizando 52.783 pedidos. Esse dado destaca 2018 como o ano de melhor desempenho em termos de volume de pedidos na base analisada.

![Grafico5](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Qtd.%20Total%20Pedidos%20por%20Ano.png)

Ao analisarmos a base de dados de forma diferente, utilizando o gráfico de linha "Quantidade de Pedidos por Mês/Ano", podemos observar que faltam informações completas para realizar uma comparação precisa das vendas anuais. Tanto 2016 quanto 2018 não possuem dados para todos os meses, o que pode resultar em análises imprecisas. No entanto, ao compararmos os meses disponíveis de 2017 e 2018, é possível identificar um forte aumento nas vendas em 2018, especialmente nos meses de janeiro a agosto. Isso sugere um crescimento significativo no desempenho de vendas nesse período específico.

![Grafico6](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Qtd.%20Pedidos%20por%20Mes_Ano.png)

No gráfico "Vendas por Mês/Ano", é possível realizar uma análise detalhada mês a mês. Com base nos dados, verificamos que novembro de 2017 foi o mês de maior volume de vendas, registrando um total de 7.289 pedidos. Esse destaque reflete um pico significativo nas vendas durante esse período.

![Grafico7](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Venda%20por%20M%C3%AAs_Ano.png)

No gráfico de dispersão, a análise revela que não há correlação significativa entre o preço dos produtos e o valor do frete. Isso indica que o valor do frete não está diretamente relacionado ao preço dos itens vendidos, sugerindo que outros fatores, como localização ou peso do produto, podem influenciar os custos de envio.

![Grafico8](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Gr%C3%A1fico%20de%20Dispers%C3%A3o.png)

No histograma abaixo, observamos a distribuição dos valores de frete. Após análise, constatamos que a maioria dos produtos apresenta um custo de frete entre R$7 e R$20, indicando uma faixa predominante de preço para o envio de mercadorias na base de dados.

![Grafico9](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Histograma%20Frete.png)

No gráfico de barras abaixo, podemos observar a quantidade de produtos por pedido. A análise revela que, na maioria dos casos, os pedidos contêm apenas um único produto. Essa tendência sugere que os clientes tendem a realizar compras mais específicas em vez de adquirir múltiplos itens por vez. 

![Grafico10](https://github.com/CarolyneS14/on33-python-s15-visualizacao-de-dados/blob/main/Carolyne-Santos/para-casa/Qtd.%20Produto%20por%20Pedido.png)

 ### - Conclusão:

🌟 Com base nos insights apresentados acima, podemos concluir que a análise das vendas da Olist revela padrões interessantes sobre o comportamento dos produtos, estados e o impacto de fatores como quantidade de vendedores e frete.

A primeira análise demonstra que, de maneira geral, as categorias com maior quantidade de produtos disponíveis são também as que mais vendem. No entanto, a exceção "informática e acessórios" nos mostra que uma alta disponibilidade de produtos não necessariamente garante estar entre as categorias mais volumosas de vendas, sugerindo que fatores como popularidade ou sazonalidade podem influenciar.

Ao olhar para a distribuição dos pedidos por estado, fica claro que São Paulo (SP) lidera tanto em número de pedidos quanto em vendedores. Entretanto, outros estados, como Paraná (PR), têm uma alta concentração de vendedores sem refletir necessariamente em um volume de vendas proporcional. Isso indica que ter muitos vendedores ativos em uma região não garante, por si só, a maior quantidade de vendas, o que pode ser influenciado por outros fatores regionais ou logísticos.

Em relação ao desempenho de vendas ao longo do tempo, 2018 foi o ano com o maior volume total de pedidos, mesmo com dados incompletos para todos os meses. A comparação mensal entre 2017 e 2018 reforça a tendência de aumento nas vendas em 2018, especialmente no primeiro semestre, destacando novembro de 2017 como o mês de melhor performance.

A análise de preços e frete mostra que não há uma correlação significativa entre esses dois fatores, e a maioria dos fretes para os produtos vendidos está na faixa de R$7 a R$20, o que pode refletir uma estratégia padrão da empresa ou limitações logísticas. Por fim, a maioria dos pedidos contém apenas um produto, o que sugere que a base de clientes da Olist tende a realizar compras mais específicas, em vez de aquisições em grande volume.

Em síntese, a análise revela que a Olist possui um desempenho sólido em determinadas categorias e regiões, mas existem oportunidades de otimização, especialmente ao considerar as variações regionais em termos de vendedores e pedidos, além da necessidade de uma visão mais completa de dados temporais para evitar conclusões errôneas.
    

## 👩🏻‍🏫 Professora Patrícia Bongiovanni Catandi.
[GitHub](https://github.com/patriciacatandi "Patricia Catandi")
