# Product Backlog - Sistema de Gestão para Hortifruti

### História 1: Cadastro de Usuário
**Como administrador, quero cadastrar funcionários no sistema, para que eu possa controlar os usuários e suas funções.**

**Tarefas:**
- Criar a função para adicionar um novo usuário.
- Implementar o armazenamento dos dados de usuário (nome, senha, e-mail, cargo e salário).
- Criar a função para editar e excluir usuários.
- Criar a função para listar os usuários cadastrados.

---

### História 2: Login de Usuário
**Como usuário (funcionário ou administrador), quero realizar login no sistema, para acessar minhas funcionalidades com base no meu cargo.**

**Tarefas:**
- Implementar a autenticação por nome de usuário e senha.
- Criar lógica para diferenciar permissões (admin x funcionário).
- Validar o acesso e redirecionar para o menu principal.

---

### História 3: Cadastro de Produtos
**Como administrador, quero cadastrar produtos no sistema, para que eu possa gerenciar o estoque de mercadorias.**

**Tarefas:**
- Criar a função para cadastrar novos produtos.
- Implementar o armazenamento dos dados do produto (nome, quantidade, preço de compra, preço de venda, validade, fornecedor).
- Criar a função para editar, excluir e visualizar produtos.

---

### História 4: Controle de Estoque
**Como administrador, quero controlar a entrada e saída de mercadorias no estoque, para garantir que as quantidades estejam atualizadas.**

**Tarefas:**
- Criar a função para entrada de mercadorias (atualizar estoque ao adicionar produtos).
- Criar a função para saída de mercadorias (atualizar estoque ao vender ou retirar produtos).
- Implementar a consulta de estoque por nome, validade e fornecedor.

---

### História 5: Realizar Venda
**Como funcionário, quero registrar vendas no sistema, para que o estoque seja atualizado automaticamente e as informações de venda sejam armazenadas.**

**Tarefas:**
- Implementar a função para selecionar produtos para venda.
- Criar a lógica para calcular o total da venda com base na quantidade e no preço de venda.
- Atualizar automaticamente o estoque com base na quantidade vendida.
- Armazenar a venda no histórico.

---

### História 6: Histórico de Vendas
**Como administrador, quero ter acesso ao histórico de vendas, para que eu possa consultar informações detalhadas sobre as transações realizadas.**

**Tarefas:**
- Criar a função para listar o histórico de vendas.
- Implementar filtros de consulta por data e produto.
- Armazenar cada venda com dados de produto, quantidade, valor e data.

---

### História 7: Relatório Financeiro
**Como administrador, quero gerar relatórios financeiros, para que eu possa analisar lucros e despesas do hortifruti.**

**Tarefas:**
- Criar a função para calcular o lucro total com base nas vendas e no preço de venda.
- Implementar a função para calcular as despesas com base no preço de compra dos produtos.
- Gerar e exibir o saldo financeiro (lucro - despesas).

---

### História 8: Interface de Linha de Comando (CLI)
**Como usuário, quero uma interface simples e interativa, para que eu possa navegar facilmente pelo sistema.**

**Tarefas:**
- Criar o menu principal com opções claras (Cadastro de usuários, login, gestão de estoque, vendas, relatórios).
- Implementar submenus para cada funcionalidade principal.
- Criar feedback visual para operações bem-sucedidas ou falhas.

---

### Priorização Sugerida:
1. Login de Usuário (História 2)
2. Cadastro de Usuário (História 1)
3. Cadastro de Produtos (História 3)
4. Realizar Venda (História 5)
5. Controle de Estoque (História 4)
6. Histórico de Vendas (História 6)
7. Relatório Financeiro (História 7)
8. Interface de Linha de Comando (CLI) (História 8)

---

Esse backlog apresenta as histórias de usuário e suas tarefas correspondentes, organizadas de forma incremental e iterativa. A priorização pode ser ajustada conforme o andamento do projeto e as necessidades do aprendizado.
