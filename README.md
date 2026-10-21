# marcellsa.github.io

Site do portfólio de Inteligência Comercial de Marcel.

Todos os projetos usam a **Basalto Athletic & Menswear**, empresa fictícia criada para o portfólio. Os dados são simulados.

## Estrutura

```
index.html                     página inicial
projetos/01-modelo-comercial.html   modelo de página de case (duplique para os próximos)
assets/css/style.css           estilos (paleta e tipografia)
assets/img/                    prints, diagramas e GIFs dos projetos
.nojekyll                      publica os arquivos como estão, sem processamento
```

## Como publicar um novo projeto

1. Duplique `projetos/01-modelo-comercial.html` e renomeie (ex.: `02-metas-realizado.html`).
2. Preencha os textos marcados com colchetes.
3. No `index.html`, remova o atributo `hidden` do item do projeto.
4. `git add . && git commit -m "feat(projetos): publica case de metas x realizado" && git push`

## Padrão de commits

Este repositório segue Conventional Commits: `tipo(escopo): descrição no imperativo`.

| Tipo | Uso neste site |
|---|---|
| `feat` | Nova página, novo case ou nova seção |
| `fix` | Correção de link quebrado, layout ou erro de texto |
| `docs` | Alteração neste README |
| `style` | Ajuste de CSS sem mudar conteúdo |
| `refactor` | Reorganização de HTML/CSS sem mudança visual |
| `chore` | Arquivos de suporte (`.nojekyll`, pastas, configurações) |
| `content` | Texto dos cases e da seção Sobre (tipo customizado deste repositório) |

Escopos usados: `home`, `projetos`, `empresa`, `sobre`, `css`, `assets`.
