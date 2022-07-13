# Lesson Code Block

## Example in line

Informe os parâmetros `username` e `password` para a função `login()`.

Para destacar uma palavra ou sequência de palavras em um parágrafo, pode ser usado a crase ( ` ) deixando o conteúdo a ser destacada em formato de código entre a crase.

## Example in line in JS

``const message = `My name is ${name}`;``

Quando estiver trabalhando em uma linguagem que precise descrever trecho de código javascript onde a crase faz parte do código, para que o markdown reconheça o bloco de código, você pode adicionar duas crases no início e ao final da sentença.

## Example in block one

    // login.js

    const username = 'robertoachar';
    const password = 'secret';

    login(username, password);

Ao trabalhar com trechos de código, que precisem ser exibidos visualmente como um bloco de código, você pode selecionar todo o conteúdo e adicionar tabulação duas vezes, o markedown reconhecerá automaticamente como trecho de código e vai renderizar corretamente como exibido acima.

## Example in block two

```
// login.js

const username = 'robertoachar';
const password = 'secret';

login(username, password);
```

Outra forma de exibir um bloco de código, é adicionando três crases ( ` ) no início e ao final da marcação, sem a necessidade de inserir tabulação no bloco de texto.

## Syntax Highlighting

```javascript
// login.js

const username = 'robertoachar';
const password = 'secret';

login(username, password);
```

Mais uma opção é você identificar de qual linguagem você está referenciando aquele bloco de código, no exemplo acima temos a adição do nome `javascript` após os três crases do início, o markdown irá renderizar conforme o padrão de marcação visual do código javascript.

## Example in block with indentation

```
|--...
|--build/
|  |--ios/
|  |--android/
|--docsite/ *bootstrap *open-props
|--src/
|  |--themes/
|     |--light.xx
|     |--dark.xx
|  |--tokens/
|     |--color.xx
|     |--typography.xx
|     |--sizes.xx
|     |...
