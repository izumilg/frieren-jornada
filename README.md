# frieren-jornada
Site de fã em HTML, CSS e JavaScript que conta a jornada do grupo do herói Himmel e a nova viagem de Frieren, Fern e Stark rumo a Ende.
# Frieren Jornada

Site de fã em página única que conta a história do grupo do herói Himmel e a nova viagem de Frieren, Fern e Stark rumo a Ende. A identidade visual segue a página da MSI GeForce RTX 5070 Ti Frieren Edition: fundo branco, tons de azul-lavanda, detalhes dourados e pétalas caindo suavemente.

## O que tem na página

- Hero com título, citação e um vídeo da Frieren e do Himmel
- Seção sobre a passagem do tempo, com contador animado
- Abas alternando entre o Grupo Lendário (Frieren, Himmel, Heiter e Eisen) e a Nova Jornada (Frieren, Fern e Stark)
- Linha do tempo com os marcos da história
- Grimório de Memórias, com feitiços clicáveis
- Pétalas azuis em canvas com fade-in e efeito de parallax ao rolar
- Animações de entrada com IntersectionObserver
- Layout responsivo para celular, tablet e desktop

## Tecnologias

HTML, CSS e JavaScript puro, tudo em um único arquivo. As fontes Cormorant Garamond e Inter vêm do Google Fonts. O vídeo está embutido no próprio HTML, então o arquivo fica com cerca de 480 KB.

## Como rodar

Baixe o repositório e abra o arquivo `index.html` no navegador. Não precisa instalar nada.

## Publicar no GitHub Pages

1. Renomeie `frieren-jornada.html` para `index.html`.
2. Envie os arquivos para o repositório.
3. Em Settings, Pages, escolha a branch `main` e a pasta `/ (root)`.
4. Aguarde alguns minutos e o site fica disponível no endereço que o GitHub mostrar.

## Trocar o vídeo ou a arte

O vídeo fica dentro da div com a classe `frame`, no começo do arquivo. Para usar uma imagem no lugar, troque a tag `<video>` por uma tag `<img src="sua-imagem.png" alt="Frieren e Himmel">`.

## Créditos

Feito por [izumilg](https://github.com/izumilg).

Página de fã sem fins lucrativos. Sousou no Frieren pertence a Kanehito Yamada, Tsukasa Abe e aos seus detentores. A inspiração visual vem da página do produto da MSI, sem vínculo com a empresa.
