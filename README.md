# 📊 Análise de Pacientes com Diabetes – Dataset PIMA

## 🧠 Descrição do Projeto
Este projeto tem como objetivo realizar a manipulação e transformação de um conjunto de dados contendo informações de pacientes diagnosticados ou não com diabetes, utilizando **Python**, **SQL** e **Banco de Dados**.

A partir do dataset original, extraímos uma **amostra de pacientes com mais de 50 anos** e realizamos uma **classificação baseada no Índice de Massa Corporal (IMC)**, identificando indivíduos como **normais** ou **obesos**.  

O resultado final é exportado para um novo arquivo CSV, pronto para ser utilizado por um **Cientista de Dados** em análises posteriores.

---

## 🎯 Objetivos
- Filtrar pacientes com **idade superior a 50 anos**
- Criar uma nova coluna de classificação de IMC:
  - **Normal** → IMC < 30  
  - **Obeso** → IMC ≥ 30
- Realizar transformações utilizando **SQL**
- Exportar os dados tratados para um novo arquivo **CSV**

---

## 🗂️ Fonte dos Dados
O conjunto de dados utilizado é o **PIMA Indians Diabetes Database**, amplamente usado em estudos e projetos de análise de dados.

🔗 Fonte oficial:  
https://data.world/data-society/pima-indians-diabetes-database

---

## 🛠️ Tecnologias Utilizadas
- **Python**
  - Pandas
  - SQLite (ou outro banco relacional)
- **SQL**
- **Banco de Dados Relacional**
- **Jupyter Notebook** (se aplicável)

---

## 🔄 Etapas do Processo
1. Importação do dataset utilizando **Python**
2. Criação de uma réplica dos dados em um **Banco de Dados**
3. Filtragem dos pacientes com **idade > 50 anos**
4. Criação da coluna de classificação de IMC via **SQL**
5. Extração dos dados tratados para um **DataFrame Pandas**
6. Exportação do resultado final para um arquivo **CSV**

---
## 📈 Resultado Esperado

Um arquivo CSV contendo:

- Apenas pacientes com mais de 50 anos
- Nova coluna indicando a classificação de IMC
- Dados prontos para análise exploratória ou modelagem

<img width="738" height="229" alt="image" src="https://github.com/user-attachments/assets/160aafb9-1916-4142-b28d-bc9928bef2e2" />


---


