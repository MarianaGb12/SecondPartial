# SecondPartial_OOP
Mariana Guerrero Benavides. 

## Problema escogido: Movie Tickets

## Diagrama de clases(uml)
![image](https://user-images.githubusercontent.com/98919850/201939709-e67a234b-d0fc-4629-8916-e62e12a95ebb.png)


## Explicación del uml: 
Se crea una clase Usuarios que tiene como atributos nombre de usuario y contraseña. Como métodos se implementan las opciones de registro e iniciar sesión. Se tiene una clase base abstracta Tiquetes, de la que heredan sus métodos las clases de tiquetes vip y regular. Luego, se tiene la clase Teatro que contiene todas las actividades que el usuario puede realizar en el teatro. Aquí existe una relación de composición entre teatro y tiquetes, puesto que no puede existir el teatro de películas, sin tiquetes para vender. Luego, tenemos una clase de Menú principal en el que los usuarios tendrán las opciones para registro y las acciones que puedan realizar en el teatro, mediante una relación respectivamente de asociación y agregación puesto que, el menú principal utiliza una instancia de Usuarios, pero usuarios puede existir sin el menú principal. 

