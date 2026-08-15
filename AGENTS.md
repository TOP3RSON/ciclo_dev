# AGENTS.md — [Nome do Projeto]

> Leia este arquivo toda sessão antes de tocar em código. 
> Documentação detalhada vive em /docs; este arquivo é o "manual de operação".

## O que este projeto é
[1-2 frases resumindo o produto — referencia o briefing.md]
Leia docs/briefing.md primeiro para contexto de produto.
Leia docs/arquitetura.md para o desenho técnico completo.

## Stack (não desviar sem atualizar docs/arquitetura.md)
- Linguagem: [ex: TypeScript]
- Framework: [ex: Next.js 15]
- Banco de dados: [ex: PostgreSQL via Supabase]
- Hospedagem: [ex: Vercel]

## Estrutura de pastas
[árvore simplificada do projeto]

## Regras de processo (workflow)
1. Uma spec por vez. Não iniciar spec N+1 sem a spec N estar com testes passando.
2. Nenhum código sem teste. Escrever teste antes da implementação (TDD).
3. Nenhum código morto ou feature pela metade — se não terminou, não faz commit na main.
4. Documentar o "porquê" no código, não o "o quê" (comentários só para decisões não óbvias).
5. Não refatorar fora do escopo da spec atual.

## Como testar
[comando exato, ex: `npm run test`]

## Como commitar
- Mensagem no formato: `[spec-XXX] descrição curta`
- Rodar testes antes de commitar
- Atualizar CHANGELOG.md a cada commit (ver seção de changelog)

## Limites de segurança do agente
- Nunca rodar comandos destrutivos (`rm -rf`, `DROP TABLE`) sem confirmação explícita
- Nunca commitar credenciais/secrets
- [outras regras suas]

## Erros já cometidos — não repetir
[Lista viva, cresce com o tempo]
- [Data] [O que aconteceu] → [regra criada por causa disso]

## O que este projeto NÃO é (fora de escopo)
[lista do que decidiram deliberadamente não fazer, evita scope creep]