## 1.1 O que são estruturas de controle?
- Os programas são executados de cima para baixo;
- Com estas estruturas podemos alterar o fluxo de execução;
- O caminho dependerá das condições comparadas;
- As principais são if e else;

## 1.2 Estrutura condicional: if
- O if é muito utilizado na programação em geral;
- Temos um bloco de código sendo executado, se uma condição for verdadeira;
- A condição é validada por um boolean gerado após a execução do trecho de código no if;
#### Exemplo
```Javascript
const m = 10;

if(m > 5) {
	console.log("M é maior que 5!");
}

const user = "João"

if(user === "João") {
	console.log("Olá João!");
}

if(user === "Maria") {
	console.log("Olá Maria!")
}
```

## 1.3 Estrutura condicional: else
- O else executa quando o if não atende sua condição;
- Ou seja, não temos um bloco de validação, apenas do que será executado;
- A ideia é: Execute algo SE x > 5, SE NÃO, execute isso;
#### Exemplo
```Javascript
const loggedIn = false

if(loggedIn) {
	console.log("Está autenticado!")
} else {
	console.log("Não está autenticado!")
}
```

## 1.4 Estrutura condicional: else if
- O else if é uma estrutura intermediária de if e do else;
- É possível adicionar novas condições, como no if;
- Assim, temos a possibilidade de criar várias validações, para resolver nosso problema;
#### Exemplo
```Javascript
if(1 > 2) {
	console.log("Teste")
} else if(2 > 3) {
	console.log("Teste 2")
} else if(5 > 1) {
	console.log("Agora sim!")
}

const userName === "Matheus"
const userAge = 31

if(userName === "José") {
	console.log("Bem vindo, José!")
} else if(userName === "Matheus" && userAge === 31) {
	console.log("Olá Matheus, você tem 31 anos!")
} else {
	console.log("Nenhuma condição aceita!")
}
```

