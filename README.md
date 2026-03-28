# 🏹 Minecraft Network Core - BedWars & Duels

Um projeto completo de servidor Minecraft focado em **BedWars** e **Duels**, desenvolvido para ser **escalável, modular e educativo**. Ideal tanto para quem deseja estudar arquitetura de servidores quanto para quem quer utilizar como base sólida para iniciar sua própria network.

---

## 🚀 Objetivo

Este projeto foi criado com dois principais propósitos:

* 📚 **Educação:** fornecer uma base real de como grandes servidores funcionam internamente.
* 🧱 **Produção:** permitir que desenvolvedores utilizem o projeto como ponto de partida para servidores próprios.

---

## 🧠 Arquitetura

A arquitetura do sistema foi projetada para ser **distribuída e altamente escalável**, permitindo fácil expansão conforme a necessidade.

### 🔗 Comunicação entre serviços

* **RabbitMQ** → Mensageria assíncrona (eventos, filas, sincronização)
* **Redis** → Cache distribuído, pub/sub e dados temporários

### 🗄️ Banco de Dados

* Suporte a múltiplos bancos:

  * **PostgreSQL**
  * **MariaDB**
* Sistema desacoplado com suporte a abstração de persistência

---

## ⚙️ Funcionalidades

### 🛏️ BedWars

* Sistema completo de partidas
* Gerenciamento de arenas
* Times e upgrades
* Leaderboards

### ⚔️ Duels

* Sistema de duelos 1v1
* Kits customizáveis
* Ranked / Unranked
* Sistema de filas

### 🧩 Core Features

* Sistema de contas (Account)
* Rank / Permissões
* Sistema de moedas
* API interna robusta
* Eventos customizados
* Sistema de cache otimizado

---

## 📈 Escalabilidade

Projetado com foco em grandes redes:

* Separação de responsabilidades
* Cache distribuído
* Comunicação desacoplada
* Fácil expansão horizontal

---

## 🛠️ Tecnologias Utilizadas

* Kotlin (PandaSpigot 1.8+)
* RabbitMQ
* Redis
* PostgreSQL / MariaDB
* Gradle

---

## 🎯 Público-Alvo

* Desenvolvedores iniciantes que querem aprender
* Desenvolvedores avançados que buscam uma base sólida
* Donos de servidores que querem iniciar uma network

---

## 📄 Licença

Este projeto é open-source e pode ser utilizado livremente para estudos e projetos próprios.

---

## 💡 Considerações Finais

Este projeto não é apenas um servidor — é uma **base completa para construção de networks Minecraft modernas**, com foco em desempenho, organização e aprendizado.

Se você quer entender como grandes servidores funcionam ou criar o seu próprio, este é o ponto de partida ideal.

---
