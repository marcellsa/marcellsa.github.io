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
4. `git add . && git commit -m "Publica projeto 2" && git push`
