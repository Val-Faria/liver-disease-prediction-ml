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
