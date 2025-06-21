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
