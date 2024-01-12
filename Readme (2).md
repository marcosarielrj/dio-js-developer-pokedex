# Trilha JS Developer - Pokedex


Variáveis JavaScript - 

Não é tipada - Converte automaticamente entre os tipos.
Com operador "+" concatena texto mais número, ou soma número com número. 
Com outros operadores tenta resolver se o texto for número e gera erro NaN(Not a Number) se o texto não for número.

Hosting 

Se chamar uma função antes e declarar depois funciona pois o JS auto organiza jogando a função pro inicio.
O mesmo não acontece com variáveis pois ele joga somente a declaração para o inicio e não a atribuição de valores.
Ex. 1
teste1() - chamar/executar a função antes funciona por ser uma função o JS joga a função para inicio quando executado.

function teste1(){
	console.log("Teste 1");
}

Ex. 2
teste2() - chamar antes NÃO funciona pois o JS joga pro inicio somente a declaração da variável e não a atribuição, a mesma ficara undefined.
var teste2 = function(){
	console.log("Teste 2);

Ex. 3
console.log(var1) - O resultado será undefined pois o JS joga apenas a declaração da variável para o inicio sem sua atribuição de valores. 
var1 = 10;
console.log(var1) - Chamar a variável após a atribuição retorna o valor atribuido no caso 10; 
