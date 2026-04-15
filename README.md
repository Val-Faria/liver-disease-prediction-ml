# 🧠 Liver Disease Prediction ML

Projeto de Machine Learning com o objetivo de prever a presença de doença hepática com base em dados clínicos.

---

## 📊 Sobre o Projeto

Este projeto acadêmico utiliza técnicas de análise de dados e aprendizado de máquina para identificar padrões em exames clínicos, permitindo prever se um paciente possui ou não doença hepática.

---

## 📁 Dataset

O conjunto de dados contém informações laboratoriais e demográficas dos pacientes, como:

- Age  
- Total_Bilirubin  
- Direct_Bilirubin  
- Alkaline_Phosphotase  
- Alamine_Aminotransferase  
- Aspartate_Aminotransferase  
- Total_Proteins  
- Albumin  
- Albumin_and_Globulin_Ratio  

A variável alvo (**Dataset**) indica a presença (1) ou ausência (0) de doença hepática.

---

## 🔍 Etapas do Projeto

- Análise exploratória dos dados (EDA)  
- Análise de correlação entre variáveis  
- Tratamento e preparação dos dados  
- Separação entre treino e teste  
- Normalização dos dados  
- Treinamento com Regressão Logística  
- Avaliação do modelo  

---

## ⚙️ Modelo Utilizado

Foi utilizado o modelo de **Regressão Logística**, com ajuste para lidar com desbalanceamento de classes:

```python
LogisticRegression(class_weight='balanced')

## 📈 Avaliação do Modelo

O modelo foi avaliado utilizando as seguintes métricas:

- **Acurácia** → desempenho geral  
- **Recall** → capacidade de identificar casos positivos  
- **F1-score** → equilíbrio entre acertos e erros  

📌 O recall foi priorizado, pois o problema envolve saúde,  
onde é mais importante reduzir falsos negativos.

---

## ⚠️ Resultados

O modelo apresentou:

- Recall: ~0.74  
- F1-score: ~0.74  

Isso indica que o modelo consegue identificar boa parte dos casos de doença,  
porém ainda deixa de detectar uma parcela relevante,  
o que pode ser crítico em um contexto clínico.

---

## 🚀 Próximos Passos

- Testar outros algoritmos (KNN, Random Forest)  
- Ajustar hiperparâmetros  
- Tratar multicolinearidade  
- Melhorar o recall do modelo  

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📌 Considerações Finais

O projeto demonstra a aplicação de técnicas de Machine Learning  
em um problema real da área da saúde, destacando a importância  
da escolha adequada de métricas e da interpretação dos resultados  
para tomada de decisão.
