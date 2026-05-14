## CT08 — Autenticação (Criar Token)

**Passos:**
1. Enviar requisição POST para endpoint de autenticação
2. Informar credenciais válidas

**Resultado Esperado:**
- Status 200
- Token retornado

---

## CT09 — Criar Reserva (POST)

**Passos:**
1. Enviar dados completos da reserva

**Resultado Esperado:**
- Status 200 ou 201
- Reserva criada
- ID retornado

---

## CT10 — Consultar Reserva (GET)

**Passos:**
1. Informar ID da reserva
2. Realizar requisição GET

**Resultado Esperado:**
- Status 200
- Dados da reserva retornados

---

## CT11 — Atualizar Reserva (PUT)

**Passos:**
1. Informar ID
2. Enviar dados atualizados

**Resultado Esperado:**
- Status 200
- Dados alterados

---

## CT12 — Deletar Reserva (DELETE)

**Passos:**
1. Informar ID válido
2. Enviar requisição DELETE

**Resultado Esperado:**
- Status 201 ou 204
- Reserva removida

---

## CT13 — Validação de Campos Obrigatórios

**Passos:**
1. Enviar requisição sem campos obrigatórios

**Resultado Esperado:**
- Status de erro (ex: 400)
- Mensagem de validação retornada
