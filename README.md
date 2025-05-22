# Neural-Network-MLP
### Repositório com rede neural MLP multipurpose criada do zero com python

- Este código foi criada por mim como estudo de redes neurais supervisionadas MLP. 
- Com o código, tendo um dataset bem estruturado, é possível modelar qualquer problema para classificação via rede neural de modo simples
- Além de funções para classificação e criação de classes automatizadas, há métodos para teste de acurácia como **validação cruzada** e **matriz de confusão**
---
A ferramenta foi criada inteiramente com **Python** e bibliotecas como **Numpy**, **Pandas**, **Matplotlib** entre outras.

## Exemplo presente
Como exemplo do execução do código temos caracteres num display 12x10 pixels traduzidos em vetores linhas na forma bipolar com 120 colunas no arquivo **x_test.csv**;
Já para as respostas há um arquivo nomeado **y_test.scv** listando em letras maiúsculas o que cada umas das linhas representa. *OBS: No código é usado um artifício para transformar as letras em vetores one-hot binários para codificação da rede, uma vez que o modelo aceita apenas números*.
***O teste em si de caracteres com ruídos para predição da rede pós treino está presente a partir da linha 1196 dos datasets***

## Como rodar
Para rodar ou analisar o código, faça o download do arquivo do código e os datasets e os abra num jupyter notebook




