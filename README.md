# SyntazWear — E-commerce de Tênis

Este repositório contém o front-end estático de um e-commerce de tênis (SyntazWear). O projeto foi pensado como um site responsivo com organização semântica e uma base CSS modular.

## Visão geral

- HTML semântico organizado em seções: header, hero, categorias, grid de produtos e footer.
- Estrutura de CSS modular com reset, variáveis, estilos base e componentes.
- Imagens e ícones localizados na pasta `images/`.

Este projeto é uma base para desenvolvimento e estilização posterior — não contém um backend.

## Estrutura do projeto

```
ecommerce/
├─ index.html                 # Página principal
├─ README.md                  # Documentação do projeto (este arquivo)
├─ css/
│  ├─ reset.css               # Reset moderno (baseado em Andy Bell)
│  ├─ base.css                # Estilos base (tipografia, utilitários)
│  └─ components/
│     ├─ variables.css        # Variáveis CSS (cores, espaçamentos)
│     ├─ header.css           # Estilos do header
│     ├─ hero.css             # Estilos da seção hero
│     ├─ product-categoria.css# Estilos das categorias
│     ├─ product-grid.css     # Estilos do grid de produtos
│     └─ footer.css           # Estilos do footer
├─ images/                    # Assets: logos, ícones, produtos, banners
│  ├─ icons/
│  ├─ logo/
│  └─ products/
└─ .git/
```

## Como abrir o projeto localmente

1. Clone o repositório ou copie os arquivos para seu computador.
2. Abra `index.html` no seu navegador.

Opcional (com servidor local):

- Usando VS Code Live Server (recomendado): instale a extensão Live Server e clique em "Go Live".
- Usando Python 3: execute no terminal a partir da pasta do projeto:

```powershell
python -m http.server 3000
```

Em seguida acesse http://localhost:3000 no navegador.

## Convenções e boas práticas

- CSS modular por componente facilita manutenção e reuso.
- O `reset.css` é carregado primeiro para garantir uma base consistente.
- Utilize variáveis em `variables.css` para cores e espaçamentos.
- Prefira HTML semântico (`<header>`, `<main>`, `<nav>`, `<section>`, `<footer>`).
