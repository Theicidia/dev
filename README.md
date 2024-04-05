<h1 style="text-align:center;">
    ANTLR
    <span style="font-size: 20px; position: relative; top: -2.5px">
        :java
    </span>
</h1>

<h2 style="text-align:center;">Documentacion para principiantes</h2>

<h2> 1: Bienvenida </h2>

Hola, hoy les vengo a presentar **JavaCC**, que es un creador de [**Lexico**](Lexico) e [**Sintatico**](Sintatico) que sirve para crear tus propios formatos de codigo
<sup>
    (pseudecodigo)
</sup>
que fue creado por **Terence Parr** y su sitio web es [antlr.org](http://antlr.org), al igual con sitio de editor de **ANTLR** que es [lab.antlr.org](http://lab.antlr.org/) e gratuito.

<h2> 2: Lenguaje de Gramatica</h2>

en esta parte voy a prensentar las palabras clave
<sup>
    keyword
</sup>
 como gramaticas:

<h3 style="text-align:center;">
    2.1: Palabras clave
    <span style="font-size:10px; position:relative; top:-2px;">
        (keyword)
    </span>
</h3>

| Keywords | Descripcion | conjunto | ejemplo |
|:-:|:-:|:-:|:-:|
| <span style="color:#CC7832;">grammar</span> | para definir tus gramaticas | <span style="color:#CC7832;">parse</span> o <span style="color:#CC7832;">lexer</span> | <span style="background-color: #202020; padding:4px; border-radius:7.5px;color:#CC7832;">grammar <span style="color:grey;">Name_Grammar;</span><span></span>|
| <span style="color:#CC7832;">lexer</span> | para definir tus lexico no permite parse | <span style="color:#CC7832;">grammar</span> | <span style="background-color: #202020; padding:4px; border-radius:7.5px;color:#CC7832;">lexer grammar <span style="color:grey;">Name_Lexer;</span><span></span>|
| <span style="color:#CC7832;">parse</span> | para definir tus parse no permite lexico | <span style="color:#CC7832;">grammar</span> | <span style="background-color: #202020; padding:4px; border-radius:7.5px;color:#CC7832;">lexer grammar <span style="color:grey;">Name_Lexer;</span><span></span>|




```java


```

