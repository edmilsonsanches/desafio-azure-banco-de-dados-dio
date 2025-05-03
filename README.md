# desafio-azure-banco-de-dados-dio

# 🗃️ Criando um Banco de Dados na Nuvem com o Microsoft Azure

Este repositório contém minhas anotações, resumos e dicas sobre como criar e configurar uma instância de banco de dados na plataforma Microsoft Azure. Esse material foi criado como parte de um desafio prático e vai me ajudar a revisar e aplicar esse conhecimento no futuro.

---

## 📘 Descrição do Desafio

O objetivo deste desafio é praticar o processo de criação de uma instância de banco de dados no Microsoft Azure. O resultado esperado é um repositório com um resumo do que foi feito, além de dicas e anotações úteis para quem quiser repetir o processo.

---

## 🌐 O que é o Microsoft Azure?

O **Microsoft Azure** é uma plataforma de serviços em nuvem que permite criar servidores, bancos de dados, aplicativos, entre outros, sem precisar de um computador físico para isso. Tudo acontece pela internet, com poucos cliques.

---

## ⚙️ Passo a passo: Criando uma instância de banco de dados

### 1. Criar uma conta no Azure
- Acesse [https://azure.microsoft.com](https://azure.microsoft.com)
- Clique em **Comece gratuitamente** e siga as instruções de cadastro.

### 2. Acessar o portal do Azure
- Vá para [https://portal.azure.com](https://portal.azure.com)
- Faça login com sua conta.

### 3. Criar um banco de dados
- No menu esquerdo, clique em **Criar um recurso**.
- Procure por **Banco de Dados SQL** (ou outro tipo como MySQL, PostgreSQL, etc).
- Clique em **Criar**.
- Preencha os campos:
  - **Nome do banco de dados**
  - **Servidor** (crie um novo ou use um existente)
  - **Usuário e senha**
  - **Região**: escolha uma próxima de você
  - **Camada de preço**: selecione a mais básica (gratuita ou mais barata)

### 4. Finalizar e revisar
- Clique em **Revisar + Criar**
- Verifique as configurações e clique em **Criar**

---

## 💡 Dicas e Observações

- ⚠️ **Importante:** Após os testes, exclua o recurso para não gerar cobranças.
- 🔑 Guarde bem o nome do servidor, usuário e senha — você vai precisar para se conectar depois.
- 💻 Você pode usar o **Azure Data Studio** ou qualquer outro cliente SQL para se conectar ao banco.
- 🧩 Se escolher MySQL ou PostgreSQL, lembre-se de habilitar o acesso pela internet (definir IP autorizado).
- 📚 O Azure tem uma documentação muito boa — vale consultar quando tiver dúvidas.

---

## 🧠 Conclusão

Criar uma instância de banco de dados no Azure foi uma ótima forma de entender como funcionam bancos de dados na nuvem. Aprendi a configurar, conectar e entender os principais elementos desse serviço.

---

## 📎 Referências

- [Documentação oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Criar um banco de dados SQL no Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/database/single-database-create-quickstart)

