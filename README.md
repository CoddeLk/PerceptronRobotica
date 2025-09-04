Perceptron: Página de Produto de Robô Doméstico
Este projeto é uma página de produto estática e simples para um robô doméstico fictício chamado "Perceptron". A página foi projetada para exibir o robô com uma imagem, um preço e uma breve descrição, juntamente com um botão "Comprar".

<img src="./Imagens/robot.png" alt="Captura de tela da página do produto Perceptron">
***

Tecnologias Utilizadas
HTML5: Para a estrutura e o conteúdo da página.

CSS3: Para a estilização do layout, cores e fontes.

Ótimo! O CSS que você forneceu cria um layout mais dinâmico usando Grid e estilos mais específicos. Ele deixa a página com uma aparência mais profissional e moderna.

Para o README ficar completo, vou atualizar a seção de Código com o novo CSS.

Perceptron: Página de Produto de Robô Doméstico
Este projeto é uma página de produto estática e simples para um robô doméstico fictício chamado "Perceptron". A página foi projetada para exibir o robô com uma imagem, um preço e uma breve descrição, juntamente com um botão "Comprar".

<img src="./Imagens/robot.png" alt="Captura de tela da página do produto Perceptron">

Tecnologias Utilizadas
HTML5: Para a estrutura e o conteúdo da página.

CSS3: Para a estilização do layout, cores e fontes.

Como Executar
Para visualizar este projeto, siga os seguintes passos:

1. Clone o repositório:

Bash

git clone https://github.com/seu-usuario/seu-nome-do-repositorio.git

2. Navegue até o diretório do projeto:

Bash

cd seu-nome-do-repositorio

3. Abra o arquivo index.html:

Abra o arquivo index.html no seu navegador web de preferência (por exemplo, Chrome, Firefox, Safari).

CÓDIGO


HTML
body {
    font-family: Georgia, "Times New Roman", Times, serif;
    margin: 0;
    padding: 20px;
    background-color: #f0f0f0;
}

h1 {
    font-size: 3em;
    text-align: center;
}

.container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    max-width: 960px; /* Adicionado para limitar a largura */
    margin: auto; /* Centraliza o container na página */
}

.imagemProduto {
    width: 100%;
    height: auto;
    display: block;
}

.preco {
    background-color: #e9e9e9;
    padding: 5px 10px;
    border-radius: 5px;
    display: inline-block;
    font-weight: bolder;
    margin-bottom: 10px;
}

.botaoComprar {
    background-color: #a052ff;
    color: #ffffff;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 20px;
}

CSS

body {
    font-family: Georgia, "Times New Roman", Times, serif;
    margin: 0;
    padding: 20px;
    background-color: #f0f0f0;
}

h1 {
    font-size: 3em;
    text-align: center;
}

.container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    max-width: 960px; /* Adicionado para limitar a largura */
    margin: auto; /* Centraliza o container na página */
}

.imagemProduto {
    width: 100%;
    height: auto;
    display: block;
}

.preco {
    background-color: #e9e9e9;
    padding: 5px 10px;
    border-radius: 5px;
    display: inline-block;
    font-weight: bolder;
    margin-bottom: 10px;
}

.botaoComprar {
    background-color: #a052ff;
    color: #ffffff;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 20px;
}

