<b>Análise de Cesta de Compras (Market Basket Analysis) </b>

<b>Qual é o problema do negócio?</b>

Um varejista quer aumentar suas vendas e para isso necessita saber a correlação entre produtos, para que possa melhor organizar seus produtos no corredores. 

Para isso, foram elencadas 06 perguntas:

1) Qual o Número de Pedidos Mais Frequente Entre os Usuários?
2) Qual Hora do Dia Tem o Maior Número de Pedidos?
3) Quais os 20 Principais Corredores Por Frequência de Pedidos?
4) Quais os 20 Principais Produtos Por Frequência de Pedidos?
5) Qual a relação de Novos Pedidos Semelhantes a Pedidos Anteriores (reorder)
6) Qual o Reorder Por Departamento ao Longo do Tempo?

<b>Fonte de Dados:</b>

https://www.kaggle.com/c/instacart-market-basket-analysis/data

<b>Método utilizado para a solução do problema:</b>

A Análise de Cesta de Compras (Market Basket Analysis) é uma das principais técnicas usadas por grandes varejistas para descobrir associações entre itens. A técnica funciona procurando combinações de itens que ocorrem juntos com frequência nas transações. Em outras palavras, permite que os varejistas identifiquem as relações entre os itens que as pessoas compram.

Inicialmente no notebook são apresentados:

A) Bibliotecas
B) Carregamento dos dados

E a seguir:

Passo 1 - Instalação e Carregamento dos Pacotes
Passo 1 - Carregamento dos Dados
Passo 1 - Análise Exploratória
Passo 1 - Limpeza dos Dados
Passo 1 - Análise Estatística Descritiva
Passo 1 - Implementação do Algoritmo Apriori

<b>Conclusão (primeiro ciclo do CRISP-DM):</b>

Aplicando Matemática e Estatística via programação( Python) foi executada uma análise de MBA gerando como resultado as regras de associação entre os produtos com diferentes métricas.
Após a aplicação do algoritmo Apriori, constatamos que há uma forte relação entre os produtos: Maçã Fuji e Banana.