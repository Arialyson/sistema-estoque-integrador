# Sistema de Controle de Estoque - Projeto Integrador

Sistema completo de controle de estoque desenvolvido como parte do Projeto Integrador da Gran Faculdade, estruturado com uma aplicação web no **Frontend** (React) e uma API REST no **Backend** (Node.js com Express e SQLite)[cite: 1, 2].

## 🚀 Tecnologias Utilizadas

### **Frontend**
* **React.js** (Biblioteca para construção da interface de usuário)[cite: 2]
* **CSS / Estilização em linha** para componentização das telas

### **Backend**
* **Node.js** (Ambiente de execução JavaScript)
* **Express** (Framework web para rotas e API REST)
* **SQLite3** (Base de dados relacional leve e embutida)
* **CORS** (Middleware para comunicação entre origens diferentes)

---

## ⚙️ Funcionalidades do Sistema

1. **Gestão de Fornecedores:** Cadastro completo de fornecedores (Nome, CNPJ, Endereço, Telefone, E-mail e Contato Principal) com validações e armazenamento em base de dados[cite: 1].
2. **Gestão de Produtos:** Registo de itens de estoque (Nome, Código de Barras, Descrição, Quantidade, Categoria e Data de Validade)[cite: 2].
3. **Associação de Fornecedores a Produtos:** Relação dinâmica (muitos para muitos) que permite vincular múltiplos fornecedores a um produto específico e gerir desassociações em tempo real.

---

## 🛠️ Como Executar o Projeto Localmente

Certifique-se de ter o **Node.js** instalado no seu computador antes de prosseguir.

### 1. Clonar o Repositório
```bash
git clone [https://github.com/Arialyson/sistema-estoque-integrador.git](https://github.com/Arialyson/sistema-estoque-integrador.git)
cd sistema-estoque-integrador
