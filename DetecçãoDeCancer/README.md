# Análise e Classificação de Câncer de Mama

Neste código, você encontrará uma análise e classificação de dados de câncer de mama usando o conjunto de dados Breast Cancer, disponível no Scikit-learn. O objetivo é treinar um modelo de Support Vector Machine (SVM) para classificar tumores como benignos ou malignos.

## Importação de Bibliotecas
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.datasets import load_breast_cancer
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.svm import SVC
from sklearn.metrics import classification_report, confusion_matrix, accuracy_score
import seaborn as sns
```

## Conjunto de Dados

- O conjunto de dados utilizado neste projeto contém informações extraídas de biópsias de câncer de mama, incluindo vários atributos descritivos. 
Os dados são divididos em características e rótulos, onde as características são os atributos das células observadas e os rótulos indicam se o tumor era benigno ou maligno.

## Pré-processamento de Dados

- Antes de alimentar os dados ao modelo SVM, eles foram divididos em conjuntos de treinamento e teste. Além disso, 
foi aplicada uma padronização aos dados usando o StandardScaler para garantir que todos os atributos tenham a mesma escala.

## Treinamento do Modelo

- O modelo SVM foi escolhido devido à sua capacidade de lidar eficazmente com problemas de classificação. Ele foi treinado com os dados de treinamento padronizados, usando um kernel linear.

## Avaliação do Modelo

- Após o treinamento, o model o foi avaliado usando os dados de teste. A acurácia foi utilizada como uma métrica inicial para avaliar o desempenho do modelo na classificação. 
A acurácia mede a proporção de previsões corretas em relação ao total de previsões.

## Resultados

- O modelo SVM demonstrou um desempenho promissor, alcançando uma acurácia de 0.96 na classificação dos tumores de câncer de mama. 
No entanto, é importante considerar outras métricas de avaliação, especialmente em contextos médicos, para uma compreensão completa do desempenho do modelo.

## Conclusão

- Este projeto ilustra a aplicação de técnicas de aprendizado de máquina na classificação de câncer de mama.
Embora a acurácia seja alta, é necessário um estudo mais aprofundado para avaliar a robustez do modelo em situações do mundo real e garantir sua eficácia clínica antes da implementação prática.

