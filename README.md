Analise de dados da rede de lojas Alura Store

Este projeto tem como objetivo ajudar o Sr. João, dono da rede de lojas Alura Store, a decidir qual das suas quatro lojas vender, com base no desempenho de vendas.

Propósito da Análise

Sr. João pretende vender uma das lojas para investir em um novo negócio. Para analisar os dados de vendas e identificar qual loja apresenta o menor desempenho em comparação com as demais, foram utilizados métricas como:

Faturamento total de cada loja

Vendas por categoria

Média de Avaliação por Loja

Produtos Mais e Menos Vendidos em cada loja

Frete Médio por Loja


Estrutura do Projeto

alura-store/
│
├── dados/  
                                   # Arquivos CSV com os dados de vendas
│   └── vendas_lojas.csv
│
├── notebook/                      # Notebook com a análise

│   └── analise_dados_alura_store.ipynb
│
├── imagens/                       # Gráficos gerados na análise

│   ├── faturamento_por_loja.png
│   └── media_avaliacao_por_loja.png
│   └── frete_medio_por_loja.png

└── README.md                      # Documentação do projeto


Exemplos de Gráficos e Insights

Faturamento por Loja

Insight: As Lojas 1 e 4 teve o menor faturamento total no período analisado.

Média de Avaliação por Loja

Insight: A Loja 1 também apresentou menor media de avaliação.

Frete Médio por Loja

Insight: As Lojas 1 e 4 apresentaram menor media de fretes.


Como Executar o Notebook

1. Clone o repositório:

git clone https://github.com/jaqueline-quaresma/analise_dados_alura_store

cd analise_dados_alura-store

2. Instale as dependências necessárias (opcional):

    pip install pandas matplotlib seaborn jupyter

4. Execute o notebook:

jupyter notebook notebook/analise_dados_alura_store.ipynb

Seguindo as instruções será possível, acompanhar toda análise feita para apoiar a decisão do seu João.

   







