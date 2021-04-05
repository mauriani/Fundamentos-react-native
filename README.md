<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 08: Fundamentos do React Native
</h3>

## :rocket: Sobre o desafio

Nesse desafio foi desenvolvido uma aplicação GoMarketplace. O intuito do projeto é aprender os conceitos como contextApi, uso de hooks, typescript com react native etc.

### Utilizando uma fake API

Nesse projeto vamos consumir uma api fake, o **json-server.**

Caso esteja usando um emulador físico basta rodar o server com o seguinte comando:

```tsx
json-server --host 192.168.xx.xx server.json --port 3333
```

Se o seu caso for diferente basta rodar com o comando abaixo:

```
  yarn json-server server.json -p 3333

```

### Funcionalidades da aplicação

- [x]  **`Listar os produtos da fake API`**
- [x]  **`Adicionar itens ao carrinho`**
- [x]  **`Exibir itens do carrinho`**
- [x]  **`Aumentar quantidade de itens do carrinho`**
- [x]  **`Diminuir quantidade de um item do carrinho`**
- [x]  **`Exibir valor total dos itens no carrinho`**

### Clonando o projeto

```
 # clonar o repositório
 $ https://github.com/mauriani/Fundamentos-react-native.git

 # acessar a pasta do projeto
 $ cd Fundamentos-react-native

 # instalar as dependências do projeto
 $ yarn or npm install

```

### Start na aplicação

Para dá start basta rodar o comando abaixo na pasta da aplicação, lembre-se também de rodar o **JSON Server.**

```
yarn android

```
