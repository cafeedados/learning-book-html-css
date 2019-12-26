# Atributos HTML

Atributos fornecem informações adicionais sobre elementos HTML.

## Atributos HTML

- Todos os elementos HTML podem ter atributos

- Atributos fornecem informações adicionais sobre um elemento

- Os atributos são sempre especificados na tag inicial

- Os atributos geralmente vêm em pares nome / valor, como: name = "value"

## O atributo href

Os links HTML são definidos com a **```<a>```** tag. O endereço do link é especificado no **```href```** atributo:

```html
<a href="https://github.com/devpedrolourencov">Isso é um Link</a>

```

Você aprenderá mais sobre os links e a **```<a>```** tag posteriormente neste tutorial.

## O atributo src

Imagens HTML são definicas com a **```<img>```** tag. 

O nome do arquivo da fonte da imagem é especificado no **```src```** atributo. 

```html
<img src="img_devpedrolourenco.jpg">

```

## Atributos de largura e altura

As imagens HTML têm **```width```** (largura) e **```height```** (altura) atributos, que especificam a largura e a altura da imagem:

```html
<img src="img_devpedrolourenco.jpg" width="500" height="600">

```

A largura e a altura são especificadas em pixels por padrão; então width = "500" significa 500 pixels de largura.

Você aprenderá mais sobre imagens em nosso tutorial Imagens em HTML .

## O atributo alt

O ```alt``` atributo especifica um texto alternativo a ser usado, se uma imagem não puder ser exibida.

O valor do ```alt``` atributo pode ser lido pelos leitores de tela. Dessa forma, alguém "ouvindo" a página da Web, por exemplo, uma pessoa com deficiência visual, pode "ouvir" o elemento.

```html

<img src="img_devpedrolourenco.jpg" alt="Essa imagem é do Grande Aprendiz de tecnologia">

```

> O **alt** atributo também é útil se a imagem não puder ser exibida (por exemplo, se ela não existir):

O atributo style

O **```style```** atributo é usado para especificar o estilo de um elemento, como cor, fonte, tamanho etc.

```html

<p style="color:red">Esse paragráfo será da cor vermelha</p>

```

## O atributo lang

O idioma do documento pode ser declarado na **```<html>```** tag.

O idioma é declarado com o **```lang```** atributo

A declaração de um idioma é importante para aplicativos de acessibilidade (leitores de tela) e mecanismos de pesquisa:

```html

<!DOCTYPE html>
<html lang="pt-BR">
<body>

...

</body>
</html>

```
As duas primeiras letras especificam o idioma (pt). Se houver um dialeto, adicione mais duas letras (BR).

## O atributo title

Aqui, um **```title```** atributo é adicionado ao **```<p>```** elemento. O valor do atributo title será exibido como uma dica de ferramenta quando você passa o mouse sobre o parágrafo:

```html

<p title="Eu amo programar">
Isso é um paragráfo.
</p>

```

## Atributos HTML

Atributo                       | Descrição   
------------------------------ | ---------------------------------------------------------------------------------------------:
 alt                           |  Especifica um texto alternativo para uma imagem, quando a imagem não pode ser exibida.        
 disabed                       |  Especifica que um elemento de entrada deve ser desativado        
 href                          |  Especifica o URL (endereço da web) para um link                     
 id                            |  Especifica um ID exclusivo para um elemento
 src                           |  Especifica o URL (endereço da web) para uma imagem  
 style                         |  Especifica um estilo CSS embutido para um elemento
 title                         |  Especifica informações extras sobre um elemento (exibido como uma dica de ferramenta)    


 <hr>
<stong>Pedro Lourenço</strong><br>
<Strong>dev.pedrolourenco@gmail.com</strong><br>
<Strong>Instagram: @devpedrolourenco</strong>         