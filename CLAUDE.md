# Instagram da loja — instruções para o Claude

Este repositório guarda as skills usadas para criar os posts da loja no Instagram.

## Regras gerais

- **Idioma:** escreva sempre em português do Brasil (legendas, roteiros, DMs, carrosséis), mesmo que a skill esteja em inglês. Adapte gírias, exemplos e hashtags ao público brasileiro.
- **Contexto:** o perfil é de uma **loja**, não de um criador de conteúdo. Onde a skill falar em "creator", "audience" ou "offer", pense em loja, clientes e produtos/promoções. O objetivo final é venda: todo post deve ter um próximo passo claro (comentar uma palavra, chamar no Direct, clicar no link, ir à loja).
- **Antes de escrever:** leia `marca/marca.md` (voz, público, produtos, preços, regras). Se não existir, ajude a preenchê-lo primeiro a partir de `marca/voz-modelo.md` e `marca/perfil-modelo.md`.

## Onde salvar os arquivos (substitui os caminhos das skills)

As skills originais salvam fora do projeto. Neste repositório use sempre:

| A skill pede | Use |
|---|---|
| `~/.claude/instagram/voice.md` e `~/.fliqr/creator-profile.md` | `marca/marca.md` |
| `~/.claude/instagram/plan.md` | `marca/plano.md` |
| `~/.claude/instagram/swipe.md` | `marca/referencias.md` |
| `~/.claude/instagram/log.md` e `~/.fliqr/post-log.md` | `marca/historico-posts.md` |

## Qual skill usar

| Para… | Skill |
|---|---|
| Planejar a semana/mês de posts | `ig-plan` |
| Legenda de um post ou Reel | `ig-caption` |
| Carrossel (slide a slide) | `ig-carousel` |
| Roteiro de Reel | `ig-reel` |
| Sequência de Stories | `ig-story` |
| Estudar posts que viralizaram | `ig-viral` |
| Reaproveitar um conteúdo em vários formatos | `ig-repurpose` |
| Deixar o texto menos "cara de IA" | `ig-human` / `polish` |
| Melhorar a bio e o perfil | `ig-profile` |
| Revisar o desempenho da conta | `ig-audit` |
| Responder comentários | `ig-comment`, `ig-reply` |
| Comentou a palavra → recebe DM | `comment-to-dm` |
| Conversa de DM que fecha venda | `dm-closer`, `ig-dm` |
| Stories que levam à compra | `story-funnel` |
| Lançamento de produto/coleção ou promoção | `launch-campaign` |
| Sorteio | `giveaway` |
| Brinde/material gratuito para captar contatos | `lead-magnet` |

Quando uma skill citar `caption`, `reel-script` ou `content-plan` (que não foram instaladas), use `ig-caption`, `ig-reel` e `ig-plan`.

Sorteios no Brasil: lembre que promoções comerciais podem exigir autorização (Lei 5.768/71) e que o Instagram exige isentar a Meta de responsabilidade no regulamento.
