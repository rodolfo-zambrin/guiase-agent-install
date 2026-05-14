# Guia-se CMO — Agente de Marketing para Claude Code

Agente autônomo de marketing da Guia-se Maringá. Instala o CMO virtual + 41 skills especializadas de marketing direto no seu Claude Code.

## Instalação (1 comando)

```bash
bash <(curl -sL https://raw.githubusercontent.com/rodolfo-zambrin/guiase-agent-install/main/install.sh)
```

Ou, se você já tem o arquivo:

```bash
bash install.sh
```

## O que é instalado

- **`/guiase-cmo`** — Agente CMO com contexto completo da Guia-se
- **41 marketing skills** especializadas:
  - `/paid-ads` — Estratégia Meta Ads + Google Ads
  - `/ad-creative` — Geração de criativos em escala
  - `/copywriting` — Copy de conversão
  - `/seo-audit` — Auditoria de SEO
  - `/social-content` — Calendário de conteúdo
  - `/analytics-tracking` — Tracking e atribuição
  - `/email-sequence` — Sequências de email
  - `/page-cro` — Otimização de landing pages
  - ... e mais 33 skills

## Como usar

Abra o Claude Code e:

- **Ativar o agente CMO:** Digite `/guiase-cmo`
- **Usar uma skill direto:** Digite `/paid-ads` ou `/ad-creative` etc.
- **Pedir naturalmente:** _"analisa essa campanha"_, _"cria copy para Meta"_, _"quero uma estratégia de SEO"_ — o agente reconhece automaticamente

## Requisitos

- [Claude Code](https://claude.ai/code) instalado
- macOS ou Linux
- `git` instalado (para baixar as skills base)
