# ALICE WEB APP

Aplicação web de e-commerce voltada para a vendas de produtos e utensílios de tabacarias(pode ser outro tema), produtos como sedas, essências, vaporizadores, piteiras e acessórios relacionados. A aplicação seguirá uma arquitetura baseada em microsserviços, conforme solicitado. Pretendemos tentar colocar um módulo de recomendação personalizada de produtos com base em hábitos de navegação e histórico de compras.

---

## 📋 Índice
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Sobre](#-sobre)
- [Funcionalidades](#-funcionalidades)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação e uso](#-instalação-uso)
  
---

## 📂 Estrutura do Projeto
![arquitetura alice tabacaria](https://github.com/user-attachments/assets/f9b2bb15-6bc7-4782-bd70-b55324ddefda)
---
## 📖 Sobre
Projeto universitário da disciplina DESENVOLVIMENTO DE SOFTWARE INTEGRADO À OPERAÇÃO DA INFRAESTRUTURA, vinculada do curso de CIÊNCIAS DA COMPUTAÇÃO, UFCG - CAMPUS CAMPINA GRANDE.

---

## ✨ Funcionalidades (Microserviços)
- Auth-service : Autenticação e autorização de usuários (Entidade Usuário comum e administrador).
- User-service: Gerenciamento de perfis e endereços.
- Catalog-Service: Listagem e cadastro de produtos.
- Cart-Service: Carrinho de compras.
- Order-Service: Criação e acompanhamento de pedidos.
- Payment-service: simulação de pagamentos.
- Frontend: Interface, acoplada aos serviços via API Gateway.
- API-Gateway: API, redireciona a requisição ao devido serviço.

---

## 📦 Pré-requisitos
O que precisa estar instalado/configurado antes de usar o projeto:
- Nodejs
- Java
- Docker
- Yarn
- Npm
- PostgreSQL
- Node

---
## Instalação e uso
Este projeto foi divido em vários repositórios, para instalação e uso, clone todos os repositórios e visite seus respectivos READMEs.

