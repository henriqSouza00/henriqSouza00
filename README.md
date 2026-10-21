# Olá, eu sou o Henrique Souza 👋

**Data Engineer · SQL · ETL · Data Quality** — São Paulo, SP

Trabalho com **migração e qualidade de dados** em ambientes de produção: levo dados de sistemas legados para bases novas, encontro inconsistências antes que virem problema e garanto que o que chega no destino bate com a origem.

## 🛠️ O que eu faço no dia a dia

- **Migração de dados** entre sistemas (Firebird → MySQL), com tabelas de staging e cargas reprocessáveis
- **Validação e reconciliação**: comparo origem × destino (contagens, valores, órfãos, duplicados) e documento cada divergência
- **Correção de dados em produção** com SQL seguro: conferência antes de alterar, backup e roteiro de execução
- **Investigação de causa raiz** quando um relatório ou documento sai errado: rastreio do dado até a origem

## 🧰 Tecnologias

![SQL](https://img.shields.io/badge/SQL-avançado-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Firebird](https://img.shields.io/badge/Firebird-F40F02?style=flat-square&logo=firebird&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## 📂 Projetos

### [Migration Validator](https://github.com/henriqSouza00/migration-validator)
Valida uma migração de dados comparando **origem × destino**: registros faltando, sobrando ou duplicados, valores diferentes coluna a coluna, somas financeiras e regras que precisam voltar vazias (parcelas órfãs, CPF repetido). Gera relatório em Markdown e tem testes com bases fictícias cheias de defeitos conhecidos.

`Python` `SQLAlchemy` `SQL` `pytest` `Data Quality`

### [ETL Data Pipeline com Python](https://github.com/henriqSouza00/etl-data-pipeline-python)
Pipeline completo que consome a API pública do IBGE, trata os dados com **pandas**, carrega em **SQLite ou MySQL** e alimenta um **dashboard no Power BI**.
Estrutura em camadas (extract / transform / load), configuração por `.env`, logging e consultas SQL de análise.

`Python` `pandas` `SQL` `MySQL` `Power BI`

### 🔜 Em construção
- **Deduplicação de pessoas**: achar o mesmo cadastro com grafias diferentes, sem juntar homônimos
- **Firebird → MySQL com Python**: extração, transformação, carga e conferência automática

## 📈 Aprendendo agora

Python para engenharia de dados e **Apache Spark**.

## 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-henrique--souza99-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/henrique-souza99)
