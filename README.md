# Abalone Age Prediction using Linear Regression

🇧🇷 Português | 🇺🇸 English

---

# 🇧🇷 Português

## 📖 Sobre o Projeto

Este projeto tem como objetivo estimar a idade de abalones a partir de características biométricas utilizando técnicas de Machine Learning.

O conjunto de dados utilizado foi o Abalone Dataset, amplamente empregado em estudos de regressão e aprendizado de máquina. A idade do abalone é estimada a partir do número de anéis presentes em sua concha, representados pela variável Rings.

---

## Objetivo

Desenvolver um modelo de regressão capaz de prever a idade dos abalones utilizando medidas físicas como:

* Length
* Diameter
* Height
* Whole Weight
* Shucked Weight
* Viscera Weight
* Shell Weight

---

## Dataset

O dataset contém informações biométricas de abalones e é amplamente utilizado para estudos de regressão.

### Variáveis Utilizadas

| Variável       | Descrição                          |
| -------------- | ---------------------------------- |
| Sex            | Sexo do abalone (M, F ou I)        |
| Length         | Comprimento                        |
| Diameter       | Diâmetro                           |
| Height         | Altura                             |
| Whole Weight   | Peso total                         |
| Shucked Weight | Peso sem casca                     |
| Viscera Weight | Peso das vísceras                  |
| Shell Weight   | Peso da concha                     |
| Rings          | Número de anéis (idade aproximada) |

---

## Análise Exploratória dos Dados

Foram realizadas:

* Estatísticas descritivas;
* Verificação de valores ausentes;
* Gráficos de dispersão;
* Histogramas;
* Comparações entre os sexos dos abalones.

---

## Modelo Utilizado

### Regressão Linear

Variáveis preditoras:

* Length
* Diameter
* Height
* Whole Weight
* Shucked Weight
* Viscera Weight
* Shell Weight

Variável alvo:

* Rings

---

## Validação Cruzada

Foi utilizada a técnica K-Fold Cross Validation com 5 partições.

Em cada execução:

* 80% dos dados foram utilizados para treinamento;
* 20% dos dados foram utilizados para teste;
* O processo foi repetido 5 vezes.

---

## Resultados

| Fold | RMSE   | R²     |
| ---- | ------ | ------ |
| 1    | 2.2485 | 0.5330 |
| 2    | 2.1553 | 0.4822 |
| 3    | 2.3523 | 0.5244 |
| 4    | 2.3904 | 0.5198 |
| 5    | 2.0329 | 0.5167 |

### Resultado Médio

* RMSE Médio ≈ 2.24
* R² Médio ≈ 0.51

---

## Conclusão

O modelo foi capaz de explicar aproximadamente 51% da variabilidade da idade dos abalones, apresentando um erro médio de aproximadamente 2,24 anéis.

Os resultados foram consistentes entre os folds, indicando boa estabilidade e capacidade de generalização.

---

# 🇺🇸 English

## About the Project

This project aims to estimate the age of abalones using biometric measurements and Machine Learning techniques.

The dataset used is the well-known Abalone Dataset, commonly employed in regression and predictive modeling studies. Abalone age is estimated through the number of shell rings, represented by the Rings variable.

---

## Objective

Build a regression model capable of predicting abalone age based on physical measurements such as:

* Length
* Diameter
* Height
* Whole Weight
* Shucked Weight
* Viscera Weight
* Shell Weight

---

## Dataset

The dataset contains biometric measurements of abalones and is widely used in machine learning research.

### Features

| Feature        | Description                     |
| -------------- | ------------------------------- |
| Sex            | Abalone sex (M, F, or I)        |
| Length         | Longest shell measurement       |
| Diameter       | Diameter measurement            |
| Height         | Height measurement              |
| Whole Weight   | Total weight                    |
| Shucked Weight | Meat weight                     |
| Viscera Weight | Gut weight                      |
| Shell Weight   | Shell weight                    |
| Rings          | Number of rings (age indicator) |

---

## Exploratory Data Analysis

The project includes:

* Descriptive statistics;
* Missing value analysis;
* Scatter plots;
* Histograms;
* Visual comparison among sex categories.

---

## Model

### Linear Regression

Input variables:

* Length
* Diameter
* Height
* Whole Weight
* Shucked Weight
* Viscera Weight
* Shell Weight

Target variable:

* Rings

---

## Cross Validation

The model was evaluated using 5-Fold Cross Validation.

For each fold:

* 80% of the data was used for training;
* 20% was used for testing;
* The process was repeated five times.

---

## Results

| Fold | RMSE   | R²     |
| ---- | ------ | ------ |
| 1    | 2.2485 | 0.5330 |
| 2    | 2.1553 | 0.4822 |
| 3    | 2.3523 | 0.5244 |
| 4    | 2.3904 | 0.5198 |
| 5    | 2.0329 | 0.5167 |

### Average Performance

* Average RMSE ≈ 2.24
* Average R² ≈ 0.51

---

## Conclusion

The Linear Regression model was able to explain approximately 51% of the variance in abalone age while maintaining an average prediction error of about 2.24 rings.

The consistency across folds suggests good model stability and generalization capability.

---

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Author

Flávia Vitória de Queiroz

