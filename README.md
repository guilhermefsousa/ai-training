# IA para Devs — Treinamento Interativo

Curso interativo de Inteligencia Artificial para equipes de desenvolvimento, do zero ao avancado. 100% em portugues brasileiro, sem dependencias externas, pronto para deploy.

## Modulos

| # | Modulo | Conteudo |
|---|--------|----------|
| 01 | Fundamentos de IA Generativa | O que e IA, LLMs, tokens, temperatura, custos |
| 02 | Prompt Engineering | Zero-shot, few-shot, chain-of-thought, framework CRISP |
| 03 | Context Engineering | Janela de contexto, system prompts, RAG intro, memory |
| 04 | Agentes de IA | Loop agente, tools, guardrails, padroes (delegacao, pipeline) |
| 05 | RAG & Tools | Retrieval-Augmented Generation, embeddings, function calling |
| 06 | Ferramentas de IA para Devs | Copilot, Claude Code, Cursor, MCP servers, frameworks |
| 07 | Avaliacao (Eval) | Metricas de qualidade, benchmarks, testes automatizados de IA |

## Como usar

1. Abra `index.html` no navegador (ou acesse via GitHub Pages)
2. Siga os modulos na ordem — cada um tem exercicios interativos e quiz final
3. Nota minima de 4/5 no quiz para marcar o modulo como concluido
4. Ao completar todos os 7, voce recebe um certificado no modulo final

## Deploy

Os arquivos sao 100% estaticos (HTML + CSS + JS inline). Nenhum servidor necessario.

**GitHub Pages:**
1. Faca push para um repositorio publico
2. Va em Settings > Pages > Source: main branch
3. Acesse `https://<usuario>.github.io/<repo>/`

**Qualquer hosting:** basta copiar `index.html` e a pasta `modules/` para o servidor.

## Estrutura

```
ai-training/
  index.html              ← Hub com progresso e links para os modulos
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

O progresso e salvo no `localStorage` do navegador (chave `ai-training-completed-v1`). Cada modulo salva seu ID (1-7) ao atingir nota minima no quiz. O hub exibe checkmarks e barra de progresso automaticamente.

## Requisitos

- Navegador moderno (Chrome, Firefox, Edge, Safari)
- Nenhuma instalacao necessaria
- Funciona offline apos o primeiro carregamento
