# Responsive Web Desing:
Consiste en utilizar HTML y CSS para adaptar un sitio web con el fin que se vea bien en todos los dispositivos móviles: tabletas y teléfonos.

## Desktop first & Mobile first


## Media Queries
Son reglas que nos permiten concicionar los estilos siempre que se cumplan ciertas condiciones.

## Breakpoints
Es una resolución expresada en pixeles con la que ordenamos a nuestro media query que cambie algo al alcanzar esa medida.

En este ejemplo el breakpoint sería 767px y le estoy indicando a mi media query, que efectue un cambio de estilos al ser menor o igual a dicha medida.

```
@media (max-width:767px) {
    ul {....
          }
}
```
