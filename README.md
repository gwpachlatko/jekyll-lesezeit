# Jekyll Lesezeit (ML)
(Deutsch/English/Français/Italiano/Español/Português)

Anzeige der Wortanzahl und (geschätzten) Lesezeit eines Artikels in Jekyll/\
Displays the word count and (estimated) reading time of an article in Jekyll/\
Affiche le nombre de mots et le temps de lecture (estimé) d'un article dans Jekyll/\
Visualizza il numero di parole e il tempo (stimato) di lettura di un articolo in Jekyll/\
Muestra el número de palabras y el tiempo (estimado) de lectura de un artículo en Jekyll/\
Exibe a contagem de palavras e o tempo de leitura (estimado) de um artigo em Jekyll

## Configuration Site Language

In `_config.yml`:

`lang: de` Display: Deutsch (default)\
`lang: __` Display: Deutsch (fallback; if empty or language not listed)\
`lang: en` Display: English\
`lang: fr` Display: Français\
`lang: it` Display: Italiano\
`lang: es` Display: Español\
`lang: pt` Dispaly: Português

## Configuraton Page Language

If page language happens to be different from site language, set
language individually in “frontmatter” of page.

## Deployment

Copy `lesezeit-if.html` or `lesezeit-case.html` to `/_includes/`

Open: `/_layouts/post.html`

Paste and save: `{%- include lesezeit-if.html -%}` or `{%- include lesezeit-case.html -%}`

## Notes

Use whichever file you prefer; both give identical results.

Avg. estimated reading time: 180 wds/min

License: WTFPL

See also Live Demos:

[Live Demo, German](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-german.html)\
[Live Demo, English](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-english.html)\
[Live Demo, French](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-french.html)\
[Live Demo, Italian](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-italian.html)\
[Live Demo, Spanish](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-spanish.html)\
[Live Demo, Portuguese](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-portuguese.html)
