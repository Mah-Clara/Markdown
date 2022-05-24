# Guia básico de Markdown Syntax
[Markdown Syntax](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open) é uma sintaxe usada para padronizar e facilitar formatação de texto na web, utilizada em aplicativos como [Slack](https://slack.com/) e [GitHub](https://github.com/). Textos estilizados com **Markdown** são, na maioria dos casos, apenas texto com caracteres não-alfabéticos, como **#**, **\*** e **![]()**, usados para a configuração de títulos, listas, itálico, negrito e inserção de imagens.

> O Markdown funciona como um conversor de texto para HTML: os caracteres não-alfabéticos são traduzidos como ```<b>```, ```<i>``` e ```<a href>```, etc. Já os textos sem formatação entram como parágrafo simples ```<p>```.

# Lista de comandos em Markdown
Veja abaixo uma lista dos comandos em markdown e alguns exemplos de seu uso:

## #1 Titulação

\# Título ```<h1>```

\#\# Título ```<h2>```

\#\#\# Título ```<h3>```

\#\#\#\# Título ```<h4>```

\#\#\#\#\# Título ```<h5>```

\#\#\#\#\#\# Título ```<h6>```

## #1.1 Exemplos de titulação

# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

## #2 Ênfase
Para adicionar ênfase ao conteúdo que será escrito, usa-se o asterisco ```*``` ou traço-baixo (_underline_) ```_```:

* **Negrito**: adicione dois asteriscos \*\*texto\*\* ou dois traços-baixos \_\_texto\_\_ no início e no fim do conteúdo.

* **Itálico**: adicione apenas um asterisco \*texto\* ou um traço-baixo \_texto\_ no início e no fim do conteúdo.

* **Negrito itálico**: adicione três asteriscos \*\*\*texto\*\*\* ou dois asteriscos e um traço-baixo \*\*\_texto\_\*\* no início e no fim do conteúdo.

> Este é um exemplo de um texto que possui uma ênfase em **negrito**, em _itálico_ e em **_negrito itálico_**.

## #3 Links
Existem duas formas de inserir link em Markdown, através de um **link direto** ou usando um **texto-âncora**:

* **Texto-âncora**: utilize os caracteres ```[]()```, adicionando entre chaves o texto que você quer que apareça, e entre os parênteses, o endereço de destino, no formato ```[meu perfil no GitHub](https://github.com/mah-clara/)```.

* **Link direto**: envolva o endereço da web em chaves <>. O endereço ficará visível e será clicável pelo usuário. O endereço em forma de link direto tem o formato ```<https://github.com/mah-clara/>```.

> Este é [meu perfil no GitHub](https://github.com/mah-clara/), e este é um link direto <https://github.com/mah-clara/> do meu perfil.

## #4 Listas de itens
Para listas não ordenadas, utilize um asterisco ```*``` na frente to item da lista:

\* Item 1

\* Item 2

\* Item 3

Para listas ordenadas, utilize o número do item seguido de ponto ```.``` :

1\. Item 1

2\. Item 2

3\. Item 3

As listas acima serão exibidas dessa maneira, respectivamente:

> * Item 1

> * Item 2

> * Item 3

> 1. Item 1

> 2. Item 2

> 3. Item 3

## #5 Imagens
O código para inserir uma imagem no conteúdo é semelhante ao código de inserir links-âncora, adicionando um ponto de exclamação ```!``` no início do código, como no exemplo abaixo:

**\![Alt ou título da imagem](URL da imagem)**

Embora seja um comando simples de ser utilizado, não é possível alterar o tamanho da imagem por meio dele. Outra opção viável e mais recomendada é:

* **Porcentagem**
```html
<img src="URL da imagem" width=número%>
```
* **Pixels**
```html
<img src="URL da imagem" width="número">
```
### Exemplo:
```html
<img src="https://github.githubassets.com/images/modules/logos_page/Octocat.png" width="50">
```

> A imagem do exemplo acima será exibida dessa maneira, respectivamente: <img src="https://github.githubassets.com/images/modules/logos_page/Octocat.png" width="50">.

> Imagens grandes podem estar em linhas individuais, para serem exibidas em maior tamanho.

## #6 Citação (Quote)
Para transformar um texto em uma citação ou comentário, semelhante ao código HTML \<blockquote\>, utilize o sinal ```>``` no início da linha que será formatada:

\>Este é um *blockquote*. O sinal usado abre e fecha este código no HTML. 
\>Para adicionar mais uma linha à citação, basta teclar Enter para um novo
\>código sinal. Isso gerará um novo parágrafo dentro do *blockquote*.
\>Códigos de \*\*negrito\*\*, \_itálico\_ e \<https://links.com\> funcionam aqui.

Como aparece no HTML:

>Este é um *blockquote*. O sinal usado abre e fecha este código no HTML. 
>Para adicionar mais uma linha à citação, basta teclar Enter para um novo
>código sinal. Isso gerará um novo parágrafo dentro do *blockquote*.
>Códigos de **negrito**, _itálico_ e <https://links.com> funcionam aqui.

## #7 Código (Code Highlight)
Há dois modos de adicionar trechos de código ao Markdown:

* **Código em linha** (_inline_): adicione um acento grave ```ˋ``` no início e no final do código.

* **Múltiplas linhas de código**: envolva as linhas de código com três acentos graves ```ˋˋˋ``` ou três tils ```~~~```.

 Esta é uma linha que contém um \`código\`.

\`\`\`
Esta é uma linha de código
\`\`\`

 Para especificar que tipo de linguagem está sendo apresentada no bloco de códigos adicionando o nome da linguagem de programação após o ```ˋˋˋ``` ou ```~~~```, por exemplo ```~~~javascript``` ou ```~~~ruby```. Veja nos exemplos abaixo:

\~\~\~javascript
Esta é uma linha de código em Javascript.
\~\~\~

\~\~\~php
Esta é uma linha de código em PHP.
\~\~\~

\~\~\~html
Esta é uma linha de código em HTML.
\~\~\~

~~~javascript
Esta é uma linha de código em Javascript.
~~~
~~~php
Esta é uma linha de código em PHP.
~~~
~~~html
Esta é uma linha de código em HTML.
~~~

> Aqui está a lista de [linguagens suportadas](https://pygments.org/languages/) pelo Pygments, usada em nosso **Learning Center**.