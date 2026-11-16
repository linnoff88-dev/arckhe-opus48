# Claude Opus 4.8 â€” RelatÃ³rio de LanÃ§amento

RelatÃ³rio de pesquisa sobre o lanÃ§amento do **Claude Opus 4.8** (Anthropic), publicado via GitHub Pages.

ðŸ”— **PÃ¡gina:** https://inematds.github.io/opus48/

## Resumo

A Anthropic lanÃ§ou o **Claude Opus 4.8** (`claude-opus-4-8`) em **28/05/2026**, ~42 dias apÃ³s o Opus 4.7 â€” o ciclo mais rÃ¡pido da famÃ­lia 4.x. Modelo de raciocÃ­nio hÃ­brido com **1M de tokens** de contexto (200k no Foundry), 128k de saÃ­da e pensamento adaptativo, focado em codificaÃ§Ã£o agÃªntica de longo horizonte.

| | |
|---|---|
| **LanÃ§amento** | 28/05/2026 (quinta-feira) |
| **API ID** | `claude-opus-4-8` |
| **Contexto / saÃ­da** | 1M tokens (200k Foundry) / 128k |
| **PreÃ§o regular** | US$ 5/M entrada Â· US$ 25/M saÃ­da (inalterado vs 4.7) |
| **Fast mode** | 2,5Ã— mais rÃ¡pido Â· ~3Ã— mais barato que o do 4.7 (US$ 10/US$ 50) |
| **Disponibilidade** | claude.ai, API, Bedrock, Vertex AI, Foundry, GitHub Copilot |

### Benchmarks (auto-reportados pela Anthropic)

- **SWE-bench Pro:** 69,2% (4.7: 64,3% Â· GPT-5.5: 58,6% Â· Gemini 3.1 Pro: 54,2%)
- **SWE-bench Verified:** 88,6%
- **OSWorld (uso de computador):** 83,4% Â· **Online-Mind2Web:** 84%
- **USAMO:** 96,7% Â· **HLE c/ ferramentas:** 57,9% Â· **AA Index:** 61,4

### Novidades

- Controle de esforÃ§o no claude.ai (Low/Medium/High/Extra/Max)
- Dynamic Workflows em research preview (centenas de subagentes paralelos no Claude Code)
- Fast mode ~3Ã— mais barato; API Messages aceita `system` inline

## Metodologia

Pesquisa multi-fonte com verificaÃ§Ã£o adversarial: 5 Ã¢ngulos de busca Â· 20 fontes Â· 100 alegaÃ§Ãµes extraÃ­das Â· 25 verificadas por votaÃ§Ã£o 3-vias â†’ **25 confirmadas, 0 refutadas**.

> **Ressalva:** benchmarks sÃ£o auto-reportados pela Anthropic, sem auditoria independente em escala. RelatÃ³rio produzido em 30/05/2026 (cobertura de lanÃ§amento). Fontes e ressalvas completas na [pÃ¡gina](https://inematds.github.io/opus48/).

---

Projeto adaptado da comunidade INEMA TDS - Marca Arckhe