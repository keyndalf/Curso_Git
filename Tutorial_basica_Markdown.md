# Aprendiendo _Markdown:_

¿Qué es? Lenguaje de marcado ligero. Se usa para redactar la mayoría de la documentación de los proyectos.

---
## Separar líneas:

Dejando un espacio en blanco entre líneas:

Línea 1.

Línea 2. (Se deja un espacio entre líneas...)

Para separar dos líneas dentro de un párrafo: (Se dejan dos espacios en blanco en la última posición de la línea, esto es):

Línea 1  
Línea 2

---
## Cursiva: 

_text_ (Los pisos bajos sirven para poner un texto en cursiva)

*text* (Aunque también funcionan los asteriscos, lo importante es que solo sea un piso bajo o un asterisco).

---
## Negritas: 

**texto** (Los asteriscos dobles sirven para poner un texto en negritas)

__texto__ (Los pisos bajos también sirven, lo importante es encerrar el texto entre dos guiones bajos o dos asteriscos).

---
## Cursiva más negritas: 

**_texto_** (Los dos asteriscos seguidos de un piso bajo para la cursiva)

***texto*** (Los tres asteriscos sirven para esto.)

___texto___ (Los tres pisos bajos también sirven para esto.)

<!--- Comentario: --->

## Poner un texto en su propio bloque:

    Un texto encerrado entre dos pisos bajos "_" es un texto que
    aparece en el documento final en cursiva.

---
## Niveles de encabezados (solo hay 6 niveles):

# Encabezado de nivel 1:

## Encabezado de nivel 2:

### Encabezado de nivel 3:

#### Encabezado de nivel 4:

##### Encabezado de nivel 5:

###### Encabezado de nivel 6:

---
## Formato para los encabezados:

Formato 1:

### Esto es un encabezado de nivel 3 ###

Formato 2 (Se crea un encabezado de nivel 1):

Esto es un encabezado de nivel 1
=

Formato 3 (Se crea un encabezado de nivel 2 subrayado):

Esto es un encabezado de nivel 2
-

---
## Crear enlaces:

Forma básica de hacerlo:

[Canal chevere](https://www.youtube.com/watch?v=FlsoBiteuPM)

Con título:

[Con título](https://joedicastro.com/pages/markdown.html "Título")

Sin título:

[Sin título](https://joedicastro.com/pages/markdown.html)

Múltiples enlaces:

[Enlace 1][1] [Enlace 2][2] [Enlace 3][3]

[1]: https://joedicastro.com/pages/markdown.html
[2]: https://joedicastro.com/pages/markdown.html
[3]: https://joedicastro.com/pages/markdown.html

Direccionador más sencillo usando simplemente una dirección de internet:

<https://joedicastro.com/pages/markdown.html>

---
## Crear direccionadores a alguna sección del documento, enlaces internos (Índices):

Los encabezados funcionan como direccionadores:

[Aprendiendo Markdown](#aprendiendo-markdown)

[Encabezado 1](#encabezado-de-nivel-1)

---
## Introducir imágenes en un documento:

Se pueden exportar imágenes usando rutas relativas de ubicación según el lugar donde esté la imagen dentro del archivo o introduciendo una url:

![imagen](img/Joseph_Joestar.jpg)
---
## Crear divisiones:

---

Este es un texto

---

Y esto es otro texto:
---
## Listas:

Ordenadas:

Basta con colocar el número seguido de un punto para comenzar a enumerar las cosas.

1. Elemento 1.
   1. Elemento 1.1:
2. Elemento 2.
3. Elemento 3.

No sirve comenzar una enumeración desde un punto distinto del uno:

10.  Elemento 10.
11.  Elemento 11.
12.  Elemento 12.

No ordenadas:

Basta con empezar la línea con un asterisco o con un guión:

Con Asterisco:

* Elemento 1.
  * Elemento 1.1.
* Elemento 2.
  
Con guión:

- Elemento a.
- Elemento b.
---
## Citas:

Cita en línea (Se usa el símbolo mayor que ">"):

> "Siempre tienes opción de no tener opinión" - Marco Aurelio.

Cita en bloque:

> Todo lo que escuchamos es una opinión, no un hecho.
> 
> Todo lo que vemos es una perspectiva, no la verdad.
>
> Marco Aurelio.

Tener en cuenta que las citas se pueden anidar, esto es:

> Nivel 1.
> > Nivel 2
> > 

---
## Tablas:

Los guiones que separan se colocan de acuerdo al número de columnas de la tabla, en el ejemplo se usan tres guiones porque solo hay tres columnas:

Con formato predeterminado:

| Nombre | Apellido | Edad |
| --- | --- | --- |
| Keyber | Sequera | 25 |
| Karen Yoselin | Sequera | 26 |

Con objetos centrados:

| Nombre | Apellido | Edad |
| :---: | :---: | :---: |
| Keyber | Sequera | 25 |
| Karen Yoselin | Sequera | 26 |

Con objetos a la izquierda (Por defecto):

| Nombre | Apellido | Edad |
| :--- | :--- | :--- |
| Keyber | Sequera | 25 |
| Karen Yoselin | Sequera | 26 |

Con objetos a la derecha:

| Nombre | Apellido | Edad |
| ---: | ---: | ---: |
| Keyber | Sequera | 25 |
| Karen Yoselin | Sequera | 26 |

---
## Destacar un código:

En línea: acento invertido `

Agrego código en el medio de la línea: `codigo`.

En varias líneas: triple acento invertido  ```

``` py # Se puede identificar el tipo de código colocando el nombre de la extensión del lenguaje usado.
def suma(a, b):
    return a + b
```
---
## Markdown es compatible con código HTML.

## Comentarios en Markdown.

<!-- Esto es un comentario -->

---
## El caracter de escape \:

Se usa al igual que el caracter de escape en una cadena de texto de Python. \*texto\* notar resalta el text en negritas.

---
## Diccionarios:

Se trabajan en combinaciones término-definición, de la siguiente manera:

Término : Definición  