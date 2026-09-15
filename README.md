# 📦 NexaTech — Automação de Controle de Estoque

Automação de controle de estoque desenvolvida com **n8n**, integrando **Google Forms** e **Google Sheets** para registrar e processar movimentações de produtos.

> Projeto desenvolvido para estudo e demonstração prática de automação de processos utilizando n8n.

---

## 🎯 Sobre o projeto

A **NexaTech** é uma empresa fictícia criada para simular um cenário real de controle de estoque.

O projeto foi desenvolvido com o objetivo de automatizar o processo de registro de **entradas e saídas de produtos**, reduzindo tarefas manuais e centralizando o processamento das informações no n8n.

O usuário registra uma movimentação através de um formulário. A resposta é armazenada no Google Sheets e, a partir de uma nova linha, o **n8n identifica o evento e inicia automaticamente o workflow**.

---

## 🔄 Fluxo da automação

### 1. Registro da movimentação

O usuário preenche o Google Forms informando:

* Tipo de movimentação;
* Produto;
* Quantidade;
* Responsável;
* Observação.

### 2. Armazenamento

As respostas do formulário são registradas automaticamente no Google Sheets.

### 3. Detecção do evento

O **Google Sheets Trigger** do n8n monitora a planilha e identifica novas linhas adicionadas.

### 4. Processamento

Ao detectar uma nova movimentação, o workflow inicia o processamento das informações recebidas.

### 5. Controle de estoque

A movimentação é utilizada para atualizar o estoque do produto correspondente.

---

## 🧠 Principais conceitos utilizados

Este projeto foi desenvolvido para praticar conceitos importantes de automação com n8n:

* Triggers;
* Integração com serviços externos;
* Google Sheets;
* Processamento de dados;
* Expressões do n8n;
* Lógica condicional;
* Manipulação de dados;
* Automação baseada em eventos;
* Workflows.

---

## 📸 Demonstração

### Google Forms

<img width="576" height="654" alt="image" src="https://github.com/user-attachments/assets/86c27877-e7bd-4ccf-996e-3abd5ec686bb" />

### Google Sheets

<img width="1102" height="444" alt="image" src="https://github.com/user-attachments/assets/6122622e-958b-4019-81a9-68c34faf8acb" />


### Workflow no n8n

<img width="1427" height="510" alt="image" src="https://github.com/user-attachments/assets/068d10b7-7098-4ae1-bfbd-1a89f5805c12" />
