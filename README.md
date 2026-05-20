# 🎓 Super Resumo EJA | Portal de Materiais de Estudo

Bem-vindo ao repositório do **Portal de Materiais de Estudo - EJA**. Este projeto é uma *Landing Page* interativa, moderna e responsiva, desenvolvida para facilitar o acesso e o download seguro de materiais de revisão focados na disciplina de Educação de Jovens e Adultos (EJA).

O site foi construído com foco na experiência do usuário (UX), aliando um design arrojado a uma solução técnica eficiente para forçar o download de arquivos diretamente pelo navegador.

## 🚀 Tecnologias e Funcionalidades

O projeto foi desenvolvido utilizando **HTML5, CSS3 e JavaScript puro (Vanilla)**, embarcando as seguintes características:

* **Design Glassmorphism:** Interface baseada em cartões translúcidos com desfoque de fundo (backdrop-filter), proporcionando um visual limpo e moderno.
* **Fundo Animado & Nuvem de Palavras:** Fundo com gradiente dinâmico, partículas flutuantes e uma nuvem de palavras-chave da EJA (como *Paulo Freire, Andragogia, Letramento, Consciência Crítica, Funções Executivas*), animadas via CSS para enriquecer a imersão.
* **Download Forçado Seguro (JS):** O script integrado utiliza a `Fetch API` e converte a resposta em um `Blob`, forçando o navegador a baixar os arquivos PDF e M4A, contornando o comportamento padrão de apenas abrir os arquivos em novas abas.
* **Totalmente Responsivo:** Layout adaptável para smartphones, tablets e desktops (Mobile First).

## 📚 Conteúdo Disponibilizado

O portal organiza os recursos em cartões de download rápido:

1. 📄 **Apostila Essencial (PDF):** Super resumo completo cobrindo as Semanas 1 a 8, teorias aprofundadas e 25 questões compiladas e gabaritadas.
2. 🎧 **ÁudioCast - Episódio 1 (M4A):** Áudio de apoio focado em Fundamentos Históricos, Legislação e o Método Paulo Freire.
3. 🎙️ **ÁudioCast - Episódio 2 (M4A):** Áudio de apoio focado em Currículo, Neurociência, Inclusão e Práticas Pedagógicas modernas.

## 📂 Estrutura do Repositório

/
├── index.html               # Arquivo principal contendo a estrutura, estilos (CSS) e lógica (JS)
├── arquivos/                # Diretório para armazenar os arquivos de download
│   ├── resumo.pdf           # O PDF do super resumo
│   ├── audio-parte1.m4a     # O primeiro áudio
│   └── audio-parte2.m4a     # O segundo áudio
└── README.md                # Documentação do projeto

*Nota: Para que o download funcione perfeitamente, os arquivos devem estar dentro da pasta "arquivos" com os nomes exatos indicados no código.*

## 🛠️ Como Utilizar ou Clonar

Se você deseja usar este projeto como base para distribuir seus próprios materiais:

1. Faça o clone do repositório:
   git clone https://github.com/profsergioericmatematica/Educacao_de_Jovens_e_Adultos.git

2. Crie a pasta `arquivos/` na raiz do projeto e insira os seus materiais dentro dela.
3. Edite o arquivo `index.html` alterando os links, títulos e o atributo `data-filename` para refletir os seus novos arquivos.
4. Hospede gratuitamente no **GitHub Pages** (basta ativar nas configurações do seu repositório).

## 👨‍🏫 Autoria

Desenvolvido e estruturado pelo **Prof. Sergio Eric**. 

Conecte-se e acompanhe mais projetos sobre tecnologia educacional, metodologias ativas e o ensino da Matemática:
👉 **[Instagram: @prof.sergio.eric.matematica](https://www.instagram.com/prof.sergio.eric.matematica/)**
