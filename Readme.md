# FUNDAMENTOS DO JAVASCRIPT CLÁSSICO

## INTEGRAÇÕES 

### Integrar JavaScript de forma interna

~~~ HTML
./index.html

<!DOCTYPE html>

<html lang="PT-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>
    <script>
        console.log("hello world!");
    </script>
</head>
<body></body>
</html>
~~~

### Integrar JavaScript de forma interna
***
- Criar diretório ***SRC*** na raiz do projeto
- Criar arquivo ***script.js*** na raiz do diretório ***SRC***
- Integrar de forma externa o arquivo ***script.js*** no arquvio ***index.html***

~~~ HTML
./index.html

<!DOCTYPE html>

<html lang="PT-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>
    <script src="./scr/script.js"></script>
</head>
<body></body>
</html>
~~~

## Comentários 

### Comentario de linha

~~~ JavaScript
./src/script.js
// Cometário de linha

~~~

### Comentario de bloco simples

~~~ JavaScript
./src/script.js
/* Cometário de bloco simples */

~~~

### Comentario de bloco com marcadores

~~~ JavaScript
./src/script.js
/**
 *  Cometário de bloco com marcadores
*/

~~~

## VARIÁVEIS

### Declaração

~~~ JavaScript
./src/script.js
var number;
~~~

### Atribuição de valor

~~~ JavaScript
./src/script.js

var number;
number = 2;
~~~

### Declaração e atribuição de valor

~~~ JavaScript
./src/script.js

var number = 2;
~~~

### Reatribuição de valor

~~~ JavaScript
./src/script.js

var number = 2;

number = 8
~~~

### Nomenclaturas

- Caracteres permitidos para iniciar a nomenclatura de um identificador

~~~JavaScript
./src/script.js

// letras
var number;
var Number;

//sublinhado
var _number

//cifrão
var $number;

~~~

- Case-senstive
~~~JavaScript
./src/script.js

// "number" é diferente de "Number"
~~~

- Nomenclaturas Compostas

~~~JavaScript
./src/script.js

// camelCase
var myName

//PascalCase
var MyName;

// snake_case
var my_name;
~~~

## TIPOS DE DADOS

### Primitivos

~~~JavaScript
./src/script.js

// String
var name = "Alex"; // Aspas Composta
var surname = 'Bessa'; // Aspas Simples

// Number
var age = 28;
var weight = 85.6;

//boolean
var active = true;
var permission = false;

// Undefined
var contains;
console.log(contains);

// Null
var data = null;

~~~

### Não primitivos

~~~ javascript
./src/script.js

// array
var values = [1, "José", true, null];

// object literal
var person = {name:"João", age: 34};

var person = {
    name: "Joseph",
    age: 40
};

~~~ 