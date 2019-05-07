# npm-area-triangulo-df
Módulo npm que tem como objetivo calcular a área de um triângulo. 
O módulo foi criado como exemplo para as aulas de Node.js

#instalação
Para instalar o módulo basta acessar a pasta de seu projeto e digitar npm install area-triangulo-df

#utilização
O código demonstra um exemplo de utilização

var calculaarea = require("area-triangulo-df");
var base = 0;
var altura = 0;
var area = 0;

console.log("Calcula a área de um triangulo");
base = parseFloat(readline.question("Base: "));
altura = parseFloat(readline.question("Altura: "));
//area = (base * altura) / 2;
area = calculaarea(base,altura);
console.log("A area do triangulo e: "+area);
