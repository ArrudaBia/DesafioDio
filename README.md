# DesafioDio

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
