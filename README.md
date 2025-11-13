# 🪐 Projeto BT21 - Website Institucional

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen) ![Contexto](https://img.shields.io/badge/Contexto-Acadêmico-blue)

## 📝 Descrição

Este projeto é um website front-end desenvolvido como um **trabalho universitário**. O tema escolhido foi o **Universo BT21!!**

O objetivo do projeto foi colocar em prática conceitos fundamentais de desenvolvimento web, focando na estruturação de páginas, estilização e navegação entre múltiplas telas.

## 🚀 Funcionalidades

O site é composto por 5 páginas principais, cada uma com um propósito específico:

* **Landing Page (Início):** Apresentação visual impactante com o slogan "A new universe, a new story".
* **Galeria de Personagens (Home):** Uma grade detalhada apresentando cada personagem (Chimmy, Cooky, Tata, etc.) com suas respectivas descrições e características.
* **Sobre (About):** Texto informativo explicando a história da marca, a parceria "Friends Creators" e a expansão global do IP.
* **Mídia (Start):** Uma seção contendo vídeos incorporados (iFrames) do YouTube relacionados ao projeto.
* **Votação (Choose Your Favorite):** Um formulário interativo onde o usuário pode selecionar seu personagem favorito e receber uma mensagem de agradecimento (lógica via JavaScript simples).

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica das páginas (`header`, `section`, `footer`, `nav`).
* **CSS3:**
    * Layouts responsivos utilizando **Flexbox**.
    * Estilização de formulários e tabelas.
    * Uso de gradientes e posicionamento absoluto/relativo.
    * Importação de fontes personalizadas.
* **JavaScript:** Lógica básica para manipulação do DOM no envio do formulário de votação (interatividade sem recarregar a página).

## 📂 Estrutura de Arquivos

O projeto está organizado da seguinte forma:

```text
/
├── index.html       # Página Inicial (Capa)
├── index2.html      # Lista de Personagens
├── index3.html      # Sobre o Projeto (História)
├── index4.html      # Página de Vídeos
├── index5.html      # Formulário de Votação
├── css/
│   ├── style.css    # Estilos da index.html
│   ├── style2.css   # Estilos da index2.html
│   ├── style3.css   # Estilos da index3.html
│   ├── style4.css   # Estilos da index4.html
│   └── style5.css   # Estilos da index5.html
└── img/             # Imagens e logotipos (logo.png, personagens, etc.)
