---
layout: post
title: "Documentar con PyDoc"
description: "Cómo documentar las clases gracias a PyDoc"
category: Documentación
tags: [PyDoc, Python, Documentar python, Evenge, Gestor de eventos]
---

Python ofrece un mecanismo sencillo para la documentación y es que si el primer bloque de la definición del objeto es una cadena de texto, ésta se asocia a la variable **__doc__** automáticamente.

Tal y como podemos ver en el ejemplo de acontinuación, hay que instar justo depués de la definición de la función el comentario.

Empezamos por tres comillas, lo cuál significa que el comentario va a tener más de una línea, seguido por una breve explicación de que hace dicha función, sus argumentos y opcionalmente unos test de prueba, que habría que poner para ejecutarlo y la salida esperada.


Ejemplo:

```python
  def sumar_dos_numeros(a, b):
    """Suma dos números y retorna su resultado

    Argumentos:
    a -- primer sumando
    b -- segundo sumando

    Test:
    >>> sumar_dos_numeros(25, 10)
    35
    >>> sumar_dos_numeros(30, 20)
    50
    """

    return a + b
```
Fuente: [Mundogeek.net](http://mundogeek.net/archivos/2008/07/07/documentacion-en-python/)  
