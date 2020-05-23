# Banda en Flask 

Lindsey Katherine Camargo Beltrán - 20172020037

Edwin Alejandro Fiesco Parra - 20182020108

## El Principio de responsabilidad única 

Está presente en el ejercicio puesto que cada clase debe realizar únicamente un trabajo, separando así qué funcionalidades tiene que cumplir cada clase y que en caso de requerir modificaciones sólo se tenga que modificar una única cosa y esta se pueda encontrar con facilidad.

Instrumento: Define que función puede realizar cada instrumento

Musico: Realiza la acción que permite cada instrumento

Banda: Crea el musico con su instrumento

## El principio de sustitución de Liskov

Está presente en el ejercicio ya que cuando heredamos métodos de una clase padre, podemos utilizar cualquiera de las clases hijas en el programa y esto no afectará el comportamiento de la clase padre.

En el ejercicio vemos que varios instrumentos heredan de la clase Instrumento, sin embargo, Instrumento nunca es modificada, sino que cada nuevo instrumento que heredó de su clase padre crea su propio comportamiento.

## El principio de segregación de interfaces 

Se cumple ya que ninguna clase debe hereda métodos que no usa. Por tanto, cuando creemos la clase abstracta Instrumento con sus comportamientos, todas las clases que implementen esta clase (Es decir los cada uno de los instrumentos definidos) necesitan y son capaces de agregar comportamientos a todos los métodos. 

## UML
