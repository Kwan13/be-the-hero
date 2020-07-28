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

1º - Instalar dependencias: 

Utilizando o terminal/console vá até a raiz da basta "backend" e digite o comando:
```
npm install
```
<br>
2º - Iniciar servidor:
Ainda no diretório "backend" utilizando o terminal digite:

```
npm start
```

<br>
3º - Rotas:

Rotas|Tipo|Descrição
:---: | :---: | :--- |
/ongs|GET|Lista todas as ONGS cadastradas no banco de dados.
/ongs|POST| Adiciona o cadastro de uma nova ONG no banco de dados.
/incidents|GET|Lista todos os "casos" registrados juntamente com os dados da ONG que criou.
/incidents|POST|Adiciona um novo "caso" no banco de dados.
/incidents/:id|DELETE|Exclui um "caso" de uma ONG especifica.

_**Front-end:**_

Instalando dependencias:
1º - Acesse o diretório "frontend" via terminal e digite o comando:
```
npm install
```
<br>

2º - Para iniciar o frontend digite:
```
npm start
```

