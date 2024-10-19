# Guia para uso de Markdowns para Github

Para cabeçalhos, utilizamos `#` e a cada # adicionado representa um nível, indo de 1 a 6, seguindo exemplo abaixo:

# Cabeçalho 1 
## Cabeçalho 2 
### Cabeçalho 3 
#### Cabeçalho 4 
##### Cabeçalho 5 
###### Cabeçalho 6

## Enfase em textos

Para enfase em um texto, podemos utilizar algumas atribuições como: Negrito, Itálico, Riscado... entre outros, conforme exemplo abaixo:

### Negrito

Este é um texto em **negrito** . Para utilizar essa marcação é necessário utilizar a palavra entre asteriscos `**`

### Itálico

Este é um texto em _itálico_. Para utilizar essa marcação é necessário utilizar a palavra entre underlines `_texto aqui_`


### Riscado

Este é um texto em ~~Riscado~~. Para utilizar essa marcação é necessário utilizar a palavra entre til `~~texto_aqui~~`


### Linha horizontal

Se você deseja fazer uma linha horizontal para dividir conteúdos, você pode utilizar `---` ou `___` 

---
 --Texto entre as linhas-- 
___

## Blocos de citação

Para criar blocos de citações é necessário utilizar o `aspas`

`Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nemo laboriosam voluptatum nesciunt
perspiciatis itaque id adipisci a, dolores debitis eos? Error eligendi aspernatur ipsam
exercitationem quae temporibus nam asperiores.`

## Links

O texto que queremos utilizar para o link vai entre `[]` e o link vai entre `()` logo após o texto.

[Epaminondas Lage](https://github.com/Epaminondaslage)

Se você deseja adicionar um título par ao link que você está criando (para aparecer quando você posiciona o mouse no link), é só você dar um espaço após o `()` e adicionar o texto do título entre aspas 

[Epaminondas Lage Github](https://github.com/Epaminondaslage) "Pagina do GitHub do Epaminondas"

## Imagens

A imagem deve estar depois de `![texto_legenda]` seguido por entre `()` com o link da imagem.

![imagem](https://source.unsplash.com/random/200x200)

## Listas Não Ordenadas

Para criação de listas não ordenadas é necessário colocar o asterisco `-  Item` antes do item para criar a lista. Exemplo:

-  Item 1
-  Item 2
-  Item 3

Se você deseja criar - - _sub itens_- -  dentro da lista, é só realizar a identação na lista, conforme exemplo:

-  Item 1
-  Item 2
  -  Sub item 1
    -  Sub item 2
      -  Sub item 3

## Listas Ordenadas

Para listas ordenadas, é necessário colocar os números `1. Item 1`  antes do item para criar a lista. Exemplo:

1. Item 1
2. Item 2
   1. Sub 1
   2. Sub 2
3. Item 3
   1. Sub 1
      a. Sub 1
      b. Sub 2

## Comentários de Códigos

### Uma linha de código em forma de comentário

Para colocar uma linha de códigos em forma comentários, é necessário utilizar  \`código` que o resultado será:

`&lt;p&gt; Este é um paragrafo em html&lt;/p&gt;`

### Várias linhas de código em forma de comentário
Para colocar um bloco de códigos em forma comentários, é necessário utilizar  \```html
código```  e também é - - _recomendado_- -  que você coloque a linguagem em que aquele bloco de código está escrito, para facilitar a marcação de palavras reservadas daquela linguagem.

#### Html
``` html
&lt;!DOCTYPE html&gt;
&lt;html lang="pt-BR"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  &lt;title&gt;Página&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
  
&lt;/body&gt;
&lt;/html&gt;
```

#### Bash
```bash
ls

pip install pandas

pip install --upgrade --user pandas

```

#### Prompt de Comando
```cmd
cd C:\\User\YourUser\Desktop

mkdir Folder
```

#### Python
```python
def hello():
    print('Hello World')

if __name__ == "__main__":
    hello()
```

## Tabelas

Para criar tabelas é necessário utilizar um formato específico para o Github, conforme bloco de códigos abaixo:

```bash
| Cabeçalho | Cabeçalho | Cabeçalho |
| --- | --- | --- |
| conteúdo | conteúdo | conteúdo |
| conteúdo | conteúdo | conteúdo |

```

| Nome | Tipo | Ataque |
| --- | --- | --- |
| Pikachu | Elétrico | 50 |
| Charmander | Fogo | 50 |

## Lista de Tarefas

Para fazer uma lista de tarefas é necessário utilizar um formato específico para o Github, conforme bloco de códigos abaixo:

```bash
- [x] Item completado
- [x] Item completado
- [ ] Item não completado
```


- [x] Criar arquivo guia para Readme no Github
- [x] Commit das mudanças
- [ ] Envio das mudanças para o repositório</pre>
