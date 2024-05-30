# Previsão de Despesas dos Clientes #
Este projeto foi desenvolvido como parte da minha jornada de aprendizado em ciência de dados e machine learning. O objetivo principal foi analisar e entender os padrões de consumo dos clientes e construir um modelo preditivo robusto para antecipar suas despesas futuras.

## Descrição do Projeto ##
Este projeto envolve várias etapas essenciais de um pipeline de ciência de dados:

### Análise Exploratória dos Dados (EDA): ###
* Investigação das características básicas dos dados.
* Identificação e tratamento de valores nulos.
* Análise da distribuição de renda e gastos dos clientes.
* Exploração da relação entre variáveis demográficas e comportamentais.

### Análise Estatística: ###
* Cálculo de correlações para entender as relações entre renda, número de filhos e gastos.
* Testes estatísticos (t-test, ANOVA de Welch) para verificar diferenças significativas nos gastos entre diferentes grupos de clientes.

### Modelo de Machine Learning: ###
* Seleção de features relevantes.
* Divisão dos dados em conjuntos de treino e teste.
* Otimização de hiperparâmetros utilizando RandomizedSearchCV.
* Construção e avaliação de um modelo XGBoost.

### Visualização de Resultados: ###
* Plotagem de gráficos para ilustrar a distribuição de renda e gastos.
* Visualização das importâncias das features no modelo preditivo.

### Resultados e Insights ###
* Distribuição de Renda: A maioria dos clientes possui uma renda entre $35,000 e $68,000, com uma variabilidade significativa.
* Gastos dos Clientes: Identificamos que a média de despesas é de $562.7, com outliers influenciando significativamente a média.
* Correlação entre Renda e Gastos: Observamos uma forte correlação positiva (0.82), indicando que clientes com rendas mais altas tendem a gastar mais.
* Impacto dos Filhos nos Gastos: Clientes sem filhos tendem a gastar mais que aqueles com filhos, com diferenças significativas dependendo do número de filhos.
* Eficácia das Campanhas de Marketing: A Campanha 4 se destacou como a mais aceita entre os clientes.
* Modelo Preditivo: O modelo XGBoost desenvolvido possui um R² de 0.997, demonstrando alta capacidade preditiva.

## Conclusão ##
Este projeto oferece uma visão abrangente do comportamento de consumo dos clientes e mostra o poder da ciência de dados para gerar insights valiosos e criar modelos preditivos eficazes. Sinta-se à vontade para explorar o código.
