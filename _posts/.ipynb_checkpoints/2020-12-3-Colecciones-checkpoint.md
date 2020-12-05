---
layout: article
title: Colecciones
categories: articles
---

Las colecciones son una manera de agrupar varios elementos. En otros notebooks vimos cómo funcionan las listas, que es la colección más usada, pero se trata solo de la punta del iceberg. Con Python tenemos varias manera de almacenar conjuntos de datos, dependiendo del tipo de dato, finalidad, tipo de acceso y rendimiento.

![imagen python]({{ site.baseurl }}/images/python.jpg)

1. [Listas](#1.-Listas)
2. [Tuplas](#2.-Tuplas)
3. [Diccionarios](#3.-Diccionarios)
4. [Sets](#4.-Sets)
5. [Conversiones entre colecciones](#5.-Conversiones-entre-colecciones)
6. [Resumen](#6.-Resumen)

## 1. Listas
Ya conocemos bastante las listas. Veamos un repaso de lo que podemos hacer con ellas, así como algunas funcionalidades nuevas

```Python
# Listas de números, strings, booleanos, con elementos repetidos, listas anidadas...
nums = [6, 2, 8, 3, 4, 5, 5]
months = ["Enero", "Febrero", "Marzo"]
mix = [5, 7, "Abril", True, None, ["Blanco", "Negro"]]

# Longitud de la lista
print(len(nums))

# Indexación
print(months[0])
print(months[len(months)-1]) # -1 porque len = 3 y el orden de los elementos es [0,1,2]
```