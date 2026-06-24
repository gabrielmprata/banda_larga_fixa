# 🛜 Anatel - Acessos de Banda Larga Fixa no Brasil

<p align="left">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge" #vitrinedev/>  

<img src="http://img.shields.io/static/v1?label=vers%C3%A3o%20do%20projeto&message=v3.0&color=red&style=for-the-badge&logo=github"/>
</p>

Página estática construída para o GitHub Pages, explorando dados públicos dos acessos de Banda Larga Fixa no Brasil.

https://gabrielmprata.github.io/banda_larga_fixa/

## 🛠️ Tecnologias

### Estrutura

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/> em um único arquivo (`index.html`) — sem build, sem framework de componentes. Ideal pra GitHub Pages porque pode ser publicado direto.

### Estilo
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/> definindo uma paleta de design tokens (rose, teal, amber, ink, mist).
- Fontes do **Google Fonts**: **Playfair Display** (serifada, para títulos), **Inter** (sans-serif, para texto) e **JetBrains Mono** (monoespaçada, para labels/dados).
- Efeitos modernos como `backdrop-filter: blur()` na navbar (efeito vidro/glassmorphism).

## 🎨 UI/UX

Paleta completa usada na página:

## Background

| Variável     | Hex       | Uso                                |
|--------------|-----------|-------------------------------------|
| `--bg`       | ![#06090f](https://placehold.co/15x15/06090f/06090f/png) `#06090f` | Fundo geral da página              |
| `--surface`  | ![#0a0f1a](https://placehold.co/15x15/0a0f1a/0a0f1a/png) `#0a0f1a` | Superfícies (menu mobile, nav)     |
| `--card`     | ![#0e1520](https://placehold.co/15x15/0e1520/0e1520/png) `#0e1520` | Fundo dos cards                    |
| `--card2`    | ![#111d2e](https://placehold.co/15x15/111d2e/111d2e/png) `#111d2e` | Hover de cards/stats                |

## Bordas

| Variável     | Hex       | Uso                          |
|--------------|-----------|-------------------------------|
| `--border`   | ![#1a2d45](https://placehold.co/15x15/1a2d45/1a2d45/png) `#1a2d45` | Borda padrão                  |
| `--border2`  | ![#243d59](https://placehold.co/15x15/243d59/243d59/png) `#243d59` | Borda em destaque/hover        |

## Cores de destaque (accent)

| Variável    | Hex       | Uso                                                       |
|-------------|-----------|-------------------------------------------------------------|
| `--cyan`    | ![#00d4ff](https://placehold.co/15x15/00d4ff/00d4ff/png) `#00d4ff` | Cor-assinatura — títulos, links, badges, glow              |
| `--blue`    | ![#1a6fff](https://placehold.co/15x15/1a6fff/1a6fff/png) `#1a6fff` | Segunda cor de destaque (gradientes, hero)                 |
| `--orange`  | ![#ff6b35](https://placehold.co/15x15/ff6b35/ff6b35/png) `#ff6b35` | Alertas, seção "Problemas Identificados"                   |
| `--green`   | ![#00e676](https://placehold.co/15x15/00e676/00e676/png) `#00e676` | Indicadores positivos (crescimento, status)                |

## Texto

| Variável     | Hex       | Uso                          |
|--------------|-----------|--------------------------------|
| `--head`     | ![#ddeeff](https://placehold.co/15x15/ddeeff/ddeeff/png) `#ddeeff` | Títulos (h1–h4)                |
| `--text`     | ![#b8cfe0](https://placehold.co/15x15/b8cfe0/b8cfe0/png) `#b8cfe0` | Corpo de texto principal        |
| `--muted2`   | ![#6a8aaa](https://placehold.co/15x15/6a8aaa/6a8aaa/png) `#6a8aaa` | Texto secundário                |
| `--muted`    | ![#4a6580](https://placehold.co/15x15/4a6580/4a6580/png) `#4a6580` | Texto terciário/labels          |

## Glows / Efeitos

| Variável        | Valor                              | Uso                              |
|-----------------|--------------------------------------|------------------------------------|
| `--glow-cyan`   | ![#00d4ff](https://placehold.co/15x15/00d4ff/00d4ff/png) `0 0 32px rgba(0,212,255,.12)`      | Box-shadow de destaque cyan        |
| `--glow-blue`   | ![#1a6fff](https://placehold.co/15x15/1a6fff/1a6fff/png) `0 0 32px rgba(26,111,255,.12)`     | Box-shadow de destaque azul        |

## Tons adicionais (hardcoded, fora das variáveis)

| Hex       | Uso                                  |
|-----------|----------------------------------------|
| ![#6ea8ff](https://placehold.co/15x15/6ea8ff/6ea8ff/png) `#6ea8ff` | Texto de tags/badges azuis             |
| ![#a8d8f0](https://placehold.co/15x15/a8d8f0/a8d8f0/png) `#a8d8f0` | Texto base dos blocos de código DAX    |
| ![#c792ea](https://placehold.co/15x15/c792ea/c792ea/png) `#c792ea` | Funções DAX (roxo)                     |
| ![#f78c6c](https://placehold.co/15x15/f78c6c/f78c6c/png) `#f78c6c` | Números DAX (laranja)                  |

---
