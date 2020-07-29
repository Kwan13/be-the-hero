
# Be The Hero
![enter image description here](https://i.imgur.com/VMsxkfk.png)
## Sobre
Be The Hero é uma aplicação que permite o encontro de ONG`S que precisam de ajuda com pessoas que estão dispostas a ajudar, basta a ONG descrever a situação, informar quantia necessária para solucionar o caso e esperar por um hero!

### Tecnologias utilizadas:

[<img src="https://cdn.iconscout.com/icon/free/png-512/react-1-282599.png" width="18"/>](https://pt-br.reactjs.org/)  -  *React*.<br/>
[<img src="https://cdn.iconscout.com/icon/free/png-512/react-1-282599.png" width="18"/>](https://reactnative.dev/) - *React Native*.<br/>
[<img src="https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg" width="18"/>](https://nodejs.org/en/) - *NodeJS*.<br/>


### Instruções
_**Backend:**_

1. Instalar dependencias: 

	Utilizando o terminal/console vá até a raiz da basta "backend" e digite o comando:
	```
	npm install
	```
	<br>
2.  Iniciar servidor:
	Ainda no diretório "backend" utilizando o terminal digite:
	```
	npm start
	```
	<br>
3. Rotas:

	Rotas|Tipo|Descrição
	|:---: | :---: | :--- |
	|/ongs|GET|Lista todas as ONGS cadastradas no banco de dados.|
	|/ongs|POST| Adiciona o cadastro de uma nova ONG no banco de dados.|
	|/incidents|GET|Lista todos os "casos" registrados juntamente com os dados da ONG que criou.|
	|/incidents|POST|Adiciona um novo "caso" no banco de dados.|
	|/incidents/:id|DELETE|Exclui um "caso" de uma ONG especifica.|
	<hr>

_**Front-end:**_

Instalando dependencias:
1. Acesse o diretório "frontend" via terminal e digite o comando:
	```
	npm install
	```
	<br>

2. Para iniciar o frontend digite:
	```
	npm start
	```
<hr>

_**Mobile:**_


Antes de qualquer coisa em seu Smartphone acesse a loja de apps e baixe o app __*Expo*__ - [<img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg" width="18">](https://apps.apple.com/br/app/expo-client/id982107779) | [<img src="https://image.flaticon.com/icons/png/512/226/226770.png" width="19">](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt_BR)

1. No computador abra o diretório "mobile" e digite o comando:
	```
	npm intall
	```
	Após o download das dependências digite no terminal:
	```
	npm start
	```
	isso abrirá uma página em seu navegador com um QR Code.
	<br>
	
2. Abra o app Expo que você baixou anteriormente e escaneie o QR Code presente em seu navegador.
