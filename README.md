# 💊 App de Gerenciamento de Medicamentos

Este repositório contém o código-fonte de um aplicativo móvel desenvolvido com **Flutter** para auxiliar usuários no **gerenciamento de seus medicamentos** e **adesão ao tratamento farmacológico**. O app também conta com integração ao **Bulário Eletrônico da Anvisa**, permitindo consulta às bulas de medicamentos de forma rápida e confiável.

## 👩🏻‍💻 Desenvolvido Por

Beatriz de Oliveira Vieira

## 📌 Objetivos

* Criar um sistema para cadastro de medicamentos, incluindo dose, horários e duração do tratamento.

* Implementar um sistema de notificações automáticas para lembrar os usuários de tomarem os remédios.

* Desenvolver um módulo de OCR (reconhecimento de texto) para escanear bulas e facilitar o cadastro dos medicamentos.

* Armazenar os dados do usuário de forma segura e acessível, permitindo backup na nuvem.

* Criar uma interface simples e intuitiva, acessível para idosos e pessoas com pouca experiência digital.

## 📱 Funcionalidades

- Cadastro e agendamento de medicamentos.
- Notificações para lembrar o horário da medicação.
- Histórico de uso e acompanhamento da adesão.
- Consulta de bulas diretamente do site da Anvisa.
- Armazenamento local com sincronização em nuvem (Firebase).
- Interface intuitiva e responsiva.

## 🚀 Tecnologias Utilizadas

| Tecnologia       | Finalidade                                 |
|------------------|---------------------------------------------|
| Flutter          | Desenvolvimento do app mobile               |
| Dart             | Linguagem de programação                    |
| SQLite           | Armazenamento local                         |
| Firebase Firestore | Armazenamento e sincronização na nuvem    |
| Firebase Auth    | Autenticação de usuários                    |
| Python + BeautifulSoup | Script para extração de dados do bulário da Anvisa |
| Firebase Functions | API para acesso aos dados extraídos       |
