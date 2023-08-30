# Análise e Classificação de Dados da Iris

Este repositório contém um notebook Jupyter com um código para realizar análise exploratória e classificação de dados usando o conjunto de dados Iris. O conjunto de dados Iris é um conjunto clássico de dados frequentemente usado para demonstrar técnicas de análise de dados e aprendizado de máquina.

## Notebook do Google Colab
Você pode visualizar e executar o notebook diretamente no Google Colab. [Clique aqui para abrir o notebook no Google Colab](https://colab.research.google.com/github/Thiago1alberto/colab/blob/main/Aprendizado.ipynb).

## Dependências
Certifique-se de ter as seguintes bibliotecas instaladas:
- numpy
- pandas
- seaborn
- matplotlib.pyplot
- scikit-learn
- tensorflow.keras

## Conteúdo do Notebook

### 1. Importação de Bibliotecas
```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.datasets import load_iris
from sklearn.preprocessing import MinMaxScaler
from tensorflow.keras.utils import to_categorical
from sklearn.model_selection import train_test_split
from sklearn.neural_network import MLPClassifier
from sklearn.metrics import accuracy_score
```
## Pré-processamento e Classificação
- O restante do notebook inclui o pré-processamento dos dados, a divisão em conjuntos de treinamento e teste, a normalização dos recursos, a codificação das variáveis de destino e a criação e avaliação de um classificador MLP (Multilayer Perceptron).

## Execução do Notebook
- Você pode executar o notebook no ambiente do Google Colab, que fornece um ambiente de execução Python com acesso a bibliotecas populares de análise de dados e aprendizado de máquina.

## Observações
- Este é um exemplo básico de análise e classificação de dados usando o conjunto de dados Iris. Sinta-se à vontade para explorar mais técnicas de análise, visualização e modelagem, bem como para adaptar o código para seus próprios projetos.
