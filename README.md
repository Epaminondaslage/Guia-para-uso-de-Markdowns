

# Guia para uso de Markdowns para Github

1. [Cabeçalhos](#Cabeçalhos)
2. [Enfase em textos](#Enfase-em-textos)
3. [Blocos de citação](#Blocos-de-citação)
4. [Links](#Links)
5. [Imagens](#Imagens)
6. [Listas Não Ordenadas](#Listas-Não-Ordenadas)
7. [Listas Ordenadas](#Listas-Ordenadas)
8. [Comentários](#Comentários)
9. [Comentário simples em HTML](#comentário-simples-em-html)
10. [Comentário dentro de código](#comentário-dentro-de-código)
11. [Exemplo de Programa em Python](#exemplo-de-programa-em-python)
12. [Tabelas](#Tabelas)
13. [Lista de Tarefas](#Lista-de-Tarefas)


## Cabeçalhos 
Para cabeçalhos, utilizamos `#` e a cada `#` adicionado representa um nível, indo de 1 a 6, seguindo exemplo abaixo:

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

Esse bloco de citação é criado utilizando o símbolo > no início da linha, e você pode formatar tanto a citação quanto o nome do autor como desejar. A citação é geralmente destacada na renderização com uma barra lateral ou um recuo.

> "A simplicidade é a maior sofisticação."  
> – Leonardo da Vinci


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

Se você deseja criar ` _sub itens_ `-  dentro da lista, é só realizar a identação na lista, conforme exemplo:

-  Item 1
-  Item 2
  - Sub item 1
    - Sub item 2
       - Sub item 3

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

## Comentários 

Em Markdown, a sintaxe de comentário pode ser feita usando os seguintes padrões, embora comentários não sejam parte oficial do Markdown e não sejam exibidos em muitos renderizadores:


#### Comentário simples (em HTML)

Use a sintaxe de comentário do HTML. Esse tipo de comentário não será exibido no resultado renderizado.

markdown
```
<!-- Este é um comentário e não será exibido -->
```

#### Várias linhas de código em forma de comentário

Para colocar um bloco de códigos em forma comentários, é necessário utilizar  ```html código```  e também é `_recomendado_`  que você coloque a linguagem em que aquele bloco de código está escrito, para facilitar a marcação de palavras reservadas daquela linguagem.

#### Html
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Olá, Mundo!</title>
</head>
<body>
    <h1>Olá, Mundo!</h1>
</body>
</html>
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
# Solicita ao usuário dois números
numero1 = float(input("Digite o primeiro número: "))
numero2 = float(input("Digite o segundo número: "))

# Calcula a soma dos dois números
soma = numero1 + numero2

# Exibe o resultado
print(f"A soma de {numero1} e {numero2} é {soma}.")
```

## Tabelas

Para criar tabelas é necessário utilizar um formato específico para o Github, conforme bloco de códigos abaixo:


| Cabeçalho | Cabeçalho | Cabeçalho |
| --- | --- | --- |
| conteúdo | conteúdo | conteúdo |
| conteúdo | conteúdo | conteúdo |


| Nome | Tipo | Ataque |
| --- | --- | --- |
| Pikachu | Elétrico | 50 |
| Charmander | Fogo | 50 |

## Lista de Tarefas

Para fazer uma lista de tarefas é necessário utilizar um formato específico para o Github, conforme bloco de códigos abaixo:


- [x] Item completado
- [x] Item completado
- [ ] Item não completado


- [x] Criar arquivo guia para Readme no Github
- [x] Commit das mudanças
- [ ] Envio das mudanças para o repositório</pre>
