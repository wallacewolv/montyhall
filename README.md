# montyhall
Jogo de Monty Hall(Multiplas portas)

Projeto desenvolvido com Vue.js, um jogo de raciocinio e sorte.

Suponha que você esteja participando de um jogo com três portas e que atrás de uma delas tenha um carro como prêmio. O apresentador do jogo pede a você que escolha uma porta. Se você escolher a porta que tem o carro, você ganha o carro.

Entretanto, após você escolher sua porta, o apresentador abre uma outra porta do jogo e mostra que aquela porta está vazia. Atrás dela não está o prêmio. O apresentador, então, pergunta: “Você quer mudar de porta?”. Há apenas duas portas sobrando, aquela que você escolheu primeiro e aquela que não foi aberta.

Você mudaria de porta? Qual a probabilidade de você ganhar o prêmio, se mudar de porta?

Em geral, as pessoas acham que é 50%. Afinal, ou o prêmio está na porta que você escolheu, ou está na outra porta que sobrou. Mas essa resposta não é correta.

A forma mais fácil de visualizar isso é a seguinte. Vamos nomear as portas de “porta premiada”, “porta não premiada 1” e “porta não premiada 2”. Ao escolher a sua porta, você tinha 1/3 de probabilidade de escolher cada uma delas.

Se você escolher a “porta premiada” e mudar, você perde. Este evento tem probabilidade de 1/3.

Se você escolher a “porta não premiada 1”, o apresentador irá abrir a “porta não premiada 2”, restando unicamente a “porta premiada”. Então se você mudar, você ganha. Este evento tem probabilidade de 1/3

O mesmo raciocínio acima vale para caso você escolha a “porta não premiada 2”. E, novamente, este evento tem probabilidade 1/3.

Logo, a probabilidade de você ganhar caso mude de porta é 1/3+1/3=2/3=66,66%.

## Project setup
```
Após o git clone em sua maquina insira o comando yarn install ou npm i no prompt dentro do repositorio para baixar as dependências
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
