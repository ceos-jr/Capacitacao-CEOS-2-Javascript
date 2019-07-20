# javascript-training-ceos

No principio, Javascript era uma linguagem voltado ao browser (nossos navegadores), e era uma linguagem bem simples. Porém, com o passar do tempo, Javascript foi se tornando cada vez mais popular, e hoje em dia a linguagem possui um amplo ecossistema, executando também no lado do servidor. Iremos aprender javascript para adicionarmos interatividade em nossos sites, quanto para escrever futuras aplicações no lado do servidor.

# Como executar Javascript

Existem algumas formas, vou apresentar duas maneiras:

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

<!-- # Sobre essa trilha

A trilha de javascript possui 2 opções de materiais: uma apostila que estamos produzindo, e um material alternativo, que são partes selecionadas do livro You Don't Know JS. -->

# Índice de conteúdos

1. Variáveis e valores - [Apostila](https://ceos-jr.github.io/Capacitacao-CEOS-2-Javascript/1)

2. Operadores - [Apostila](https://ceos-jr.github.io/Capacitacao-CEOS-2-Javascript/2)

3. Conversão entre tipos - [Apostila](https://ceos-jr.github.io/Capacitacao-CEOS-2-Javascript/3)

4. Estruturas de decisão - [Apostila](https://ceos-jr.github.io/Capacitacao-CEOS-2-Javascript/4)

5. Estruturas de repetição - [Apostila](https://ceos-jr.github.io/Capacitacao-CEOS-2-Javascript/5)

6. Funções - [Apostila]()

7. Escopo de variáveis - [Apostila]()

8. Closures - [Apostila]()

9. Objetos - [Apostila]()

10. Arrays - [Apostila]()

11. Spread e Rest - [Apostila]()

12. Estruturas de dados - [Apostila]()

13. Try/Catch/Finally/throw - [Apostila]()

14. this - [Apostila]()

15. Arrow functions - [Apostila]()

16. prototype - [Apostila]()

17. Class - [Apostila]()
