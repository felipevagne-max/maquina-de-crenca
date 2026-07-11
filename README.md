# 🧠 A Máquina de Crença

O arsenal de copy direct-response do **Felipe Loriem**, empacotado como plugin do **Claude Code**.

> Na era da IA, a habilidade não é **criar**. É **diagnosticar**.
> Você diagnostica, a IA executa.

Instala 9 agentes proprietários que fazem o Claude pensar como um copywriter DR de elite — do zero ao webinário, do funil ao criativo.

---

## ⚡ Instalação (2 comandos)

Você precisa do [Claude Code](https://claude.com/claude-code) instalado. Dentro dele, digite:

```
/plugin marketplace add felipevagne-max/maquina-de-crenca
/plugin install maquina-de-crenca
```

Pronto. As skills já estão ativas. Teste:

```
/mentecopy
```

Para atualizar quando sair versão nova: `/plugin marketplace update maquina-de-crenca`.

---

## 🗂 As 9 skills

| Skill | Trigger | O que faz |
|-------|---------|-----------|
| **MenteCopy** | `/mentecopy` | Ativa a lente de pensamento DR black (economia > copy, estilo Sultanic). Compõe com todas as outras. |
| **SherlockTube** | `/sherlocktube` | Minera comentários do YouTube e extrai a voz real do público — dores, desejos, crenças, objeções. |
| **MasterBelief** | `/masterbelief` | Transforma a pesquisa no **One Belief** — as 10 perguntas de persuasão viradas numa narrativa só. |
| **Vórtice** | `/vortice` | Monta a apresentação de vendas inteira (webinário, VSL, carta) num framework campeão. |
| **RaioX** | `/raiox` | Diagnóstico de funil pela Cadeia das 5 Crenças — acha onde vaza e por quê. |
| **AdsLoriem** | `/adsloriem` | Adapta criativos validados para novos nichos/experts, preservando a estrutura persuasiva. |
| **SuperFluxo** | `/superfluxo` | Gera fluxos de automação WhatsApp (captura + antecipação) prontos pra importar. |
| **Slides** | `/slides` | Gera slides de webinário de vendas do zero. |
| **Comentários** | `/comentarios` | Transforma um MP4 de webinário em chat orgânico simulado (CSV cronometrado). |

---

## 🔁 O fluxo (a rotina de copy)

O jeito de usar em sequência — cada etapa alimenta a próxima:

```
SherlockTube  →  MasterBelief  →  Vórtice / AdsLoriem
 (a voz)          (a crença)        (a execução)
                       ↑
                   MenteCopy (a lente, sempre ligada)
                       ↓
                   RaioX (diagnostica o funil no ar)
```

A IA roda cada etapa. Você fica **entre** elas, diagnosticando.

---

## 🔧 Requisitos por skill

A maioria das skills roda **só com o Claude** (raciocínio + geração de texto/HTML). Duas precisam de ferramenta local:

| Skill | Precisa de |
|-------|-----------|
| **SherlockTube** | uma **YouTube Data API key** na variável de ambiente `YOUTUBE_API_KEY` + `python3`. [Como pegar a key →](https://console.cloud.google.com/apis/library/youtube.googleapis.com) |
| **Comentários** | `ffmpeg` instalado (`brew install ffmpeg`) + `python3`. O Whisper se instala sozinho no primeiro uso. |

As demais 7 skills não têm dependência externa. Skills que geram HTML/slides podem sugerir deploy no Vercel — use suas próprias contas.

---

Feito com ❤️ e Claude Code por **Felipe Loriem** — [@felipe.loriem](https://www.instagram.com/felipe.loriem/).
