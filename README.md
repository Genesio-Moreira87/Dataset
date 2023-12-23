# Dataset

# Análise Econômica Global

## Coleta de Dados
### Fonte dos Dados
Os dados foram obtidos a partir da [https://www.kaggle.com/datasets/mittvin/world-economic-indicators-1960-2022-dataset].

### Pré-processamento
1. Remoção de dados ausentes.
2. Preenchimento de valores faltantes com a média (ou outra estratégia, se aplicável).
3. Conversão de tipos de dados.

## Modelagem
### Análise Exploratória
1. Visualização da distribuição das variáveis.
2. Matriz de correlação entre as variáveis.
3. Identificação de tendências ao longo do tempo.

### Desenvolvimento do Modelo de Previsão
1. Escolha do algoritmo de aprendizado de máquina.
2. Divisão do conjunto de dados em treino e teste.
3. Treinamento do modelo.
4. Avaliação do desempenho do modelo.

## Conclusões
### Correlações Identificadas
- A taxa de desemprego parece ter uma correlação negativa com o crescimento do PIB.
- Remessas pessoais recebidas não mostram uma correlação clara com a taxa de desemprego.

### Previsão do Desemprego
- O modelo de previsão tem uma precisão moderada (R^2 = 0.4).
- Variáveis como crescimento do PIB e remessas pessoais têm contribuições significativas.

### Comparação de Países
- Brasil, EUA e China destacam-se com desempenho econômico notável.
- Visualizações mostram tendências de crescimento ou declínio ao longo dos anos.

## Simulações e Testes Adicionais
- Simulação 1: Aumento de 10% nas remessas pessoais e seu impacto na taxa de desemprego.
- Simulação 2: Redução no crescimento do PIB e como isso afeta o desemprego.
- Teste 1: Avaliação do modelo com dados de 2020 para verificar a robustez.

## Limitações e Melhorias Futuras
- **Limitações nos Dados:**
  - Dados ausentes para alguns países ou anos podem limitar a análise nesses períodos.
  - Diferenças na qualidade dos dados entre países podem afetar a precisão das comparações.

- **Limitações no Modelo:**
  - A simplicidade do modelo pode não capturar todos os nuances do mercado de trabalho.
  - A variabilidade econômica global pode exigir modelos específicos para diferentes regiões.

- **Melhorias Futuras:**
  - Incorporar dados adicionais, como indicadores sociais e políticos.
  - Explorar modelos mais avançados, como redes neurais, para previsões mais complexas.
  - Realizar análises setoriais para insights mais granulares.

Objetivos:

Identificar Correlações: Analisar as correlações entre as variáveis fornecidas (Remessas Pessoais Recebidas, Desemprego, PIB e Crescimento do PIB).

Previsão do Desemprego: Desenvolver um modelo de aprendizado de máquina para prever a taxa de desemprego com base nas outras variáveis. Variavel resposta 'Total Unemployment (% of total labor force'

Comparação de Países: Comparar o desempenho econômico de diferentes países ao longo dos anos.
