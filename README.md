# 🧠 A Máquina de Crença

O arsenal de copy direct-response do **Felipe Loriem**, empacotado como plugin do **Claude Code**.

> Na era da IA, a habilidade não é **criar**. É **diagnosticar**.
> Você diagnostica, a IA executa.

Instala um arsenal inteiro de agentes de copy dentro do seu Claude — do primeiro insight de pesquisa ao webinário no ar. Alguns você comanda; outros disparam sozinhos enquanto você trabalha.

---

## ⚡ Instalação (2 comandos)

Você precisa do [Claude Code](https://claude.com/claude-code) instalado. Dentro dele, digite:

```
/plugin marketplace add felipevagne-max/maquina-de-crenca
/plugin install maquina-de-crenca
```

Pronto. O arsenal já está ativo. Para atualizar quando sair versão nova:

```
/plugin marketplace update maquina-de-crenca
```

---

## 🗂 O que instala

Não é uma skill — é uma **máquina**. Dezenas de agentes cobrindo cada canto do funil:

- **Pesquisa** — a voz real do público, minerada.
- **Crença** — a pesquisa vira o One Belief.
- **Apresentação** — webinário, VSL, carta, advertorial.
- **Criativos** — do zero e por variação do campeão.
- **Funil** — diagnóstico do que vaza e por quê.
- **Automação** — os fluxos que levam o lead até o show-up.
- **E o resto no automático** — CRO, e-mail, pricing, retenção, tráfego… disparando sozinho.

Você não precisa decorar comando nenhum. **Comece a trabalhar copy — o arsenal reage.**

---

## 🔧 Requisitos

Quase tudo roda só com o Claude. Dois recursos usam uma ferramenta local:

| Recurso | Precisa de |
|---------|-----------|
| **Pesquisa de público** | uma **YouTube Data API key** na variável `YOUTUBE_API_KEY` + `python3`. [Como pegar →](https://console.cloud.google.com/apis/library/youtube.googleapis.com) |
| **Transcrição de vídeo** | `ffmpeg` (`brew install ffmpeg`) + `python3`. O resto se instala sozinho. |

---

Feito com ❤️ e Claude Code por **Felipe Loriem** — [@felipe.loriem](https://www.instagram.com/felipe.loriem/).
