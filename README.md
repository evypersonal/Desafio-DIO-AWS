# Arquiteturas AWS - Diagramas e Demonstrações

Este repositório contém diagramas e vídeos explicativos de arquiteturas AWS utilizando diferentes serviços.  
Com propósito de concluir o desafio proposto pela DIO.

Abaixo, a sequência de evolução de cada arquitetura:

---

## Arquitetura 1 - **EC2 + EBS**

### 📌 Diagrama 1  
Representação da utilização do **EC2** em conjunto com o **EBS**, demonstrando a criação da instância e a ligação do volume para persistência de dados.

![Diagrama EC2 + EBS](/ec2/Desafio-v1-EC2.png)

### 🎥 Diagrama **EC2 + EBS** Finalizado  
GIF apresentando o **fluxo finalizado** da arquitetura EC2 + EBS.  

![Diagrama EC2 + EBS](/ec2/Desafio-v2-EC2.gif)

---

## Arquitetura 2 - **Lambda + S3 + Cognito + DynamoDB + CloudWatch**

### 📌 Diagrama 1  
Utilização do **Lambda** integrado ao **S3** para processamento de arquivos e eventos.

![Diagrama Lambda + S3](/lambda/Desafio-v1-Lambda.png)

### 📌 Diagrama 2  
Correção da arquitetura com ajustes no **Cognito** (autenticação) e nos retornos do **DynamoDB** e **S3** para o Lambda(pre-sign URL).

![Diagrama com Cognito e ajustes](/lambda/Desafio-v2-Lambda.png)

### 📌 Diagrama 3  
Versão finalizada da arquitetura, com a inserção do **CloudWatch** para monitoramento e logs.

![Diagrama final com CloudWatch](/lambda/Desafio-v3-Lambda.png)

### 🎥 Diagrama **Lambda + S3**  
GIF apresentando o **fluxo finalizado** da arquitetura com Lambda, S3, Cognito, DynamoDB e CloudWatch.  

![Diagrama Lambda + S3](/lambda/Desafio-v4-Lambda.gif)
---

## 📂 Estrutura de Pastas

. <br>
├── ec2 <br>
│ ├── Desafio-v1-EC2.png<br>
│ └── Desafio-v2-EC2.gif<br>
│<br>
├── lambda<br>
│ ├── Desafio-v1-Lambda.png<br>
│ ├── Desafio-v1-Lambda.png<br>
│ ├── Desafio-v2-Lambda.png<br>
│ └── Desafio-v4-Lambda.gif<br>
│<br>
└── README.md<br>