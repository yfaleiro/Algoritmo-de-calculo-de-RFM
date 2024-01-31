# Cálculo de RFM para e-commerce

## Objetivo
Analisar base de dados de uma empresa do ramo de e-commerce e calclar os indicadores de RFM (Recência, Frequencia e Ticket Médio. O output desse trabalho deve ser um arquivo também em .csv, porem constando apenas a identificação do cliente e as métricas de RFM. Para chegar ao objetivo, faremos os processos de data cleaning, tratando nulos, duplicados e outliers, antes de partimos para o data wrangling, onde calcularemos o RFM e os inseriremos no output final da base de dados.

## Disclaimer
Foi informado pelo cliente hipotético que valores faltantes na identificação do cliente deverão ser removidos. Além disso, valores negativos em preço unitário (UnitPrice) e quantidade (Quantity) também deverão ser removidos. Linhas duplicadas também deverão ser removidas visto que é muito improvavel que o mesmo cliente faça um pedido identico em valor e quantidade na mesmo dia e hora.

Além disso, foi solicitado para que os outliers sejam considerados como erro e removidos da base, sendo considerado como outlier dados em que a quantidade é acima de 10.000 e o preço unitário é maior que 5.000.

## Método utilizado
Bibliotecas:

Pandas para análise descritiva e preparação e limpeza dos dados;

Seaborn para análise descritiva;

## Resultado
Como resultado, o algoritmo será capaz de calcular automáticamente o RFM do e-commerce trazendo a seguinte base como output:
![image](https://github.com/yfaleiro/Algoritmo-de-calculo-de-RFM/assets/116303455/fe316d72-e1cd-4ff4-86a2-85c634858c06)

