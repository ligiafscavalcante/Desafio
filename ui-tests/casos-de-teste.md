# 📋 Casos de Teste — Sauce Demo

---

## 🧪 CT01 — Login válido

**Objetivo:**  
Validar login com usuário padrão.

**Pré-condição:**  
Usuário cadastrado e ativo.

**Passos:**
1. Acessar a tela de login.
2. Informar usuário válido.
3. Informar senha válida.
4. Clicar em Login.

**Resultado Esperado:**  
Acesso à página de produtos.

---

## 🧪 CT02 — Login inválido

**Objetivo:**  
Validar tentativa de login com credenciais incorretas.

**Passos:**
1. Acessar tela de login.
2. Informar usuário e/ou senha inválidos.
3. Clicar em Login.

**Resultado Esperado:**  
Exibição de mensagem de erro.

---

## 🧪 CT03 — Ordenação de produtos

**Objetivo:**  
Validar ordenação por preço (menor → maior).

**Passos:**
1. Realizar login.
2. Selecionar opção de ordenação por preço crescente.

**Resultado Esperado:**  
Produtos exibidos em ordem correta de menor para maior preço.

---

## 🧪 CT04 — Fluxo completo de compra

**Objetivo:**  
Validar o processo completo de compra.

**Passos:**
1. Fazer login.
2. Adicionar item ao carrinho.
3. Acessar carrinho.
4. Clicar em Checkout.
5. Preencher dados obrigatórios.
6. Finalizar compra.

**Resultado Esperado:**  
Compra concluída com sucesso e mensagem de confirmação.

---

## 🧪 CT05 — Remover item do carrinho

**Objetivo:**  
Validar remoção de produto do carrinho.

**Passos:**
1. Fazer login.
2. Adicionar produto ao carrinho.
3. Acessar carrinho.
4. Remover item.

**Resultado Esperado:**  
Carrinho atualizado corretamente, sem o item removido.

---

## 🧪 CT06 — Navegação

**Objetivo:**  
Validar navegação entre páginas principais.

**Passos:**
1. Realizar login.
2. Acessar páginas como Produtos, Carrinho e Menu.

**Resultado Esperado:**  
Navegação funcionando corretamente entre as telas.

---

## 🧪 CT07 — Logout

**Objetivo:**  
Validar funcionalidade de logout.

**Passos:**
1. Estar logado no sistema.
2. Acessar menu.
3. Clicar em Logout.

**Resultado Esperado:**  
Retorno para tela de login.
