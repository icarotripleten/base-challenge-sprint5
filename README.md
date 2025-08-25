Desafio: Construindo um Card de Notícia Responsivo
Bem-vindos ao desafio prático do nosso webinar!

Neste projeto, você terá a oportunidade de aplicar os conceitos de Design Responsivo, Unidades Relativas e Media Queries para construir um componente de interface de usuário real e funcional.

🎯 Objetivo
O seu objetivo é transformar o código-base fornecido em um Card de Notícia responsivo, que se adapte perfeitamente a telas de desktops, tablets e celulares.

🚀 Tarefas
Siga os passos abaixo para completar o desafio.

Adicionar uma Fonte Personalizada (fonts.css)

Escolha e baixe uma fonte de sua preferência (ex: Google Fonts).

No arquivo fonts.css, adicione a regra @font-face para importar a fonte para o projeto.

Aplique a nova fonte ao body no arquivo style.css para que ela seja usada em toda a página.

Estilizar com Unidades Relativas (style.css)

Crie a estilização para a versão desktop do card. Use unidades relativas (% e vw) para definir as dimensões e o espaçamento, garantindo que o layout seja flexível.

Utilize a metodologia BEM (Bloco, Elemento, Modificador) para nomear suas classes, como .card, .card__title, .card__button, etc.

Tornar o Card Responsivo (style.css)

Agora, vamos criar a versão para telas menores usando uma media query.

Recorte: Crie uma media query com a condição @media (max-width: 768px).

Ações: Dentro deste bloco, adicione regras de CSS que ajustem o layout do card para tablets e celulares. Recomendamos:

Mudar a direção do flexbox do .card para column.

Ajustar a largura do .card para ocupar mais espaço na tela.

Fazer a imagem (.card__image) ocupar 100% da largura do contêiner.

📁 Arquivos do Projeto
Você encontrará os seguintes arquivos no repositório:

index.html: A estrutura HTML base do card.

fonts.css: Arquivo onde você irá adicionar a regra @font-face.

style.css: Arquivo onde você irá adicionar os estilos para o desafio.

✨ Dica Extra
Lembre-se da abordagem desktop-first. Os estilos que você criar fora da media query são o padrão para telas grandes. A media query serve apenas para adicionar ou modificar regras específicas para telas menores.

🎉 Vamos começar!
Clone ou baixe este repositório para a sua máquina e abra os arquivos no seu editor de código preferido.

Boa sorte e divirtam-se!