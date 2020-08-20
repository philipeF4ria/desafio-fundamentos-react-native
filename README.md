# Desafio Fundamentos React Native

![68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732d6e65772e706e67](https://user-images.githubusercontent.com/60238162/90712557-b099a180-e279-11ea-8f9d-078bde095632.png)

## :rocket: Sobre o desafio ##
Nesse desafio, foi desenvolvida uma nova aplicação, a GoMarketplace. Dessa vez para praticar o que  foi aprendido <br />
até agora no React Native junto com o TypeScript, utilizando rotas, Async Storage e a Context API.

## :iphone: Sobre a aplicação ##
Esta aplicação consiste em uma loja virtual. <br />

![Screenshot01RED](https://user-images.githubusercontent.com/60238162/90713440-b6908200-e27b-11ea-866e-1f00adcac43f.png)
> Dashboard do aplicativo

## :computer: Tecnologias utilizadas ##

Typescript :white_check_mark: <br />
React Native :white_check_mark: <br />
Styled Components :white_check_mark: <br />
Axios :white_check_mark: <br />

## :wrench: Como funciona ##
A aplicação utiliza o Axios para consumir uma fake API que fornece os dados de cada produto. <br />
Quando os produtos são carregados em tela, o usuário poderá escolher todos que quiser e <br />
adicioná-los ao carrinho. Através do Context API, do React, os dados são mantidos <br />
tanto no dashboard do usuário, quanto em seu carrinho.

![Screenshot02RED](https://user-images.githubusercontent.com/60238162/90713801-7e3d7380-e27c-11ea-8497-0ba39f5fca96.png)
> Carrinho com os produtos escolhidos

## :construction_worker: Como utilizar ##

Para utilizar esta aplicação em sua máquina, basta seguir os passos abaixo:
1) Clonar este repositório. <br />
2) No diretório raiz, rodar o comando `yarn` para instalar as depenências. <br />
3) Dar o comando `yarn json-server server.json -p 3333` para inicializar a fake API. <br />
4) Por fim, basta inicializar o dispositivo móvel (virtual ou físico) e dar o comando `yarn android` ou `yarn ios`. <br />
