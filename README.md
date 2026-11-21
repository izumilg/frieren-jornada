# frieren-jornada
Site de fã em HTML, CSS e JavaScript que conta a jornada do grupo do herói Himmel e a nova viagem de Frieren, Fern e Stark rumo a Ende.
Frieren Jornada

Site de fã que conta a história do grupo do herói Himmel e da nova viagem de Frieren, Fern e Stark. A ideia é passar o clima da obra: calmo, nostálgico e um pouco melancólico, com muito espaço em branco e pétalas azuis caindo devagar. O visual foi inspirado na página da MSI GeForce RTX 5070 Ti Frieren Edition.

Pré-visualização do site

Sobre o site

Sousou no Frieren (Frieren: Beyond Journey's End) começa depois que o herói Himmel derrota o Rei Demônio. Para Frieren, uma elfa de mais de mil anos, os dez anos de viagem com o grupo foram quase nada. Só quando Himmel morre, cinquenta anos depois, ela percebe que não chegou a conhecê-lo de verdade, e parte numa nova jornada para entender o que viveu. O site resume essa história em uma única página de rolagem.

Seções
Hero: título, citação e um vídeo curto da Frieren e do Himmel.
A Jornada: explica a passagem do tempo, com um contador animado (10 anos de viagem, 50 até a despedida, mais de 1000 de vida da elfa).
O Grupo: duas abas, uma com o Grupo Lendário (Frieren, Himmel, Heiter e Eisen) e outra com a Nova Jornada (Frieren, Fern e Stark). Cada card traz a classe, o papel, uma breve história e um traço marcante.
Linha do Tempo: os marcos da história, da derrota do Rei Demônio até a viagem para Ende.
Grimório de Memórias: feitiços sem utilidade aparente que Frieren coleciona. Ao clicar em um card, a história do feitiço aparece com uma pequena animação de pétalas.
Detalhes do visual
Fundo branco, com azul-lavanda #8faadc e #b4c6e7, dourado pálido #c5a880 e um acento vermelho discreto.
Títulos em Cormorant Garamond e texto corrido em Inter.
Pétalas azuis desenhadas em canvas, com fade-in ao abrir e parallax ao rolar.
Menu fixo que ganha efeito de vidro fosco ao rolar.
Animações de entrada com IntersectionObserver e layout responsivo para celular, tablet e desktop.
Tecnologias

HTML, CSS e JavaScript puro, tudo em um único arquivo. As fontes vêm do Google Fonts e o vídeo está embutido no próprio HTML.

Como rodar

Baixe o repositório e abra o index.html no navegador. Não precisa instalar nada.

Publicar no GitHub Pages
Deixe o arquivo principal com o nome index.html.
Envie os arquivos para o repositório.
Em Settings, Pages, escolha a branch main e a pasta / (root).
Espere alguns minutos e o GitHub mostra o endereço do site.
Personalizar

O vídeo fica na div com a classe frame, no começo do arquivo. Para usar uma imagem, troque a tag <video> por <img src="sua-imagem.png" alt="Frieren e Himmel">. O arquivo preview.png citado acima é um print da página que você pode adicionar à raiz do repositório.

Créditos

Feito por izumilg.

Página de fã sem fins lucrativos. Sousou no Frieren pertence a Kanehito Yamada, Tsukasa Abe e aos seus detentores. A inspiração visual vem da página de produto da MSI, sem vínculo com a empresa.
