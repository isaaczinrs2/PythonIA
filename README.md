# 🧠 Projeto de IA: Classificação de Score de Crédito

Este projeto utiliza técnicas de Machine Learning para classificar o score de crédito de clientes em três categorias: **Ruim**, **Ok** e **Bom**. O objetivo é auxiliar instituições financeiras na avaliação de risco de crédito, automatizando a análise com base em dados históricos dos clientes.

## 📊 Objetivo

Desenvolver um modelo de aprendizado de máquina capaz de prever o score de crédito de novos clientes, com base em informações como idade, profissão, salário anual, número de contas, histórico de pagamentos, entre outras variáveis relevantes.

## 🛠️ Tecnologias Utilizadas

* Python 3.13
* Pandas
* Scikit-learn
* Jupyter Notebook

## 🔍 Etapas do Projeto

1. **Importação e Visualização dos Dados**

   * Leitura dos dados dos clientes a partir do arquivo `clientes.csv`.
   * Análise exploratória para compreensão das variáveis disponíveis.

2. **Pré-processamento dos Dados**

   * Codificação de variáveis categóricas utilizando `LabelEncoder`.
   * Separação dos dados em variáveis independentes (features) e dependente (target).

3. **Divisão dos Dados**

   * Separação dos dados em conjuntos de treino e teste utilizando `train_test_split`.

4. **Treinamento dos Modelos**

   * Treinamento de dois modelos:

     * Random Forest Classifier
     * K-Nearest Neighbors (KNN)

5. **Avaliação dos Modelos**

   * Avaliação da acurácia dos modelos utilizando `accuracy_score`.
   * Seleção do modelo com melhor desempenho para aplicação futura.

6. **Previsão para Novos Clientes**

   * Aplicação do modelo treinado para prever o score de crédito de novos clientes a partir do arquivo `novos_clientes.csv`.

## 📈 Resultados

* **Random Forest Classifier**: Acurácia de 83.04%
* **K-Nearest Neighbors**: Acurácia de 74.41%

O modelo de Random Forest apresentou melhor desempenho e foi selecionado para realizar as previsões nos novos dados.

## 🚀 Como Executar o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/isaaczinrs2/PythonIA.git
   cd PythonIA
   ```

2. Crie um ambiente virtual e ative-o:

   ```bash
   python -m venv venv
   source venv/bin/activate  # Para Linux/Mac
   venv\Scripts\activate  # Para Windows
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Execute o notebook:

   ```bash
   jupyter notebook notebooks/inicial.ipynb
   ```

## 📚 Referências

* [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
* [Pandas Documentation](https://pandas.pydata.org/docs/)

---
