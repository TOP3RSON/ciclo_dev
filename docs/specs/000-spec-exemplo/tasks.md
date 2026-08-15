# Tasks 001: Cadastro de usuário

> Cada task deve ser pequena o suficiente pra implementar e verificar 
> isoladamente. Marcar [P] quando puder rodar em paralelo (arquivo 
> diferente, sem dependência de outra task).

## Setup
- [ ] T001: [ex: criar migration da tabela users] 
      **Verificação:** migration roda sem erro, tabela existe no banco

## Testes (escritos ANTES da implementação — TDD)
- [ ] T002 [P]: Escrever teste do caso feliz (cadastro com dados válidos)
      **Verificação:** teste existe e falha (RED) — ainda não há implementação
- [ ] T003 [P]: Escrever teste do caso de erro (e-mail duplicado)
      **Verificação:** teste existe e falha (RED)

## Implementação (Core)
- [ ] T004: Implementar endpoint de cadastro
      **Verificação:** T002 e T003 passam (GREEN)
- [ ] T005: Implementar validação de e-mail duplicado
      **Verificação:** T003 passa isoladamente

## Integração
- [ ] T006: Conectar endpoint ao formulário do frontend
      **Verificação:** fluxo completo testado manualmente, dado real salvo no banco

## Polimento
- [ ] T007: Tratar mensagens de erro amigáveis pro usuário
      **Verificação:** erro exibido é legível, não é stack trace cru

---
**Status geral desta spec:** 0/7 concluídas