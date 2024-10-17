# Sprint Planning - Sistema de Gestão para Hortifruti

## Sprint 1: Autenticação e Controle de Acesso (Login e Cadastro de Usuário)
**Objetivo:** Implementar o login de usuários e o cadastro de funcionários, permitindo controle de acesso ao sistema.

### Tarefas:

#### Login de Usuário (História 2):
- Implementar autenticação por nome de usuário e senha: **4 horas**
- Criar lógica para diferenciação de permissões (admin x funcionário): **3 horas**
- Validar o acesso e redirecionar para o menu principal: **2 horas**

**Total estimado para Login:** 9 horas

#### Cadastro de Usuário (História 1):
- Criar a função para adicionar novo usuário: **4 horas**
- Implementar armazenamento dos dados de usuário (nome, senha, e-mail, cargo, salário): **3 horas**
- Criar função para editar e excluir usuários: **3 horas**
- Criar função para listar os usuários cadastrados: **2 horas**

**Total estimado para Cadastro de Usuário:** 12 horas

**Tempo Total para Sprint 1:** 21 horas

---

## Sprint 2: Cadastro e Controle de Produtos (Gestão de Estoque - Parte 1)
**Objetivo:** Criar as funcionalidades para cadastrar e gerenciar produtos no estoque.

### Tarefas:

#### Cadastro de Produtos (História 3):
- Criar a função para cadastrar novos produtos: **4 horas**
- Implementar armazenamento dos dados do produto (nome, quantidade, preço de compra, preço de venda, validade, fornecedor): **3 horas**
- Criar função para editar, excluir e visualizar produtos: **4 horas**

**Total estimado para Cadastro de Produtos:** 11 horas

#### Controle de Estoque (História 4):
- Criar a função para entrada de mercadorias (atualizar estoque ao adicionar produtos): **4 horas**
- Criar a função para saída de mercadorias (atualizar estoque ao vender ou retirar produtos): **4 horas**
- Implementar a consulta de estoque por nome, validade e fornecedor: **3 horas**

**Total estimado para Controle de Estoque:** 11 horas

**Tempo Total para Sprint 2:** 22 horas

---

## Sprint 3: Gestão de Vendas e Atualização de Estoque
**Objetivo:** Implementar a funcionalidade de vendas e a atualização automática do estoque.

### Tarefas:

#### Realizar Venda (História 5):
- Implementar a função para selecionar produtos para venda: **4 horas**
- Criar a lógica para calcular o total da venda com base na quantidade e no preço de venda: **3 horas**
- Atualizar automaticamente o estoque com base na quantidade vendida: **4 horas**
- Armazenar a venda no histórico: **3 horas**

**Total estimado para Realizar Venda:** 14 horas

#### Histórico de Vendas (História 6):
- Criar a função para listar o histórico de vendas: **3 horas**
- Implementar filtros de consulta por data e produto: **4 horas**
- Armazenar cada venda com dados de produto, quantidade, valor e data: **3 horas**

**Total estimado para Histórico de Vendas:** 10 horas

**Tempo Total para Sprint 3:** 24 horas

---

## Sprint 4: Relatórios Financeiros e Fechamento do Sistema
**Objetivo:** Implementar a funcionalidade de relatórios financeiros e finalizar a interface de usuário.

### Tarefas:

#### Relatório Financeiro (História 7):
- Criar a função para calcular o lucro total com base nas vendas e no preço de venda: **4 horas**
- Implementar a função para calcular as despesas com base no preço de compra dos produtos: **4 horas**
- Gerar e exibir o saldo financeiro (lucro - despesas): **4 horas**

**Total estimado para Relatório Financeiro:** 12 horas

#### Interface de Linha de Comando (CLI) (História 8):
- Criar o menu principal com opções claras (Cadastro de usuários, login, gestão de estoque, vendas, relatórios): **3 horas**
- Implementar submenus para cada funcionalidade principal: **3 horas**
- Criar feedback visual para operações bem-sucedidas ou falhas: **2 horas**

**Total estimado para Interface CLI:** 8 horas

**Tempo Total para Sprint 4:** 20 horas

---

## Resumo dos Sprints

| **Sprint**  | **Funcionalidades**                           | **Estimativa Total** |
|-------------|-----------------------------------------------|----------------------|
| **Sprint 1**| Login de Usuário, Cadastro de Usuário          | 21 horas             |
| **Sprint 2**| Cadastro de Produtos, Controle de Estoque (Parte 1) | 22 horas             |
| **Sprint 3**| Realizar Venda, Histórico de Vendas            | 24 horas             |
| **Sprint 4**| Relatório Financeiro, Interface CLI            | 20 horas             |

---

## Conclusão
Este planejamento de sprints permite que o desenvolvimento do sistema seja realizado de maneira incremental, priorizando as funcionalidades essenciais nas primeiras etapas. As estimativas de tempo foram feitas para refletir a simplicidade e o objetivo acadêmico do projeto.
