# Lesson links

Para criação de links no markdown, você pode seguir os seguintes métodos.

## Link one

[Clique aqui](https://github.com/junior-maciel/markdown)

É usado colchetes [ ] e parenteses ( ), onde dentro do colchetes é colocado o texto do link, e dentro dos parenteses é colocado o link de destino.

## Link two

[Visite o repositório](https://github.com/junior-maciel/markdown "Markdown Class")

Aos links pode-se adicionar um texto alternativo, que é exibido ao pairar o mouse por alguns segundos no link, para isso basta adicionar dentro dos parenteses após o link, o seu texto alternativo entre aspas ( " )
Ex: "Texto alternativo"

## Link three

Podemos usar variáveis como links, caso você possua links que serão repetidos em diversos locais dentro da sua página, este método é utilizado para facilitar a manutenção ou atualização de links que precisam ser exibidos em diversos locais dentro do seu projeto.

[site-url]: https://github.com/junior-maciel/markdown

Após definir uma variável para seu link, você agora irá chamar a sua variável dentro de colchetes no lugar de parenteses.

No primeiro colchetes você irá digitar o texto do link, e no segundo colchetes digite a variável do seu link.

[Clique aqui][site-url]