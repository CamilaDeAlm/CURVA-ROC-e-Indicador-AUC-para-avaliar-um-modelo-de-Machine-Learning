# Curva ROC e Indicador AUC

A curva ROC (Receiver Operating Characteristic) e o indicador AUC (Area Under the Curve) são ferramentas usadas para avaliar o desempenho de modelos de classificação, especialmente quando 
há uma classe positiva e uma classe negativa. Ela vem do modelo de logística Binária, que possui variável dependente qualitativa e com duas categorias (Dummy).

O dataset contém dados sobre a possibilidade do desenvolvimento de doenças cardíacas e o caderno foi desenvolvido baseado em uma aula do canal Nerd dos Dados.

## Curva ROC

A curva ROC é um gráfico que ilustra o desempenho de um modelo de classificação ao variar o limiar de decisão.

Eixo X (FPR - False Positive Rate): Representa a taxa de falsos positivos (ou seja, a proporção de negativos que foram incorretamente classificados como positivos).

Eixo Y (TPR - True Positive Rate): Representa a taxa de verdadeiros positivos (ou seja, a proporção de positivos que foram corretamente classificados).

Cada ponto na curva ROC corresponde a um limiar de decisão diferente, mostrando a troca entre a taxa de verdadeiros positivos e a taxa de falsos positivos. Quanto mais a curva se 
aproxima do canto superior esquerdo do gráfico, melhor o modelo é considerado, pois indica uma alta taxa de verdadeiros positivos e uma baixa taxa de falsos positivos.
<div align="center">
  <img src="https://github.com/CamilaDeAlm/CURVA-ROC-para-AVALIAR-um-modelo-de-Machine-Learning/blob/main/folder/Captura%20de%20tela%202024-08-30%20154307.png" alt="Exemplo" 
    width="largura" height="altura">
</div>

## Indicador AUC
O AUC é o valor numérico que representa a área sob a curva ROC. Ele varia de 0 a 1 e quantifica o desempenho geral do modelo:

 - AUC = 0.5: O modelo não tem capacidade discriminativa (equivalente a uma classificação aleatória).
- AUC < 0.5: O modelo tem desempenho pior do que o acaso, o que significa que está invertendo as classes.
- AUC > 0.5: O modelo tem algum poder discriminatório, com 1.0 sendo o valor perfeito (todos os positivos são corretamente classificados como positivos, e todos os negativos são
corretamente classificados como negativos).

<div align="center">
  <img src="https://github.com/CamilaDeAlm/CURVA-ROC-para-AVALIAR-um-modelo-de-Machine-Learning/blob/main/folder/Captura%20de%20tela%202024-08-30%20154321.png" alt="Exemplo" width="largura" height="altura">
</div>

FIM.
