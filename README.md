# Entrega-de-projeto
🔐 Projeto de Segurança / Pentest

## 📌 Descrição
Este projeto tem como objetivo demonstrar testes de segurança utilizando ferramentas como Medusa, focando em autenticação de serviços.

## 🎯 Objetivo
- Testar combinações de usuário e senha
- Analisar respostas do serviço
- Identificar possíveis vulnerabilidades

## 🛠️ Ferramentas utilizadas
- Kali Linux
- Medusa
- FTP (serviço testado)

## 📂 Estrutura do projeto
- `/wordlists` → listas de usuários e senhas
- `/scripts` → comandos e automações
- `/images` → capturas de tela dos testes

## ⚙️ Exemplo de comando
```bash
medusa -h <IP> -U user.txt -P pass.txt -M ftp
