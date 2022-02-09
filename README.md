## 💰 FinApi - Financeira

---

### 🚀 Technologies
- [Node Js](#)
- [Express](https://expressjs.com/pt-br/)
- [Nodemon](https://www.npmjs.com/package/nodemon)


### ▶ Starting the project

```bash

# Clone the repository git@github.com:daianessousa/ig-news.git
$ git clone git@github.com:daianessousa/FinApi.git

# Install the dependencies
$ yarn

# Run in development mode
$ yarn dev

# Will start on http://localhost:3333/ 

```

### Requisitos
- [x] Deve ser possível criar uma conta
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [x] Deve ser possível atualizar dados da conta do cliente
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível deletar uma conta
- [x] Deve ser possível retornar o balanço

---

### Regras de negócio
- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível excluir uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente