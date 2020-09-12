# Version del curso
Version actual: v1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines

Underline1
--------------

Underline2
============

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tacahdo~~.
- aqui podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~. 

#Listas
1. Esto es una lista ordenada.
2. Esto es una lista ordenada.
3. Esto es una lista ordenada.

- Esto es una lista desordenada.
- Esto es una lista desordenada.
- Esto es una lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link en HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html) 

# Imagenes
![Logo GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)


# Code Snippets
Código en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Código en JavaScript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```


# Tablas

| Nombre | Apellido | Documento|
| ------ | ---------| ---------|
|Fernando|Vercellino|29739893  |
|Rocio|Martinatto|34989898|

# Citas
Esto es un texto referente a una cita que pondremos debajo:
>Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
>Esto es otra cita

# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios.

---

Esto es un texto que sera dividido por asteriscos.

***

Esto es un texto que sera dividido por guiones bajos.

___


# Saltos de Linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista

