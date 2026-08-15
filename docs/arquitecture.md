# Arquitetura — [Nome do Projeto]

> Baseado em docs/briefing.md. Referencie o requisito do briefing 
> que motivou cada decisão técnica.

## 1. Formato do produto
[Ex: app mobile Flutter + backend Node.js + Postgres, 
motivado pelo requisito de "funcionar offline" do briefing]

## 2. Stack escolhida
| Camada | Tecnologia | Motivo (ligado ao briefing) |
|---|---|---|
| Frontend | [ex: Flutter] | [ex: público usa Android majoritariamente, precisa de app nativo offline-first] |
| Backend | [ex: Node.js + Express] | [ex: equipe já conhece JS, deploy simples] |
| Banco | [ex: PostgreSQL] | [ex: dados relacionais, precisa de queries complexas] |
| Hospedagem | [ex: Railway] | [ex: baixo custo pra MVP, deploy simples] |

## 3. Alternativas descartadas
[Opção considerada] — descartada porque [motivo]

## 4. Padrão de arquitetura
[Ex: feature-based folders, MVC, hexagonal — o que for, com breve justificativa]

## 5. Convenções de código
- Nomenclatura: [ex: camelCase pra variáveis, PascalCase pra componentes]
- Estrutura de pastas por módulo: [padrão exato]

## 6. Invariantes (nunca violar)
1. [Regra técnica inegociável] — motivo: [breve]
2. [Regra técnica inegociável] — motivo: [breve]

## 7. Fora de escopo técnico (v1)
[O que decidiram não implementar tecnicamente ainda — ex: "sem multi-tenant", "sem cache distribuído"]