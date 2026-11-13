# Narinha — Assistente Pessoal Inteligente

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-20232A?logo=react&logoColor=61DAFB)

## Sobre o projeto

A **Narinha** é uma assistente pessoal e administrativa inteligente, desenvolvida para auxiliar na organização de tarefas, compromissos e atividades do dia a dia.

O projeto busca integrar inteligência artificial, automação de processos e desenvolvimento de aplicações para criar uma experiência prática, organizada e intuitiva.

## Objetivos

- Facilitar o gerenciamento de tarefas e prazos.
- Organizar compromissos e agendamentos.
- Interpretar solicitações em linguagem natural.
- Automatizar processos por meio de integrações.
- Desenvolver uma interface moderna e acessível.

## Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| Python | Desenvolvimento do backend |
| FastAPI | Construção da API |
| MongoDB Atlas | Banco de dados |
| n8n | Automação de fluxos |
| GPTMaker | Configuração do assistente de IA |
| React Native / Expo | Desenvolvimento do aplicativo |

## Funcionalidades implementadas

- **Gestão de tarefas:** criação e consulta de tarefas por meio de integração com a API.
- **Organização de prazos:** interpretação de datas e horários em linguagem natural.
- **Integração com IA:** comunicação entre GPTMaker e fluxos automatizados.
- **Automação de processos:** utilização do n8n para conectar os serviços.
- **Backend com autenticação:** endpoints protegidos para operações de integração.
- **Gestão de compromissos:** desenvolvimento da integração para registro de agendamentos.


## Arquitetura do projeto

A aplicação está sendo desenvolvida com uma arquitetura que integra:

1. **Frontend:** interface do aplicativo.
2. **Backend:** processamento de requisições e regras de negócio.
3. **Banco de dados:** armazenamento das informações.
4. **Automação:** integração entre serviços e execução de fluxos.
5. **Inteligência artificial:** interpretação das solicitações do usuário.

## Desafios técnicos e aprendizados

Durante o desenvolvimento da Narinha, foram trabalhados desafios relacionados a:

- Integração de serviços externos por meio de APIs HTTP.
- Desenvolvimento e validação de endpoints com FastAPI.
- Autenticação e proteção das requisições.
- Integração entre inteligência artificial e automações.
- Interpretação e conversão de datas em linguagem natural.
- Comunicação entre frontend, backend e banco de dados.
- Organização de fluxos automatizados utilizando n8n.

O desenvolvimento também proporcionou experiência prática com resolução de erros de integração, validação de dados e testes de comunicação entre diferentes serviços.

## Arquitetura técnica

O funcionamento da Narinha é baseado na integração entre diferentes componentes:

```text
Usuário
   |
   v
Aplicativo (React Native / Expo)
   |
   v
Backend (Python / FastAPI)
   |
   v
Banco de dados (MongoDB Atlas)

Assistente de IA (GPTMaker)
   |
   v
Automação (n8n)
   |
   v
API do Backend (FastAPI)
   |
   v
Registro e organização das informações
```

Essa arquitetura permite separar a interface, as regras de negócio, o armazenamento de dados e as automações, facilitando a manutenção e a evolução do sistema.

## Desenvolvimento

O projeto está em desenvolvimento contínuo, com implementação gradual de funcionalidades, integração entre serviços e aprimoramento da experiência do usuário.

## Objetivo acadêmico e profissional

Este projeto representa uma oportunidade de aplicar conhecimentos de Engenharia de Inteligência Artificial, desenvolvimento de software, integração de APIs, automação e bancos de dados em uma aplicação prática.

---

**Projeto desenvolvido como iniciativa de estudo e desenvolvimento tecnológico.**

O código-fonte completo permanece em repositório privado por questões de segurança e proteção do projeto.
