# Levantamento de Requisitos - Sistema de Gestão para Hortifruti

## Objetivo
Desenvolver um sistema simples de gestão para hortifruti, utilizando a linguagem C. O sistema deverá incluir funcionalidades básicas de controle de usuários, estoque, vendas e gestão financeira, atendendo às necessidades do projeto acadêmico de forma simplificada.

## 1. Funcionalidades Principais

### 1.1. Cadastro de Usuário
**Descrição**: O sistema deve permitir o cadastro de funcionários, armazenando informações básicas para acesso e controle.

**Dados para cadastro**:
- Nome
- Senha
- E-mail
- Cargo (Admin ou Funcionário)
- Salário

**Requisitos Funcionais**:
- Deve permitir a inclusão, edição, visualização e exclusão de usuários (CRUD).
- Somente o administrador pode cadastrar e editar funcionários.

### 1.2. Login de Usuário
**Descrição**: O sistema deverá ter um mecanismo de login com controle de acesso para administrador e funcionários.

**Requisitos Funcionais**:
- Autenticação por nome de usuário e senha.
- Diferenciação entre administradores e funcionários para controle de permissões.
- Administrador terá acesso a todas as funcionalidades do sistema.
- Funcionário terá acesso limitado (ex: realizar vendas e visualizar produtos).

### 1.3. Gestão de Estoque
**Descrição**: O sistema deverá permitir o cadastro e controle de produtos no estoque, incluindo a entrada e saída de mercadorias.

**Dados de Produto**:
- Nome do produto
- Quantidade em estoque
- Preço de compra
- Preço de venda
- Data de validade
- Fornecedor

**Requisitos Funcionais**:
- Cadastro de produtos (CRUD completo).
- Atualização de quantidade no estoque após venda.
- Controle de entrada e saída de mercadorias.
- Consulta de produtos por nome, validade e fornecedor.
- Exclusão de produtos quando necessário.

### 1.4. Gestão de Vendas
**Descrição**: O sistema deverá permitir a realização de vendas e atualizar o estoque automaticamente com base nas vendas efetuadas.

**Requisitos Funcionais**:
- Registro de vendas, com quantidade vendida, produto, e valor total.
- Atualização automática do estoque após a venda.
- Geração de histórico de vendas.
- Relatório de vendas por período (diário, semanal, mensal).

### 1.5. Gestão Financeira
**Descrição**: O sistema deverá gerar relatórios financeiros simples para auxiliar no controle de lucros e despesas.

**Requisitos Funcionais**:
- Relatório de lucro baseado no preço de venda dos produtos e quantidade vendida.
- Relatório de despesas com base no preço de compra dos produtos.
- Relatório de saldo (lucro total - despesas totais).

## 2. Requisitos Não Funcionais
- **Interface**: Interface de linha de comando (CLI), simples e intuitiva, adequada para um exercício acadêmico.
- **Armazenamento de Dados**: Inicialmente, o armazenamento será realizado em arquivos de texto (txt), simulando um banco de dados simples.
- **Segurança**: Controle de acesso básico por meio de autenticação de usuários (nome e senha), sem necessidade de criptografia complexa.

## 3. Casos de Uso

### 3.1. Caso de Uso: Cadastro de Usuário
- **Ator Principal**: Administrador
- **Fluxo Principal**:
  1. Administrador acessa o sistema com seu login.
  2. Seleciona a opção "Cadastrar Funcionário".
  3. Insere os dados do novo funcionário (nome, senha, e-mail, cargo, salário).
  4. O sistema armazena o novo funcionário.
  5. Administrador pode visualizar, editar ou excluir o funcionário posteriormente.

### 3.2. Caso de Uso: Login
- **Ator Principal**: Funcionário ou Administrador
- **Fluxo Principal**:
  1. Usuário insere nome e senha na tela de login.
  2. O sistema valida as credenciais.
  3. O usuário é autenticado e direcionado para o menu principal, com permissões baseadas no cargo.

### 3.3. Caso de Uso: Gestão de Estoque
- **Ator Principal**: Administrador ou Funcionário
- **Fluxo Principal**:
  1. Usuário seleciona "Gestão de Estoque".
  2. Usuário insere as informações do produto para cadastro.
  3. O sistema armazena o novo produto e sua quantidade em estoque.
  4. Usuário pode consultar, editar ou excluir produtos do estoque.

### 3.4. Caso de Uso: Realizar Venda
- **Ator Principal**: Funcionário
- **Fluxo Principal**:
  1. Usuário acessa a tela de "Realizar Venda".
  2. Seleciona o produto a ser vendido.
  3. Insere a quantidade vendida.
  4. O sistema atualiza automaticamente o estoque e registra a venda no histórico.

### 3.5. Caso de Uso: Geração de Relatórios Financeiros
- **Ator Principal**: Administrador
- **Fluxo Principal**:
  1. Administrador seleciona "Gerar Relatório Financeiro".
  2. Sistema calcula lucros e despesas com base nas vendas e compras de produtos.
  3. O sistema gera e exibe o relatório financeiro.

## 4. Conclusão
Esse levantamento de requisitos proporciona uma visão geral das funcionalidades e fluxos principais do sistema de gestão para hortifruti, adequado para o aprendizado em programação com a linguagem C. O sistema será uma aplicação simples, mas eficaz, para entender conceitos como CRUD, autenticação e controle de estoque.
