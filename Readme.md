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