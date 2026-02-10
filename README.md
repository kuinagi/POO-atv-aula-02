# Aprendendo Markdown

## Trechos de código

Você pode criar blocos de código isolados colocando acentos graves triplos ``` antes e depois do bloco de código. É recomendável colocar uma linha em branco antes e depois dos blocos de código para facilitar a leitura da formação bruta.

Você pode adicionar um identificador de linguagem opcional para habilitar o realce de sintaxe no bloco de código isolado.

O realce da sintaxe altera a cor e o estilo do código-fonte para facilitar a leitura.

Por exemplo, para código Ruby do realce de sintaxe:

````
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
````

Isso exibirá o bloco de código com o realce de sintaxe:

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Utilizar esse método para todas as liguagens, somente alterando para o nome da linguagem que deseja após as ```.

## Formatação  de texto e ALERTS

# Nota (Note): Informações úteis que os utilizadores devem saber, mesmo ao ler o conteúdo rapidamente.

# Dica (Tip): Conselhos úteis para fazer as coisas melhor ou mais facilmente.

# Importante (Important): Informações cruciais que os utilizadores precisam de saber para atingir o seu objetivo.

# Aviso (Warning): Informações urgentes que necessitam da atenção imediata do utilizador para evitar problemas.

# Cuidado (Caution): Alerta sobre riscos ou resultados negativos de certas ações.