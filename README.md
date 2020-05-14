# PokéApp

## Índice

* [1. Introdução](#1-introducao)
* [2. PokéApp](#2-pokeapp)
* [3. Desenvolvimento](#3-desenvolvimento)
* [3.1 Protótipo de baixa fidelidade](#3.1-prototipo-de-baixa-fidelidade)
* [3.2 Pesquisa de usabilidade e definição de usuários](#3.2-pesquisa-de-usabilidade-definicao-de-usuarios)
* [3.3 Teste de usabilidade](#3.3-teste-de-usabilidade)
* [3.4 Refatoração](#3.4-refatoracao)
* [4. Considerações técnicas](#4-consideracoes-tecnicas)

***

## 1. Introdução
O presente projeto foi realizado em duplas, com o objetivo de desenvolver uma página web que permitia vizualizar e manipular dados, fornecendo algumas funcionalidades de acordo com as necessidades e histórias do usuário.
O banco de dados escolhido foi o do Pokémon.

***

## 2. PokéApp
O PokéApp foi criado a partir de uma frustração dos usuários com páginas que possuem muita informação e que não são fáceis de localizar o que se procura. Com isso, tivemos o intuito de fornecer aos visitantes uma experiência agradável, onde tudo pode ser localizado com objetividade e clareza. A plataforma permite você descobrir o mundo Pokémon e explorar cada um deles e suas peculiaridades.
***

## 3. Desenvolvimento
As tecnologias utilizadas nesse projeto foram:
* CSS
* HTML
* ES6
* Jest


**Arquivos**
* `src/index.html` Primeira página exibida ao usuario contendo todos os pokemons e filtros.
* `src/sobre.html` Página para informar ao usuário sobre o projeto.
* `src/curiosidades.html` página contendo as curiosidades do universo Pokémon.
* `src/main.js` contém os códigos relacionados a manipulação do DOM.
* `src/data.js` contém as funções puras utilizadas na manipulação do DOM.
* `src/style.css` estilização da página.
* `test/data.spec.js` contém os teste unitários das funções implementadas no arquivo data.js.

***

## 3.1 Protótipo de baixa fidelidade
Inicialmente, foi feito um protótipo de baixa fidelidade do site, no qual foram propostas a principal(home) e mais duas páginas adicionais, a sobre e a de curiosidades.
***

## 3.2 Definição dos usuários e testes de usabilidade
Para definir os usuário, elaboramos uma pesquisa no forms do google e após obter os dados dispostos, chegamos em duas personas e a partir delas elaboramos nossas histórias de usuário.

### Personas:

#### **Plínio** tem 22 anos,trabalha com administração e seu hobby é jogar videogames.
**o que ele precisa:** 
* conhecer os poderes dos pokémons, pois precisa dessa informação para poder usar em suas batalhas.
* conhecer os tipos dos pokémons para saber qual seria ideal para usar em suas batalhas
###

#### Paulo tem 10 anos,estuda no fundamental e seu hobby é assistir animes.
**o que ele precisa:**

*  precisa das características principais de cada pokémon porque irá responder um teste para entrar em uma comunidade no facebook que deseja fazer parte

* O amigo de paulo está curioso sobre pokemons, paulo quer indicar uma plataforma para que ele possa encontrar o que deseja

 ###
Foram desenvolvidos testes unitários para identificar falhas em nossas funções e testes de usabilidade com alguns voluntários. Após realizado, foram propostos alguns ajustes mediante a página home e a disposição de alguns elementos.  Estes foram corrigidos e apresentados novamente, recebendo uma maior aprovação, possibilitando a melhoria de experiência do usuário.
***

## 3.4 Refatoração

***

## 4. Considerações Técnicas
:warning: Para usá-lo, você precisa instalar o node.js – visto que, eles são empacotados juntos.  :warning:

Os comandos necessários para executar o programa em sua máquina são:

* npm install - este irá auxiliar na instalação do projeto, no gerenciamento da versões e no gerenciamento de dependências necessárias para executa-lo.

* npm start -  executa os scripts que estiverem localizados no arquivo package.json, no caso o **"start"**, devolvendo assim o arquivo do servidor.

* npm test - procura pelo script  **test** dentro do package.json, executar o que estiver dentro dele e mostrar se os testes passaram ou não.

* npm deploy - publica uma versão do seu projeto no GitHub Pages.