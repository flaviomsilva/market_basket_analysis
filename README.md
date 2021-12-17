<b>Análise de Cesta de Compras (Market Basket Analysis) </b>

O conjunto de dados (anônimo)  descreve os pedidos dos clientes ao longo do tempo.

<b>Qual é o problema do negócio?</b>

Prevê  quais produtos estarão no próximo pedido de um usuário.
Para isso, foram elencadas 06 perguntas:
<li>
	<ul>1) Qual o Número de Pedidos Mais Frequente Entre os Usuários?</ul>
	<ul>2) Qual Hora do Dia Tem o Maior Número de Pedidos?</ul>
	<ul>3) Quais os 20 Principais Corredores Por Frequência de Pedidos?</ul>
	<ul>4) Quais os 20 Principais Produtos Por Frequência de Pedidos?</ul>
	<ul>5) Qual a relação de Novos Pedidos Semelhantes a Pedidos Anteriores (reorder)</ul>
	<ul>6) Qual o Reorder Por Departamento ao Longo do Tempo?</ul>
</li>
<b>Fonte de Dados:</b>

https://www.kaggle.com/c/instacart-market-basket-analysis/data

<b>Método utilizado para a solução do problema:</b>

A Análise de Cesta de Compras (Market Basket Analysis) é uma das principais técnicas usadas por grandes varejistas para descobrir associações entre itens. A técnica funciona procurando combinações de itens que ocorrem juntos com frequência nas transações. Em outras palavras, permite que os varejistas identifiquem as relações entre os itens que as pessoas compram.

Inicialmente no notebook são apresentados:

<li>
	<ul>A) Bibliotecas</ul>
	<ul>B) Carregamento dos dados</ul>
</li>

E a seguir:

<li>
<ul>Passo 1 - Instalação e Carregamento dos Pacotes</ul>
<ul>Passo 1 - Carregamento dos Dados</ul>
<ul>Passo 1 - Análise Exploratória</ul>
<ul>Passo 1 - Limpeza dos Dados</ul>
<ul>Passo 1 - Análise Estatística Descritiva</ul>
<ul>Passo 1 - Implementação do Algoritmo Apriori</ul>
</li>

<b>Conclusão (primeiro ciclo do CRISP-DM):</b>

Aplicando Matemática e Estatística via programação( Python) foi executada uma análise de MBA gerando como resultado as regras de associação entre os produtos com diferentes métricas.
Após a aplicação do algoritmo Apriori, constatamos que há uma forte relação entre os produtos: Maçã Fuji e Banana.