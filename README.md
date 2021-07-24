# Jekyll Lesezeit (ML)

Displays the word count and (estimated) reading time of an article in Jekyll\
Available languages: Deutsch/English/Français/Italiano/Español/Português/čeština

## Configuration Site Language

In `_config.yml`:

`lang: de` Display: Deutsch (default)\
`lang:  ` Display: English (fallback; if empty or language not listed)\
`lang: en` Display: English\
`lang: fr` Display: Français\
`lang: it` Display: Italiano\
`lang: es` Display: Español\
`lang: pt` Dispaly: Português\
`lang: cz` Dispaly: čeština

## Configuration Page Language

If page language happens to be different from site language, set
language individually in “frontmatter” of page.

## Deployment

Copy `lesezeit.html` to `/_includes/`

Open: `/_layouts/post.html`

Paste `{%- include lesezeit.html -%}` and save.

## Notes

Avg. estimated reading time: 180 wds/min

License: WTFPL

See also Live Demos:

[Live Demo, German](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-german.html)\
[Live Demo, English](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-english.html)\
[Live Demo, French](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-french.html)\
[Live Demo, Italian](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-italian.html)\
[Live Demo, Spanish](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-spanish.html)\
[Live Demo, Portuguese](https://gwpachlatko.github.io/emwd/fehlersuche/2020/02/19/testing-lesezeit-portuguese.html)\
[Live Demo, Czech](https://gwpachlatko.github.io/emwd/fehlersuche/2020/12/04/testing-lesezeit-czech.html)\
[Detailed information concerning other files in this repository in English](https://gwpachlatko.github.io/anything-goes/software/2020/02/21/jekyll-lesezeit-howto.html)
