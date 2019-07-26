# Como executar Javascript

Existem algumas formas, vou apresentar quatro maneiras:

- A forma mais prática de executar Javascript, é utilizando o **Node**. 

Se você usa o Windows, baixe o instalador no site: https://nodejs.org/en/download/

Caso você use Linux, pode instalar o Node seguindo esse tutorial: https://github.com/nodesource/distributions/blob/master/README.md#debinstall

Se usa alguma versão de Linux que não seja Ubuntu ou Debian-based, procure a versão adequada pro seu sistema no site: https://nodejs.org/en/download/

Caso não consiga instalar seguindo os links acima, vejam esse link: https://github.com/backend-br/como-instalar-xyz#linguagens

Após instalar o node, crie um arquivo chamado `hello.js` em qualquer diretório, nesse arquivo, escreva o seguinte:

```
console.log("ola mundo");
```

Salve o arquivo, abra seu terminal e vá até o diretório onde o arquivo está salvo, e então digite `node hello.js`. Pronto, você executou seu primeiro código Javascript na sua maquina :)

Para praticar, você pode criar vários arquivos, com o nome que desejar. E para executar o arquivo, basta escrever no terminal `node nomeDoArquivo.js`.

- Criando um arquivo HTML e usando a tag `<script> </script>`

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <script>
        console.log('Ola mundo :)'); // imprime 'Ola mundo :)' no console
    </script>
</body>
</html>
```

Tudo que estiver dentro das tag `<script> </script>` será executado como *código javascript*, portanto, basta abrir esse código html no seu navegador, que você pode visualizar a **saída** do seu código javascript no **console** do navegador.

- Criando um arquivo HTML e um arquivo com a extensão `.js` na mesma pasta

É possível referenciar um arquivo *javascript* dentro do HTML, com a tag `<script> </script>`, basta usar o atributo `src`.

Criando um arquivo `hello.js` e chamando esse arquivo dentro de um HTML.

HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <script src='hello.js'>
    </script>
</body>
</html>
```

Arquivo javascript `hello.js`:
```
console.log('Ola mundo :)'); // imprime 'Ola mundo :)' no console
```

Todo código javascript que estiver no arquivo `hello.js` será executado quando abrirmos nosso HTML :)

- Também é possível executar javascript pelo console dos nossos navegadores, para isso, basta abrir o seu navegador, clicar com o botão direito em qualquer lugar e escolher "inspecionar elemento". Após isso, clique na aba "console".

No console, podemos colar nossos códigos Javascript, ou então escrever por lá mesmo. É muito útil para testes. No console, escreva `console.log("hello world");` para executar seu primeiro programa!