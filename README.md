# Revis-o-HTMLCSS


# ConsoleLab — Evolução dos Consoles

Trabalho de revisão de HTML e CSS que usa a história dos videogames como tema. Site estático com 5 páginas, navegação fixa e conteúdo interativo (quiz + player de áudio).

## Estrutura

```
HTMLeCSS/
├── index.html          # Página inicial
├── historia.html        # História dos consoles
├── geracoes.html         # Gerações de consoles
├── comparativo.html      # Tabela comparativa
├── quiz.html              # Interação (quiz + áudio)
├── style.css              # Estilo global do site
├── audio/
│   ├── historia-dos-consoles.mp3
│   └── LEIA-ME.txt
├── imagens/images/
│   ├── Console1.png
│   ├── Console3.png
│   ├── Console5.png
│   └── ConsoleAtual.png
└── Revisão/Revisão/       # Exercícios extras de divs e tabelas
    ├── index.html
    ├── divs.html
    ├── tabelas.html
    ├── estilo.css
    └── estrutura_site.png
```

## Páginas

- **Início** — apresentação do site e cards de navegação para as demais seções.
- **História** — principais momentos da evolução dos consoles.
- **Gerações** — mudanças em gráficos, controles e mídias ao longo do tempo.
- **Comparativo** — tabela comparando diferentes épocas.
- **Interação** — quiz e player de áudio (`historia-dos-consoles.mp3`).

## Como usar

1. Abra `index.html` no navegador (não precisa de servidor).
2. Para o player de áudio em `quiz.html` funcionar, o arquivo `historia-dos-consoles.mp3` já deve estar dentro da pasta `audio/`.

## Tecnologias

HTML5 e CSS3 puros, sem frameworks ou JavaScript de terceiros.

## Pasta Revisão

Contém exercícios separados de prática com `<div>` e `<table>`, usados como material de revisão antes do projeto principal.
