# Portfólio - João Madeira

Portfólio pessoal em HTML/CSS estático, hospedado no GitHub Pages, com foco em BI, FP&A e Engenharia de Dados.

🔗 [joaomadeir4.github.io/portfolio](https://joaomadeir4.github.io/portfolio/)

## Estrutura

```mermaid
flowchart TD
    A[index.html] --> B[Seções do portfólio]
    B --> B1[Sobre / Experiência]
    B --> B2[Skills técnicas]
    B --> B3[Projetos]
    B --> B4[Contato]

    A --> C[favicon.svg]
    A --> D[Google Analytics GA4]

    E[GitHub Pages] -->|build & deploy| A
    F[Visitante] -->|acessa| E
    D -->|coleta métricas de| F
```

## Stack

- HTML5 + CSS puro
- Google Fonts (Syne, Inter)
- Google Analytics (GA4) para métricas de acesso
- Deploy automático via GitHub Pages
