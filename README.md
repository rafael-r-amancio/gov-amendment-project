
[PORTUGUESE]

## 🚀 Projeto Consumo de API com Apache Hop

### 📚 Descrição

Projeto consiste em fazer um pipeline para consumo de API do portal da transparência brasileiro, mapeando e tratando seus campos, visto que a resposta do serviço retorna uma estrtura de JSON.

Como forma de demonstrar os dados extraídos, foi criado um dashboard em Power BI que pode ser acessado neste link: http://bit.ly/4bqaC4l

### 💻 Tecnologias

![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rafael-r-amancio) ![Hop](https://img.shields.io/badge/Hop-white?style=for-the-badge&logo=hop&logoColor=blue) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

### 🚶‍♀️ Passo a Passo

- Necessário ter o Java 11+ para executar o projeto;
- Necessário acessar site do portal da transparência brasileiro e criar um token de acesso a API no endereço https://portaldatransparencia.gov.br/api-de-dados/cadastrar-email e ter uma conta GOV https://www.gov.br/pt-br
- No primeiro passo do pipeline trocar o campos "SEU TOKEN" pelo gerado no passo anterior.
- Necessário ter algum banco de dados para persistência das informações, no projeto foi utilizado SQL Server rodando em um contêiner Docker.
- Fazer a conexão do Apache Hop com o banco de dados, segue documentação: https://bit.ly/4bzueTF
- Realizar criação de um banco e posterior criar tabela (processo pode ser feito pelo Apache Hop)

### ⛲ Fontes

Portal da transparência - https://portaldatransparencia.gov.br

### 💱 Creditos

Imagem Dashboard - https://bit.ly/3wkdJuc (Image by Vectonauta on Freepik)

### 🗣 Fale Comigo

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-ribeiro-amancio/)

<br><br>

[ENGLISH]

## 🚀 API Consumption Project with Apache Hop

### 📚 Description

The project consists of creating a pipeline for consuming the Brazilian transparency portal's API, mapping and processing its fields, as the service's response returns a JSON structure.

As a way to demonstrate the extracted data, a Power BI dashboard was created that can be accessed at this link: http://bit.ly/4bqaC4l

Data dictionary is present in the repository.

### 💻 Technologies

![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rafael-r-amancio) ![Hop](https://img.shields.io/badge/Hop-white?style=for-the-badge&logo=hop&logoColor=blue) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

### 🚶‍♀️ Step by Step

- Java 11+ is required to run the project;
- You must access the Brazilian transparency portal website and create an API access token at https://portaldatransparencia.gov.br/api-de-dados/cadastrar-email and have a GOV account https://www.gov .br/pt-br
- In the first step of the pipeline, exchange the "YOUR TOKEN" field for the one generated in the previous step.
- It is necessary to have a database for information persistence. In the project, SQL Server was used running in a Docker container.
- Connect Apache Hop to the database, follow the documentation: https://bit.ly/4bzueTF
- Create a database and then create a table (process can be done using Apache Hop)

### ⛲ Sources

Transparency portal - https://portaldatransparencia.gov.br

### 💱 Credits

Dashboard Image - https://bit.ly/3wkdJuc (Image by Vectonauta on Freepik)

### 🗣 Talk to Me

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-ribeiro-amancio/)
