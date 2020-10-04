---
layout: post
title: "Markdown study"
subtitle: "Markdown syntax study"
category: Studies
tags: Code-Review
image: https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg

---

# Markdown Syntax

## Contents
 * [Intro](#Intro) 
 * [Design](#Design)
    * [Line](#Line)
    * [Header](#Header)
    * [Font](#Font)
    * [Footnote](#Footnote)
    * [Quote](#Quote)
    * [Line](#Line)
 * [Tricks](#)
    * [Image](#Image)
    * [Code](#Code)
    * [URL](#URL)
    * [Table](#Table)
    * [Gif](#Gif)


<br>
<br>  

## __Intro__ <a id="Intro"></a>
      
Hello, This page is for *__Markdown syntax__* review.  
Markdown have simple and easy syntax, but highly effective.  
So, Markdown have been loved as *__README__* file since 2004.  

If you have a plan to create your own *__github pages__* or *__jupyter notebook__*, (*or if you already have except markdown*) markdown could enrich your *__github__* / *__jupyter notebook__* quality. 



<br>  

***    


## *Design* <a id="Design"></a>

> At here, 

### *Line* <a id="Line"></a>

Markdown looks like text file, but 

| ```Markdown[ENTER]```  
Markdown
```Markdown[SPACE x 2]```  
Markdown  

### *Header* <a id="Header"></a>

! _Note_ !  
*White space should be exist after "#"*

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown Syntax</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge"># Heading level 1</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;Heading level 1&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip="" id="heading-level-1">Heading level 1</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">## Heading level 2</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;Heading level 2&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip="" id="heading-level-2">Heading level 2</h2></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">### Heading level 3</code></td>
      <td><code class="highlighter-rouge">&lt;h3&gt;Heading level 3&lt;/h3&gt;</code></td>
      <td><h3 class="no-anchor" data-toc-skip="" id="heading-level-3">Heading level 3</h3></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">#### Heading level 4</code></td>
      <td><code class="highlighter-rouge">&lt;h4&gt;Heading level  4&lt;/h4&gt;</code></td>
      <td><h4 class="no-anchor" id="heading-level-4">Heading level 4</h4></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">##### Heading level 5</code></td>
      <td><code class="highlighter-rouge">&lt;h5&gt;Heading level 5&lt;/h5&gt;</code></td>
      <td><h5 class="no-anchor" id="heading-level-5">Heading level 5</h5></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">###### Heading level 6</code></td>
      <td><code class="highlighter-rouge">&lt;h6&gt;Heading level 6&lt;/h6&gt;</code></td>
      <td><h6 class="no-anchor">Heading level 6</h6></td>
    </tr>
  </tbody>
</table>

<br>  

### *Font* <a id="Font"></a>

| *__Syntax__*  | *__Result__*  |*__Remark__*  |
|:-------------:|:-------------:|:-------------:|
| ```__Bold__ ```     |   __Bold__ |Markdown|
| ```*Italic*```     |      *Italic*      |Markdown|
| ```___*Bold-Italic*___```      |      __*Bold-Italic*__      |Markdown|
|```<span style="color:skyblue">SkyBlue</span>```|<span style="color:skyblue">SkyBlue</span>|Html|

<br>

### *Footnote* <a id="Footnote"></a>
Footnote [^1]

### *Quote* <a id="Quote"></a>
René Descartes said,
> Cogito, ergo sum ( *I think, therefore I am* )  

### *Line* <a id="Line"></a>

<br>
***
<br>

## *Trick* <a id="Trick"></a>

> From here, let's handle some useful tricks for markdown.

### *URL* <a id="URL"></a>

```
[URL Name]("URL Link")
```
>
   e.g)
   ```
   [Github](www.github.com)
   ```
   [Github](www.github.com)

<br>

### *Image* <a id="Image"></a>
```
![IMAGE NAME]("IMG Link")
```
>
   e.g)  
   ```
   ![Github icon](https://avatars1.githubusercontent.com/u/9919?s=200&v=4)
   ```
   ![Github icon](https://avatars1.githubusercontent.com/u/9919?s=200&v=4)

<br>

### *Code* <a id="Code"></a>


### *Table* <a id="Table"></a>

Align :--- 

```
| Align Left  |  Align Mid  | Align Right  |
| :-----      | :-----:     | -----:       |
|     *1*     |     *1*     |     *1*      |
|    __2__    |    __2__    |    __2__     |
|      3      |      3      |      3       |
```

| Align Left  |  Align Mid  | Align Right  |
| :-----      | :-----:     | -----:       |
|     *1*     |     *1*     |     *1*      |
|    __2__    |    __2__    |    __2__     |
|      3      |      3      |      3       |

Actually, making table is quite boring stuff, try [Table Generater](https://www.tablesgenerator.com/markdown_tables).



*** 

- Markdown syntax (default size)  
![GIF](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

- html syntax (400x400)  
<img src="https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif" width="400" height="400" />


<br>

# Done!  

If you want to try to write *__Markdown__* at Visual Code,  
*__Right Click__* your md file and Select *__Open Preview__* (*Ctr+Shift+V*)

You could try [Markdown Tutorial](https://www.markdowntutorial.com/) 

[^1]: Footnote 1