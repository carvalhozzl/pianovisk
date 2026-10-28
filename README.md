# pianovisk

Site animado de página única: mar cinza de dia, luz dourada de noite.

## Como abrir

Abra o `index.html` no navegador. Ou, para servir localmente:

```bash
python -m http.server 5517
```

e acesse http://localhost:5517.

## Estrutura

- `index.html` — página completa (HTML, CSS e JS num arquivo só, sem dependências além das fontes do Google Fonts)
- `fotos/` — as 5 fotos usadas no site

## O que tem

- Abertura com o nome montado letra por letra
- Topo com luzes flutuantes em canvas e brilho que segue o mouse
- Capítulos "dia" e "noite" com parallax e revelação ao rolar
- Galeria arrastável com inclinação 3D e visualização em tela cheia
- Frase que acende palavra por palavra
- Respeita a preferência de "reduzir movimento" do sistema
