# DesafiosDio

## 🚀 Desafio AWS Step Functions
---
## 🧩 Descrição do Desafio
---

Este projeto faz parte do laboratório prático sobre AWS Step Functions, com o objetivo de consolidar o aprendizado sobre workflows automatizados na AWS.
O repositório reúne anotações, insights e exemplos práticos adquiridos durante o estudo.

## 🎯 Objetivos de Aprendizagem
---
Aplicar conceitos de orquestração de tarefas com AWS Step Functions.

Criar e entender máquinas de estado (State Machines).

Documentar processos técnicos de forma clara e reprodutível.

Utilizar o GitHub para compartilhar documentação técnica.
---
## ⚙️ Etapas Realizadas
---
Acompanhei todas as vídeo-aulas do laboratório.

Criei um workflow básico com AWS Step Functions:

Utilizando AWS Lambda como função principal.

Definindo transições de estado e condições de sucesso/falha.

Testei o fluxo e registrei os resultados.

Documentei o processo com capturas de tela e anotações.
---
## 🧠 Insights e Aprendizados
---
Entendi como Step Functions ajudam a orquestrar funções Lambda e serviços AWS.

Aprendi a criar máquinas de estado em formato JSON para definir fluxos.

Percebi que o CloudWatch é essencial para monitorar execuções e depurar erros.

A integração com Lambda, S3 e DynamoDB facilita muito a automação de processos complexos.

---
## 🧰 Ferramentas Utilizadas
---
AWS Step Functions

AWS Lambda

AWS CloudWatch

Visual Studio Code

GitHub

# Gerenciando Instâncias EC2 na AWS - DIO Santander Code Girl

## 🎯 Objetivo do Laboratório
Consolidar conhecimentos em **gerenciamento de instâncias EC2 na AWS**, aplicando os conceitos aprendidos nas aulas, conectando-se via SSH, configurando segurança e documentando toda a experiência.  
O entregável é um **repositório organizado contendo anotações e insights adquiridos durante a prática**, servindo como material de apoio para estudos futuros.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
- **AWS EC2** – Criação e gerenciamento de instâncias
- **AWS Management Console** – Interface web da AWS
- **Git & GitHub** – Versionamento e compartilhamento da documentação
- **SSH (Secure Shell)** – Conexão remota com a instância
- **Markdown** – Organização da documentação
- **Nginx** (opcional) – Servidor web para teste

---

## 📚 Experiência Passo a Passo

### 1️⃣ Preparação do Ambiente
- Acessei o **AWS Management Console**.
- Selecionei o serviço **EC2**.
- Criei um **Key Pair** para permitir conexões SSH seguras.

### 2️⃣ Criação da Instância
- **AMI escolhida:** Amazon Linux 2  
- **Tipo de instância:** t2.micro (gratuita)  
- **Security Group:**
  - Porta 22: SSH
  - Porta 80: HTTP (opcional)
- **Tags:** Nome e identificadores claros para facilitar o gerenciamento

> 💡 Dica: Sempre adicione tags para organizar múltiplas instâncias.

### 3️⃣ Conexão via SSH
**exmplo**
```bash
ssh -i "minha-chave.pem" ec2-user@<IP-da-instancia>
```
---
### ✅ Conclusão

Este laboratório permitiu consolidar conhecimentos sobre EC2, SSH, Security Groups e boas práticas de organização de instâncias na AWS.

O repositório com as anotações e insights adquiridos serve como referência prática para estudos futuros, além de auxiliar em implementações reais em projetos na nuvem.
