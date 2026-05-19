# Modelagem de IA — FarmTech Solutions
**FIAP — Inteligência Artificial | Fase 3 — Capítulo 10**

## Sobre o projeto
Aplicação de técnicas de aprendizado supervisionado de classificação multiclasse para recomendação de culturas agrícolas com base em variáveis de solo (N, P, K, pH) e clima (temperatura, umidade, precipitação).

## Dataset
- 2200 amostras | 22 culturas | 7 features
- Perfeitamente balanceado (100 amostras por cultura)

## Modelos treinados
| Modelo | Acurácia | F1-macro |
|---|---|---|
| Random Forest | 0.9955 | 0.9955 |
| SVM (RBF) | 0.9841 | 0.9840 |
| KNN (k=5) | 0.9795 | 0.9793 |
| Regressão Logística | 0.9727 | 0.9725 |
| Decision Tree | 0.9636 | 0.9639 |

## Estrutura do notebook
1. Setup e leitura do dataset
2. Análise Exploratória (EDA)
3. Análise Descritiva com 6 visualizações
4. Perfil ideal de solo/clima e comparação entre culturas
5. Modelagem preditiva com 5 algoritmos
6. Conclusões

## Grupo
- Lucas Carvalho Cordeiro — RM570388
- Brenoezo Leardini — RM572533
- Abner Henrique Dias Rosa Sanches — RM572253
- Elton Modesto de Souza Dias — RM572530
- Larissa da Silva Marcelino — RM571790

## Tecnologias
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)
