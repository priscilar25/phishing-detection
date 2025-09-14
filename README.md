# Detecção de Phishing em URLs e Páginas Web

Este projeto explora técnicas de análise de dados e Machine Learning para identificar tentativas de phishing em URLs e páginas da web. O objetivo é construir soluções que auxiliem na detecção desse tipo de ameaça, contribuindo para a segurança digital e a prevenção de ataques.

---

## 🗂️ Origem dos Dados

Os dados analisados neste projeto são provenientes do [UCI Machine Learning Repository - Phishing Websites Data Set](https://archive.ics.uci.edu/ml/datasets/phishing+websites), um dos mais utilizados em pesquisas sobre detecção de phishing.  
O arquivo principal utilizado é o `phishing.csv`, o segundo arquivo `dataset_modelo_phishing.csv` é gerado após análise exploratória.

---

## 📜 Sobre o Projeto

O núcleo do projeto consiste na análise exploratória das características das URLs, seguida da aplicação de diferentes algoritmos de Machine Learning para distinguir páginas legítimas de páginas de phishing. O trabalho abrange desde a limpeza e compreensão dos dados até a avaliação dos modelos preditivos, buscando identificar os padrões mais relevantes para a detecção mais adequada.

---

## 🎯 Objetivos

- Explorar e entender as principais características relacionadas a URLs de phishing.
- Construir pipelines de Machine Learning para classificação automática.
- Avaliar os modelos por métricas como acurácia, recall e F1-score.
- Identificar os padrões mais relevantes utilizados por phishers.
- Compartilhar visualizações e resultados de forma acessível.

---

## 📋 Etapas do Projeto

O desenvolvimento é realizado em Jupyter Notebook, dividido nas seguintes fases principais:

### **Notebook: `deteccao_phishing_eda.ipynb`**

1. **Carregamento e Preparação dos Dados:**
   - Leitura do dataset e tratamento inicial das features.

2. **Análise Exploratória de Dados (EDA):**
   - Exploração estatística, visualização de padrões e identificação das features mais relevantes.

### **Notebook: `deteccao_phishing_ml.ipynb`**

3. **Pré-processamento para Machine Learning:**
   * Seleção de features.
   * Normalização e divisão dos dados em conjuntos para treino e teste.
4. **Aplicação de Algoritmos de Detecção de Anomalias:**

    Experimentação com modelos supervisionados:

   - **Regressão logística**
   - **Random Forest**
   - **SVM(Support Vector Classifier)**
5. **Avaliação dos Resultados:** Análise das métricas de performance e discussão dos principais achados.


## 🛠️ Tecnologias Utilizadas

* **Python 3.13.5**
* **Pandas:** 
* **NumPy:** 
* **Matplotlib & Seaborn:** 
* **Scikit-learn:** 
* **Jupyter Notebook:**

---

## 👤 Autor

* **Priscila Borges** 


