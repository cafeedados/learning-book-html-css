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

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

Exemplo explicado

O **```<html>```** elemento define o documento inteiro .

Possui uma tag de início **```<html>```** e uma tag de finalização **```</html>```**.

Dentro do elemento **```<html>```** está o **```<body>```** elemento.


<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>