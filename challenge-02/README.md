# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
<<<<<<< HEAD
function soma(a, b){
=======
function somaArg(a, b){

>>>>>>> b30def1fdb2199c85e62149f99e019fa3113f18a
    return (a+b);
}

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
<<<<<<< HEAD
var inc = soma(2,3) + 5;
=======
var total = somaArg(2,3) + 5;
>>>>>>> b30def1fdb2199c85e62149f99e019fa3113f18a

// Qual o valor atualizado dessa variável?
10;

// Declare uma nova variável, sem valor.
<<<<<<< HEAD
var semValor;
=======
var qualquer;
>>>>>>> b30def1fdb2199c85e62149f99e019fa3113f18a

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
<<<<<<< HEAD
function addValor(parametro){
    semValor = parametro;
    return "O valor da variavel semValor agora é" + semValor;
=======
function retornaMsg(){
    qualquer = total;
     msg =  "O valor da variável agora é " + qualquer;
     return msg;
>>>>>>> b30def1fdb2199c85e62149f99e019fa3113f18a
}

// Invoque a função criada acima.
addValor(15);

// Qual o retorno da função? (Use comentários de bloco).
"O valor da variavel semValor agora é 15";

/* + semValor
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function verificaArgumentos(a, b, c){
if(a == undefined || b == undefined || c == undefined){
    return "Preencha todos os valores corretamente!";
}
resultado = a * b * c;
return resultado;

}

// Invoque a função criada acima, passando só dois números como argumento.
verificaArgumentos(3,4);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
nada;

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
verificaArgumentos(3,4, 2);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
24;

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/
function verificaArgumentos2(a, b, c){

if(a == undefined && b == undefined && c == undefined){
    return false;
}
if(a != undefined && b != undefined && c != undefined){
    return a + b + c;
}

return true;

}

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
verificaArgumentos2(1,2,3);
verificaArgumentos2(1,2);
verificaArgumentos2(2);
verificaArgumentos2();


