## PT:

# 🚀 Projeto Milhas: Gerenciador de Pontos e Milhas

![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-17-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Authentication-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

## 📄 Sobre o Projeto

Este é um projeto acadêmico desenvolvido para a disciplina de **Programação Web 1** do curso de **Bacharelado em Sistemas de Informação** do Instituto Federal de Sergipe (IFS) - Campus Lagarto.

O objetivo é criar um sistema completo para gerenciamento de milhas e pontos de cartões de crédito. O sistema visa ajudar o usuário a controlar seus pontos, garantindo previsibilidade e oferecendo notificações automáticas sobre promoções e prazos de crédito.

## ✨ Funcionalidades Principais

O sistema foi projetado para atender aos seguintes requisitos:

* **Cadastro de Usuários**:
    * Permite que novos usuários se cadastrem com nome, e-mail e senha.
    * Implementa autenticação e autorização seguras via JWT.
    * Possibilita recuperação de senha e atualização de perfil.

* **Controle de Cartões e Programas de Pontos**:
    * Cadastro de diferentes bandeiras de cartões (Visa, MasterCard, etc.).
    * Associação de cada cartão a um programa de pontos (Smiles, TudoAzul, etc.).
    * Controle do saldo atual de pontos de cada programa.

* **Registro de Aquisições e Pontos**:
    * Registro de novas compras que geram pontos.
    * Anexo de comprovantes da compra (imagens ou PDFs).
    * Cálculo automático dos pontos a receber com base no cartão.
    * Exibição do tempo restante para o crédito dos pontos.

* **Alertas e Notificações**:
    * Alertas sobre expiração do prazo de crédito dos pontos.
    * Notificações sobre promoções de milhas nos programas cadastrados.

* **Dashboard e Relatórios**:
    * Exibição de gráficos e tabelas com pontos por cartão e histórico de acúmulo.
    * Permite exportar dados em PDF e CSV.

## 🛠️ Tecnologias Utilizadas

* **Backend:** Java 17+, Spring Boot, Spring Security (JWT), JPA/Hibernate, PostgreSQL.
* **Frontend:** Angular.
* **Upload de arquivos:** Suporte para PDF, PNG e JPG.
* **Testes:** Implementação de testes unitários e de integração.
* **Notificações Push (Opcional):** Firebase Cloud Messaging (FCM) ou serviço compatível.

---
**Desenvolvido para a disciplina de Programação Web 1 (Ano/Período: 2025/02).**


## EN:

# 🚀 Miles Manager Project

![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-17-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Authentication-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

## 📄 About The Project

This is an academic project developed for the **Web Programming 1** course of the **Bachelor's Degree in Information Systems** at the Federal Institute of Sergipe (IFS) - Lagarto Campus.

The goal is to create a complete system for managing credit card points and miles. The system aims to help users control their points, ensuring predictability and providing automatic notifications about promotions and credit deadlines.

## ✨ Key Features

The system is designed to meet the following requirements:

* **User Registration**:
    * Allows new users to sign up using their name, email, and password.
    * Implements secure authentication and authorization via JWT.
    * Provides features for password recovery and profile updates.

* **Card and Loyalty Program Management**:
    * Registration of different card brands (Visa, MasterCard, etc.).
    * Association of each card with a loyalty program (Smiles, TudoAzul, etc.).
    * Management of the current points balance for each program.

* **Points Acquisition and Tracking**:
    * Logging of new purchases that generate points.
    * Attachment of purchase receipts (images or PDFs).
    * Automatic calculation of points to be received based on the card.
    * Displays the remaining time until points are credited.

* **Alerts and Notifications**:
    * Alerts when the points crediting period expires.
    * Notifications about miles promotions in the user's registered programs.

* **Dashboard and Reports**:
    * Displays charts and tables showing points per card and accumulation history.
    * Allows data to be exported to PDF and CSV formats.

## 🛠️ Tech Stack

* **Backend:** Java 17+, Spring Boot, Spring Security (JWT), JPA/Hibernate, PostgreSQL.
* **Frontend:** Angular.
* **File Uploads:** Support for PDF, PNG, and JPG files.
* **Testing:** Implementation of unit and integration tests.
* **Push Notifications (Optional):** Firebase Cloud Messaging (FCM) or a compatible service.

---
**Developed for the Web Programming 1 course (Year/Term: 2025/02).**
