# **`Predição Desempenho ENEM`**

## Objetivo
Criar um modelo de predição para a nota média de desempenho no Enem, utilizando dados socieconômicos e do participante.

## Etapas Realizadas
- Pré-Processamento de dados utilizando OneHotEncoder, Target Enconding e Standard Scaler
- Treinamento de Modelos de Árvores de Decisão
- Otimização de Hiperparâmetros utilizando Validação Cruzada
- Boruta para Feature Selection
- Valores Shapley para importância das variáveis na predição

## Resultado Final
- O modelo criado possui erro quadrático médio de 70 pontos. Enquanto o desvio padrão da variável é de 88 pontos.

Obs: A otimização de hiperparâmetros foi realizada de maneira não exaustiva. Devem existir combinações melhores que minizem ainda mais a função de risco.
