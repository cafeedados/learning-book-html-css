# Elementos HTML

Um elemento HTML geralmente consiste em uma tag **inicial** e uma tag **final** , com o conteúdo inserido entre:

> **< tagname > O conteúdo entra aqui ... < / tagname >**

O **elemento** HTML é tudo, desde a tag inicial até a tag final:

> **< p > Meu primeiro parágrafo. < / p >**

Inicio da Tag                  | Conteúdo do Elemento    |   Fim da Tag
------------------------------ | -----------------------:|---------------:
```<h1> ```                    |       Cabeçalho         |  ```</h1> ```
```<p>  ```                    |       Paragrafo         |``` </p> ```
```<br> ```                    |                         |     


>Elementos HTML sem conteúdo são chamados de elementos vazios. Os elementos vazios não possuem uma tag final, como o elemento <br> (que indica uma quebra de linha)

## Elementos HTML aninhado

Os elementos HTML podem ser aninhados (os elementos podem conter elementos).

Todos os documentos HTML consistem em elementos HTML aninhados.

Este exemplo contém quatro elementos HTML:

Exemplo


```html
<!DOCTYPE html>
<html>
<body>

<h1>Meu primeiro cabeçalho</h1>
<p>Meu primeiro paragrafo</p>

</body>
</html>
```

Exemplo explicado

O **```<html>```** elemento define o documento inteiro .

Possui uma tag de início **```<html>```** e uma tag de finalização **```</html>```**.

Dentro do elemento **```<html>```** está o **```<body>```** elemento.

```html
<html>
<body>

<h1>Meu primeiro cabeçalho</h1>
<p>Meu Primeiro paragráfo</p>

</body>
</html>
```

O **```<body>```** elemento define o corpo do documento .

Possui uma tag de início **```<body>```** e uma tag de final **```</body>```**.

Dentro do elemento **```<body>```** há dois outros elementos HTML: **```<h1>```** e **```<p>```**.

```html
<body>

<h1>Meu primeiro cabeçalho</h1>
<p>Meu Primeiro paragráfo</p>

</body>
```

O **```<h1>```** elemento define um cabeçalho .

Possui uma tag **inicial** **```<h1>```** e uma tag **final** **```</h1>```**.

O **conteúdo do** elemento é: Meu primeiro título.


```html
<h1>Meu primeiro cabeçalho</h1>
```

O **```<p>```** elemento define um parágrafo .

Possui uma tag de **início** **```<p>```** e uma tag de **finalização** **```</p>```**.

O **conteúdo do** elemento é: Meu primeiro parágrafo.

```html
<p>Meu Primeiro paragráfo</p>
```

## Não esqueça a tag final

Alguns elementos HTML serão exibidos corretamente, mesmo se você esquecer a tag final:

Exemplo
```html
<html>
<body>

<p>This is a paragraph
<p>This is a paragraph

</body>
</html>
```

O exemplo acima funciona em todos os navegadores, porque a marca de fechamento é considerada opcional.

**Nunca confie nisso. Pode produzir resultados inesperados e / ou erros se você esquecer a tag final.**

## Elementos HTML vazios

Elementos HTML sem conteúdo são chamados de elementos vazios.

**```<br>```** é um elemento vazio sem uma tag de fechamento (a **```<br>```** tag define uma quebra de linha):




Exemplo
```html
<p>Isso é um paragrafo na primeira linha<br> paragrafo quebrado para segunda linha</p>
```

Elementos vazios podem ser "fechados" na tag de abertura assim: **```<br />```**.

O HTML5 não requer que elementos vazios sejam fechados. Mas se você deseja uma validação mais rígida ou se precisa tornar seu documento legível por analisadores XML, feche todos os elementos HTML corretamente.

## HTML não diferencia maiúsculas de minúsculas

As tags HTML não diferenciam maiúsculas de minúsculas: **```<P>```** significa o mesmo que **```<p>```**.

O padrão HTML5 não requer tags em minúsculas, mas o W3C **recomenda** letras minúsculas em HTML e **exige** letras minúsculas para tipos de documentos mais rígidos, como XHTML.

>Eu, particularmentte sempre uso tags em minúsculas.


<hr>
<stong>Pedro Lourenço</strong><br>
<Strong>dev.pedrolourenco@gmail.com</strong><br>
<Strong>Instagram: @devpedrolourenco</strong>