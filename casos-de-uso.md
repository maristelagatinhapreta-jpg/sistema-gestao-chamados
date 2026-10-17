# Casos de Uso - Sistema de Gestão de Chamados

## UC01 - Login no Sistema

**Ator:** Usuário

**Descrição:**
Permite que o usuário acesse o sistema utilizando e-mail e senha.

**Fluxo Principal:**
1. Informar e-mail.
2. Informar senha.
3. Clicar em Entrar.
4. Sistema valida os dados.
5. Sistema permite acesso.

**Resultado Esperado:**
Usuário autenticado.

---

## UC02 - Abrir Chamado

**Ator:** Usuário

**Descrição:**
Permite registrar uma solicitação de suporte técnico.

**Fluxo Principal:**
1. Selecionar "Novo Chamado".
2. Informar título.
3. Descrever problema.
4. Salvar chamado.

**Resultado Esperado:**
Chamado cadastrado com sucesso.

---

## UC03 - Consultar Chamados

**Ator:** Usuário

**Descrição:**
Permite visualizar os chamados registrados.

**Fluxo Principal:**
1. Acessar menu Chamados.
2. Sistema exibe lista de chamados.

**Resultado Esperado:**
Lista apresentada ao usuário.

---

## UC04 - Atualizar Status

**Ator:** Técnico

**Descrição:**
Permite alterar o andamento do atendimento.

**Fluxo Principal:**
1. Localizar chamado.
2. Selecionar status.
3. Salvar alteração.

**Resultado Esperado:**
Status atualizado.

---

## UC05 - Encerrar Chamado

**Ator:** Técnico

**Descrição:**
Permite finalizar um chamado concluído.

**Fluxo Principal:**
1. Acessar chamado.
2. Selecionar Encerrar.
3. Confirmar ação.

**Resultado Esperado:**
Chamado encerrado.
