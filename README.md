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

\1. Item 1
\2. Item 2
\3. Item 3

As listas acima serão exibidas dessa maneira, respectivamente:

> * Item 1

> * Item 2

> * Item 3

> 1. Item 1

> 2. Item 2

> 3. Item 3