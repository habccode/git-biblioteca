# git-biblioteca
# **¿Qué son los actores y cómo identificarlos?**
Actor es algo o alguien fuera del Sistema que interactúa con el Sistema.

Un actor especifica un rol que alguna entidad externa adopta cuando interactúa con el sistema directamente. Puede representar un rol de usuario o un rol jugado por otro sistema o hardware que toca la frontera del sistema.

La siguiente es la lista de preguntas que permiten identificar a los actores que 

|  Actor | XXX (lector) |
|---|---|
| Descripción  | _Lector actor_  |
| Características  | _Le gusta los generos de fantasia y terror_ |
| Relaciones | _Hay grupos de lectura que se hacen en la biblioteca y se reunen los sabados._  |
| Referencias | _El delivery de libros que pide del stock, se mete en las ofertas y asiste a los grupos de lectura_ |   
|  Notas |  _Aparte de los generos le encanta enamorarse de lo que lee_ |
| Autor  | _lector_ |
|Fecha | _01-11-2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |




|  Actor | XXX (bibliotecario) |
|---|---|
| Descripción  | _bibliotecario actor_  |
| Características  | _Le gusta los generos de misterio y drama_ |
| Relaciones | _Organiza los grupos de lectura que se hacen en la biblioteca._  |
| Referencias | _Los libros que anexa revisa en el sistema de cual es el mas vendido_ |   
|  Notas |  _Le gusta los grupos de lectura_ |
| Autor  | _Bibliotecario_ |
|Fecha | _01-11-2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |







------


# **LOS CU(casos de uso):**

 Un **caso de uso** es una descripción de cómo un usuario (actor) interactúa con un sistema para lograr un objetivo específico. Define una secuencia de acciones que el sistema lleva a cabo para satisfacer una necesidad del usuario. Los casos de uso son fundamentales para comprender los requisitos y el comportamiento esperado de un sistema.



|  Caso de Uso	CU | lector  |
  |---|---|
  | Fuentes  | _ingresa al sistema_  |
  | Actor  |  _Actor lector_ |
  | Descripción | _interactua con el sistema y escoge a su gusto_  |
  | Flujo básico | _ busca libros para pedir_ |
  | Pre-condiciones | _Observa su valoracion_  |  
  | Post-condiciones  | _Si no es alta no lo compra_  |  
  |  Requerimientos | _tarjeta de credito_  |
  |  Notas |  _Comentarios: positivos y negativos de nuestros clientes_ |
  | Autor  | _lector_ |
  |Fecha | _01-11-2024_ |




  |  Caso de Uso	CU | bibliotecario  |
  |---|---|
  | Fuentes  | _Gestiona el sistema_  |
  | Actor  |  _Actor bibliotecario_ |
  | Descripción | _ingresa los nuevos registros _  |
  | Flujo básico | _Revisa el registro siempre y analisis y prueba, cuando se satura usa el crud._ |
  | Pre-condiciones | _analisis_  |  
  | Post-condiciones  | _prueba_  |  
  |  Requerimientos | _Registro a la plataforma,seleccion de producto mas confirmacion y el pago_  |
  |  Notas |  _Notas adicionales_ |
  | Autor  | _Bibliotecario_ |
  |Fecha | _01-11-2024_ |