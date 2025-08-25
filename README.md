# Desafio: Construindo um Card de Notícia Responsivo

Bem-vindos ao desafio prático do nosso webinar!

Neste projeto, você terá a oportunidade de aplicar os conceitos de **Fonts Personalizadas**, **Design Responsivo**, **Unidades Relativas** e **Media Queries** para construir um componente de interface de usuário real e funcional.

---

### 🎯 **Objetivo**

O seu objetivo é transformar o código-base fornecido em um **Card de Notícia responsivo**, que se adapte perfeitamente a telas de desktops, tablets e celulares, utilizando uma abordagem de **três níveis de responsividade**.

---

### 🚀 **Tarefas**

Siga os passos abaixo para completar o desafio.

1.  **Adicionar uma Fonte Personalizada (`fonts.css`)**
    * Escolha e baixe uma fonte de sua preferência (ex: [Google Fonts](https://fonts.google.com/)).
    * No arquivo `fonts.css`, adicione a regra `@font-face` para importar a fonte para o projeto.
    * Aplique a nova fonte ao `body` no arquivo `style.css` para que ela seja usada em toda a página.

2.  **Estilizar o Card (`style.css`)**
    * Crie a estilização para a **versão desktop** do card. Você pode utilizar pixel mas procure utilizar unidades relativas (`%` e `vw`) para praticar.
    * Para as a propriedade `font-size` utilize pixels. A principal meta é fazer o layout principal se adaptar.
    * Utilize a metodologia **BEM** (Bloco, Elemento, Modificador) para nomear suas classes, como `.card`, `.card__title`, `.card__button`, etc.

3.  **Tornar o Card Responsivo (`style.css`)**
    * Agora, vamos criar as regras para telas menores. Você fará dois pontos de corte.
    * **Nível 1 (Tablets):** Crie uma `media query` com a condição `@media (max-width: 768px)`. Dentro dela, adicione regras de CSS que ajustem o layout do card para tablets.
    * **Nível 2 (Celulares):** Crie uma segunda `media query` com a condição `@media (max-width: 480px)`. Dentro dela, o desafio é fazer com que a imagem do card **desapareça** completamente.

---

### 📁 **Arquivos do Projeto**

Você encontrará os seguintes arquivos no repositório:

-   `index.html`: A estrutura HTML base do card.
-   `vendor/fonts.css`: Arquivo onde você irá adicionar a regra `@font-face`.
-   `vendor/fonts/`: Pasta onde você deve armazenar os arquivos de fonte.
-   `style.css`: Arquivo onde você irá adicionar os estilos para o desafio

---

### ✨ **Dica Extra**

Lembre-se da abordagem **desktop-first**. Os estilos que você criar fora da `media query` são o padrão para telas grandes. As `media queries` servem apenas para adicionar ou modificar regras específicas para telas menores.

---

### 🎉 **Vamos começar!**

Clone ou baixe este repositório para a sua máquina e abra os arquivos no VSCode.

Boa sorte e divirtam-se!
