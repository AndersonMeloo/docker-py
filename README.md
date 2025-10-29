# 🐍 Flask + Redis com Docker

Projeto demonstrando o uso de **Flask** com **Redis**, executando dentro de um **container Docker**.  
O servidor conta o número de visitas usando Redis como cache, retornando a quantidade de vezes que a rota `/` foi acessada.

---

## 🚀 Tecnologias utilizadas

- Python 3  
- Flask  
- Redis  
- Docker  
- Docker Compose  

---

## 📦 Como clonar o projeto

```bash
# Clonar o repositório
git clone https://github.com/AndersonMeloo/nome-do-projeto.git

# Acessar a pasta do projeto
cd nome-do-projeto
```

## ⚙️ Rodando com Docker

```bash
# Buildar e iniciar os containers
docker compose up --build
```

## 🧠 Conceitos aplicados
- Criação de aplicação web simples com Flask
- Contador de visitas usando Redis como cache
- Containerização com Docker e Docker Compose
- Reconexão automática ao Redis em caso de falha
- Separação de ambientes (desenvolvimento x produção)
