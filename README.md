# Previsão de Preço de Aluguel de Imóveis 🏠

Projeto de **Machine Learning** desenvolvido no **Google Colab** para prever o preço de aluguel de imóveis brasileiros a partir de características como área, número de quartos, banheiros, vagas e cidade.

---

## Objetivo
Estimar o valor de aluguel de um imóvel com base em atributos físicos e localização, usando um modelo simples de **regressão linear**.

---

## Técnicas utilizadas
- **Pandas** — manipulação de dados  
- **Scikit-learn** — criação e avaliação do modelo  
- **Matplotlib** — visualização da comparação entre valores reais e previstos  

---

## Estrutura do projeto
1. Criação de um dataset simulado com imóveis de **São Paulo, Rio de Janeiro, Belo Horizonte e Curitiba**.  
2. Conversão da variável categórica “cidade” em colunas numéricas (one-hot encoding).  
3. Divisão entre **dados de treino e teste**.  
4. Treinamento de um modelo de **Regressão Linear**.  
5. Avaliação com métricas **MAE** (Erro Médio Absoluto) e **R²**.  
6. Visualização da relação entre valores reais e previstos.

---

## Como executar
1. Abra o arquivo `Previsao_Aluguel_Brasil.ipynb` no **Google Colab**.  
2. Execute as células em sequência (Shift + Enter).  
3. Observe as métricas e o gráfico final comparando previsões e valores reais.  

---

## Exemplo de saída


Gráfico:
- Linha vermelha = previsão ideal (perfeita)  
- Pontos = valores reais x previstos pelo modelo

---

## Conceito básico
O modelo aprende padrões nos dados históricos (área, quartos, cidade etc.) e tenta prever o valor de aluguel mais provável para novas combinações dessas variáveis.

