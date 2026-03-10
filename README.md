# Telecom_X

## 🧠 Sobre o Projeto

Este projeto analisa dados da empresa fictícia **TelecomX**, uma operadora de telecomunicações que enfrenta um problema de **cancelamento de clientes (churn)**.

A proposta é utilizar **análise exploratória de dados (EDA)** para entender melhor o comportamento dos clientes e descobrir quais fatores podem estar relacionados ao cancelamento dos serviços.

O trabalho segue um fluxo comum em projetos de análise de dados: **importação dos dados, tratamento, exploração das informações e apresentação dos resultados**.

---

## 🎯 Objetivos

* Examinar como o churn aparece na base de clientes;
* Identificar características comuns entre clientes que cancelam;
* Verificar a relação entre churn e algumas variáveis do dataset;
* Apresentar insights que possam ajudar a reduzir cancelamentos.

---

## 🛠️ Ferramentas Utilizadas

* **Python**
* **Pandas** — tratamento e manipulação de dados
* **Matplotlib e Seaborn** — criação de gráficos
* **Google Colab** — ambiente de desenvolvimento
* **Git e GitHub** — controle de versão e publicação

---

## 📂 Estrutura do Projeto

```id="telecomxestrutura"
📁 telecomx-churn-analysis

├── 📄 TelecomX_Data.json      # Base de dados original
├── 📄 notebook.ipynb          # Notebook com a análise
├── 📄 README.md               # Documentação do projeto
```

---

## 🔄 Etapas da Análise

### 1️⃣ Importação dos Dados

Carregamento do dataset em formato **JSON**.

### 2️⃣ Preparação dos Dados

* Ajuste de categorias inconsistentes;
* Conversão de colunas para tipos corretos;
* Tratamento de valores ausentes;
* Criação da variável **Contas_Diarias** para análise de custo diário.

### 3️⃣ Exploração dos Dados

Foram analisadas relações entre churn e algumas variáveis, como:

* tipo de contrato
* serviços adicionais
* método de pagamento
* tempo de permanência
* valores cobrados

Diversos gráficos foram utilizados para facilitar a visualização dessas relações.

### 4️⃣ Síntese dos Resultados

Organização dos principais achados e recomendações com base nas análises realizadas.

---

## 📈 Principais Observações

Alguns padrões foram identificados durante a análise:

* contratos **Month-to-month** apresentam maior cancelamento;
* clientes com **pouco tempo de permanência** cancelam mais;
* valores mensais mais altos aparecem com frequência entre churners;
* ausência de serviços extras aumenta a probabilidade de evasão;
* pagamento via **Electronic Check** aparece em muitos cancelamentos.

---

## 📌 Considerações Finais

A análise indica que fatores como **tipo de contrato, preço e serviços adicionais** influenciam diretamente o churn.

Essas informações podem auxiliar na criação de **estratégias para retenção de clientes** e melhoria dos serviços oferecidos.

---

## 🚀 Possíveis Melhorias Futuras

* criação de um **modelo preditivo de churn**;
* técnicas de **balanceamento de dados**;
* criação de novas variáveis relevantes;
* avaliação de modelos de classificação.

---

## 👤 Autor

**Bruno Trindade**

Projeto desenvolvido para **estudo e prática em análise de dados**.

---

