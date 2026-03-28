# IA para Devs — Treinamento Interativo

Curso interativo de Inteligência Artificial para equipes de desenvolvimento, do zero ao avançado. 100% em português brasileiro, sem dependências externas, pronto para deploy.

## Módulos

| # | Módulo | Conteúdo |
|---|--------|----------|
| 01 | Fundamentos de IA Generativa | O que é IA, LLMs, tokens, temperatura, custos |
| 02 | Prompt Engineering | Zero-shot, few-shot, chain-of-thought, framework CRISP |
| 03 | Context Engineering | Janela de contexto, system prompts, RAG intro, memória |
| 04 | Agentes de IA | Loop agente, tools, guardrails, padrões (delegação, pipeline) |
| 05 | RAG & Tools | Retrieval-Augmented Generation, embeddings, function calling |
| 06 | Ferramentas de IA para Devs | Copilot, Claude Code, Cursor, MCP servers, frameworks |
| 07 | Avaliação (Eval) | Métricas de qualidade, benchmarks, testes automatizados de IA |

## Como usar

1. Abra `index.html` no navegador (ou acesse via GitHub Pages)
2. Siga os módulos na ordem — cada um tem exercícios interativos e quiz final
3. Nota mínima de 4/5 no quiz para marcar o módulo como concluído
4. Ao completar todos os 7, você recebe um certificado no módulo final

## Deploy

Os arquivos são 100% estáticos (HTML + CSS + JS inline). Nenhum servidor necessário.

**GitHub Pages:**
1. Faça push para um repositório público
2. Vá em Settings > Pages > Source: main branch
3. Acesse `https://<usuario>.github.io/<repo>/`

**Qualquer hosting:** basta copiar `index.html` e a pasta `modules/` para o servidor.

## Estrutura

```
ai-training/
  index.html              ← Hub com progresso e links para os módulos
  modules/
    01-fundamentos.html
    02-prompt-engineering.html
    03-context-engineering.html
    04-agentes.html
    05-rag-tools.html
    06-ferramentas.html
    07-eval.html
```

## Progresso

O progresso é salvo no `localStorage` do navegador (chave `ai-training-completed-v1`). Cada módulo salva seu ID (1-7) ao atingir nota mínima no quiz. O hub exibe checkmarks e barra de progresso automaticamente.

## Requisitos

- Navegador moderno (Chrome, Firefox, Edge, Safari)
- Nenhuma instalação necessária
- Funciona offline após o primeiro carregamento
