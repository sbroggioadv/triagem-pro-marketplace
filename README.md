# Triagem Pro — Marketplace

Marketplace oficial do **Triagem Pro** para Claude Code e Claude Cowork.

## Como instalar (Claude Cowork)

1. Abra o Cowork (claude.ai)
2. Vá em **Settings → Plugins → Marketplace → Add from URL**
3. Cole:

```
https://github.com/sbroggioadv/triagem-pro-marketplace
```

4. Selecione `triagem-pro` na lista de plugins disponíveis e clique em **Install**

## Como instalar (Claude Code CLI)

```
/plugin marketplace add https://github.com/sbroggioadv/triagem-pro-marketplace
/plugin install triagem-pro
```

## O que vem instalado

- **Triagem inteligente** — `verifica meu zap` → tabela classificada por urgência (URGENTE / ATRASADA / IMPORTANTE / NORMAL / RECENTE)
- **Redator com sua voz** — agente que lê seu estilo de escrita e devolve 1–3 opções de mensagem (você aprova qual sai)
- **Guardrail OAB** — 5 travas éticas aplicadas em toda mensagem (promessa de resultado, dados sensíveis, aconselhamento a lead, captação, emoji em comunicação profissional)
- **4 comandos de supervisão** — `/sem-resposta`, `/tempo-resposta`, `/resumo-dia`, `/grupos-inativos`
- **Wizard `/configurar`** — instalação conversacional 100% pelo chat (sem código, sem terminal)

## Após instalar

Digite no chat do Claude:

```
/configurar
```

Em 15 minutos o agente está pronto. Detalhes completos em [INSTALAR.md do plugin](https://github.com/sbroggioadv/triagem-pro/blob/main/INSTALAR.md).

## Status

- **Versão atual:** v0.1.0 (publicada em 2026-05-24)
- **v0.2.0 em desenvolvimento:** motor `WebFetch` nativo (suporte completo ao Cowork, sem Python local)

## Plugin source

[github.com/sbroggioadv/triagem-pro](https://github.com/sbroggioadv/triagem-pro)

---

Triagem Pro · uso e distribuição sob autorização.
