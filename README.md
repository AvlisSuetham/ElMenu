# 🍽️ El Menu: Crystal Blue Edition 1.0

**Crystal Blue Edition** é a **primeira versão de lançamento (release)** do projeto **El Menu**, criado originalmente para fins didáticos durante um curso técnico em Desenvolvimento de Sistemas.  
Seu nome faz referência ao icônico produto do personagem *Walter White*, simbolizando um tributo ao PHP puro — simples, direto e poderoso.

---

## 📦 Sobre o Projeto

Esta versão funciona como uma **beta pública**, demonstrando uma amostra prática do que sou capaz de desenvolver **do zero**.  
Ela apresenta recursos essenciais de um sistema de gerenciamento de pedidos, com foco na simulação de um restaurante ou lanchonete.

O código segue o paradigma **procedural**, com **organização modular** por meio de `includes` e separação por funções específicas para facilitar a manutenção.

---

## 🧪 Funcionalidades Incluídas

- ✅ CRUD completo de **Produtos**
- ✅ CRUD completo de **Categorias**
- ✅ CRUD completo de **Cupons de Desconto**
- ✅ Sistema de **Carrinho de Compras**
- ✅ Simulação de **Pagamentos** (modo de teste)
- ✅ Geração de **QR Codes Pix** simulados
- ✅ Cadastro e **Login de Usuários**
- ✅ Criação e **Gerenciamento de Funcionários**
- ✅ Sistema de **Admissão/Demissão**
- ✅ **Gestão de Pedidos** com painel administrativo
- ✅ Relatórios de vendas por **dia**, **semana**, **mês** e **ano**
- ✅ **Proteção básica** com sessões PHP
- ✅ Interface **Responsiva** com design clean em CSS nativo

---

## 🚀 Como Usar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/elmenu-crystalblue.git
```

### 2. Configure o banco de dados

- Crie um banco no MySQL.  
- Importe o arquivo `elmenu.sql` (caso fornecido).  
- Edite as credenciais no arquivo `includes/db.php`.  

### 3. Inicie um servidor local

Você pode utilizar:
- **XAMPP / WAMP**  
- **PHP embutido**:
  ```bash
  php -S localhost:8000
  ```

### 4. Acesse no navegador

```
http://localhost:8000
```

Explore, teste e divirta-se!

---

## 📋 Changelog

### Versão 1.0 – Crystal Blue Edition

- Primeira release pública  
- Interface totalmente responsiva  
- Integração com sessão de usuários  
- Módulo de autenticação e criptografia  
- CRUD completo de:
  - Produtos
  - Categorias
  - Cupons de desconto
  - Funcionários (com admissão/demissão)
- Sistema de carrinho e checkout  
- Simulação de pagamento com QR Code Pix  
- Painel administrativo com:
  - Gerenciamento de pedidos
  - Relatórios por período (dia, semana, mês, ano)
- Modularização do código em `includes/`  
- Criptografia básica de dados sensíveis (usuário, e-mail, CPF)  
- Separação de acesso por tipo de usuário (`admin`, `funcionário`, `cliente`)  

---

## ⚠️ Licença Customizada

> Este projeto foi desenvolvido **exclusivamente para fins educacionais**.

- 🚫 **Uso comercial não autorizado.**
- 🆓 Você pode estudar, modificar e testar **livremente** para fins pessoais ou acadêmicos.
- 💰 Para **uso comercial**, **implementação em produção** ou **redistribuição**, é necessário adquirir uma **licença completa**.

Esta versão é uma **amostra do que sou capaz de criar**.  
Caso deseje uma versão personalizada ou com funcionalidades específicas para seu negócio, **entre em contato!**

---

© 2025 Sophira Digital — Criando Sistemas com ❤️
