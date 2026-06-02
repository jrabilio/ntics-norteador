# 🎯 NTICS Projetos — Clareza da Semana

Infográfico semanal do Escritório de Projetos NTICS — o **Norteador** que orienta a reunião Hands On toda semana.

## O que é

Um painel visual gerado automaticamente a partir do ClickUp, que apresenta:

- **Projetos Críticos** da semana
- **Projetos em Planejamento**, Execução, Finalização e Próximo Mês
- **Quadro de Execuções em Campo** — dia a dia, com etiquetas de NTICS em campo e cobertura
- **Áreas de Apoio e Gestão** — Financeiro, Lab, Vendas, Inscrições
- **Principais Ações** da semana

## Como funciona

O norteador é gerado via Claude (claude.ai) com uma skill personalizada (`norteador-semana`) que:

1. Puxa os projetos do ClickUp automaticamente
2. Classifica cada projeto no bloco correto pela Fase registrada
3. Monta o quadro de campo via etiqueta `📍execução`
4. Gera o HTML pronto para revisão e publicação

## Estrutura do repositório

```
/
├── index.html          ← Norteador da semana atual (atualizado toda semana) 
├── historico/          ← Norteadores anteriores
│   └── norteador-25-29-maio-2026.html
└── README.md
```

## Atualização semanal

Todo domingo o norteador é gerado e o `index.html` é substituído pela versão nova.
O histórico é mantido na pasta `/historico`.

---

*NTICS Projetos — Escritório de Projetos | Joinville, SC*
