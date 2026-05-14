# 📌 Plano de Testes — API Testing (Restful-Booker)

## 1. Objetivo

Validar as funcionalidades obrigatórias da API Restful-Booker, garantindo que o sistema permita autenticação, criação, consulta, atualização e exclusão de reservas, além da validação de campos obrigatórios.

---

## 2. Escopo

### ✔ Funcionalidades Incluídas (Nível Obrigatório)

- Autenticação (geração de token)
- CRUD de reservas:
  - Criar reserva (POST)
  - Consultar reserva (GET)
  - Atualizar reserva (PUT)
  - Atualização parcial (PATCH)
  - Remover reserva (DELETE)
- Validação de campos obrigatórios
- Tratamento básico de erros (status codes e mensagens)

### ❌ Funcionalidades Excluídas

- Testes de performance
- Testes de segurança avançados
- Automação com scripts
- Testes de carga
- Testes de integração externa

---

## 3. Estratégia de Teste

- Testes funcionais manuais via Postman (ou ferramenta equivalente)
- Validação de:
  - Status code
  - Estrutura da resposta
  - Campos obrigatórios
  - Mensagens de erro
- Utilização de Collection organizada
- Uso de variáveis de ambiente
- Registro de evidências (prints das requisições e respostas)

---

## 4. Cenários de Teste Cobertos

### 🔐 Autenticação
- Gerar token com credenciais válidas
- Validar retorno do token
- Validar comportamento com credenciais inválidas

### 📦 CRUD de Reservas
- Criar reserva com dados válidos
- Consultar reserva por ID
- Atualizar reserva existente
- Atualizar parcialmente reserva
- Excluir reserva

### ❗ Validação de Dados
- Criar reserva sem campos obrigatórios
- Enviar dados inválidos
- Validar retorno de erro apropriado

---

## 5. Critérios de Aceitação

- API retorna status codes corretos (200, 201, 400, 404, etc.)
- Dados criados são persistidos corretamente
- Atualizações refletem nos registros
- Exclusões removem corretamente os dados
- Erros são tratados com mensagens claras
- Evidências documentadas

---

## 6. Ambiente de Teste

- API pública Restful-Booker
- Ferramenta: Postman
- Ambiente configurado com:
  - Base URL
  - Token
  - Variáveis dinâmicas (ex: booking_id)

---

## 7. Premissas

- API está disponível e funcional durante os testes
- Dados podem ser criados e excluídos livremente
- Ambiente não possui bloqueios de autenticação adicionais

---

## 8. Riscos

- Instabilidade do serviço externo
- Conflito de dados entre execuções
- Dependência de conectividade com internet

---

## 9. Evidências

- Capturas de tela das requisições
- Registro de respostas da API
- Status codes obtidos
- Evidências organizadas por cenário

---

## 10. Ferramentas Utilizadas

- Postman
- GitHub (documentação)
- Markdown para documentação
