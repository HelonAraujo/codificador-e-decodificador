# Codificador e Decodificador de texto

# Utilizando HTML, CSS e JavaScript

Este é o meu primeiro _challenge_ desenvolvido durante o programa **ONE - Oracle Next Education**, com o objetivo de colocar em prática os conteúdos estudados. O desafio consiste em criar um **codificador/decodificador** de texto utilizando conhecimentos em **HTML**, **CSS** e **JavaScript** adquiridos durante as aulas.
Foram disponibilizados _cards_ no _Trello_ para orientar e gerenciar o desenvolvimento do projeto e um modelo proposto de estilização no _Figma_.

# Meu projeto

Busco manter meu código sempre organizado, para facilitar a compreensão e o acesso, caso algo precise ser alterado.

# Na estrutura HTML modifiquei:

- o ícone, o título e a descrição da página;
- o _header_, onde coloquei o _link_ da página no logo. Assim, ao clicar no logo, a página é recarregada (eu geralmente faço isso pois acho uma funcionalidade interessante);
- o aviso de "apenas letras minúsculas e sem acento" para aparecer somente se o usuário digitar letras maiúsculas ou acentuadas;
- a _textarea_ que mostra o resultado da codificação/decodificação para _readonly_, pois caso o usuário digitasse algo algo nela (com ou sem intenção) e depois tentasse fazer a codificação/decodificação, o texto não era mostrado;
- o _footer_, onde adicionei meu nome e redes sociais;

# No CSS modifiquei:

- A fonte para _"Montserrat light 300"_, seu tamanho e o espaçamento das linhas;
- As cores do fundo (com um gradiente de azul-claro para azul-escuro) e das sombras;
- As animações dos _links_ e dos botões (usei _transform_ e _opacity_);
- O ponto de exclamação antes das mensagens de erro (_::before_) e a imagem de fundo da _textarea_ quando não há texto inserido (_:placeholder-shown_);
- O _layout_ da página para dispositivos móveis;

# No JavaScript:

- Criei a função de codificar separando os caracteres do texto em um _array_ (_texto.value.split_), substituindo com _forEach_ e retornando com _.join("")_;
- Criei a função de decodificar utilizando um _array_ com a "chave" da codificação e utilizando _replaceAll(chave[i][1])_;
- Criei uma função para validar o texto inserido, permitindo apenas letras minúsculas e sem acento;
- Criei uma função para mostrar uma mensagem de erro caso não fosse inserido texto;
- Criei uma função para que, ao copiar o texto codificado/decodificado usando o botão "copiar", as _textareas_ sejam limpas e o input seja focado, para que o usuário não precise novamente clicar no input e apagar o texto previamente digitado para colar outro texto.

**ASS**: Helon R Araujo
