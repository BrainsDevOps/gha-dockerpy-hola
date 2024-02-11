# gha-dockerpy-hola
# gha-dockerpy-dice
Este repositorio forma parte de los ejemplos del curso de udemy [Domina Github Actions](https://www.udemy.com/course/domina-github-actions/?referralCode=CBFBAF72C38BE758CFE1)

Esta acción de github es un ejemplo de acción personalizada usando docker y python.

La acción devuelve como output el saludo al nombre que se pase como parámetro.

## Inputs
* nombre: El de la persona a saludar.
    * Valores aceptados: cadena de texto
    * Valor por defecto: John Doe

## Outputs
* saludo: "Hola, John Doe"
