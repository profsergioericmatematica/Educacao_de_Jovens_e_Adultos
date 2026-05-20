# Super Resumo EJA — Material de Estudo

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat&logo=github&logoColor=white)](https://pages.github.com/)
[![Licença MIT](https://img.shields.io/badge/Licença-MIT-green.svg)](LICENSE)

Página web moderna, responsiva e interativa para disponibilizar materiais de estudo da **Educação de Jovens e Adultos (EJA)**. Baixe o PDF completo com teoria e questões, além de dois ÁudioCasts narrados que cobrem desde os fundamentos de Paulo Freire até metodologias ativas, avaliação e inclusão.

---

## ✨ Funcionalidades

- **Design Glassmorphism:** Interface translúcida com blur, gradientes escuros animados e partículas flutuantes.
- **Nuvem de palavras‑chave:** Mapa mental visual ao fundo com termos da EJA em diversas cores, tamanhos e orientações.
- **3 Cards de Download:** PDF, ÁudioCast – Fundamentos e ÁudioCast – Práticas, todos com `download` nativo.
- **Gradientes e Glows Temáticos:** Cada card possui cores e sombras próprias (vermelho, roxo, ciano).
- **Totalmente Responsivo:** Testado em desktops, tablets e smartphones (Flexbox + media queries).
- **Pronto para GitHub Pages:** Sem dependências de back‑end. Basta ativar o Pages no repositório.

---

## 📂 Estrutura de Arquivos

Educacao_de_Jovens_e_Adultos/
├── index.html ← Site completo (HTML + CSS + palavras-chave)
├── LICENSE ← Licença MIT
├── README.md ← Este arquivo
└── arquivos/
├── resumo.pdf ← Apostila essencial (Semanas 1 a 8 + Questões)
├── audio-parte1.m4a ← ÁudioCast – Fundamentos (Semanas 1 a 4)
└── audio-parte2.m4a ← ÁudioCast – Práticas (Semanas 5 a 8)

---

## 🛠️ Como testar localmente

1. **Clone o repositório** ou baixe o ZIP.
2. Certifique‑se de que a pasta `arquivos/` está no mesmo nível de `index.html`.
3. Para evitar problemas com CORS ao testar via `file://`, use uma das opções:
   - **Live Server** no VS Code.
   - Servidor local Python: `python -m http.server 8000`.
4. Acesse `http://localhost:8000` no navegador.

---

## 🚀 Publicação no GitHub Pages

1. Faça o push do repositório para o GitHub.
2. Acesse **Settings > Pages**.
3. Em *Source*, escolha `Deploy from a branch` e selecione a branch `main` (ou `master`).
4. Clique em **Save**. Em poucos minutos, o site estará disponível em:

https://profsergioericmatematica.github.io/Educacao_de_Jovens_e_Adultos/
---

## 🎨 Paleta de Design

| Cor               | Uso                          | Código     |
|-------------------|------------------------------|------------|
| Roxo escuro       | Fundo animado                | `#0f0c29`  |
| Azul meia‑noite   | Fundo animado                | `#302b63`  |
| Vermelho vibrante | Card PDF, ícone, glow        | `#ff4757`  |
| Roxo intenso      | Card Áudio 1, ícone, glow    | `#7c5cfc`  |
| Ciano             | Card Áudio 2, ícone, glow    | `#00d2d3`  |
| Rosa Instagram    | Link de autoria              | `#e1306c`  |

---

## 👨‍🏫 Autor

Desenvolvido por **Sergio Eric**  
📸 [@prof.sergio.eric.matematica](https://www.instagram.com/prof.sergio.eric.matematica/)

---

## 📄 Licença

Este projeto está licenciado sob os termos da licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.