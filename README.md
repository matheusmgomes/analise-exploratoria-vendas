# Análise Exploratória de Dados de Vendas

Projeto da aula PY-06 para praticar Análise Exploratória de Dados (EDA) com Python.

## Arquivos

- `PY-06_EDA_Vendas_Colab.ipynb`: notebook com inspeção, engenharia de atributos, visualizações e atividade.
- `sales_data.csv`: conjunto de dados usado na análise.
- `sales_data_analisado.csv`: saída opcional gerada pelo notebook.

## Bibliotecas

Pandas, NumPy, Matplotlib e Seaborn.

## Como executar

1. Abra o notebook no VSCode ou Google Colab. (Em caso de uso do VSCode, selecionar o kernal com as ferramentas necessárias instaladas)
2. Execute as células na ordem.
3. Na etapa de upload, selecione `sales_data.csv`. (No VSCode, apenas indicar onde está o arquivo)
4. Complete a atividade e registre as conclusões.

## Análises realizadas

- inspeção de estrutura, tipos, ausências e duplicidades;
- criação de atributos temporais, lucro, margem e faixa de vendas;
- resumo por região e por dia da semana;
- histogramas, dispersão, pairplot e gráfico de barras;
- recomendações baseadas nos resultados.

## Principais conclusões

**Principal padrão observado:**  
Possível notar que as vendas são altas no início da semana (segunda e terça), porém têm uma queda considerável nos dias decorrentes.

**Cuidado com a conclusão:**  
A análise leva em conta apenas 10 dias no mês, portanto é uma amostra bem pequena do que pode acontecer. Algumas conclusões podem não se aplicar com mais amostras de dados.

**Recomendação 1 — aproveitar dias fortes:**  
Manter o que vêm sendo feito.

**Recomendação 2 — desenvolver dias fracos:**  
Criar promoções, principalmente nos fins de semanas onde o público está mais disponível a ir às compras.
