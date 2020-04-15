# Manejo-de-colecciones-en-JAVA
Resumen sobre las colecciones de Java

# ¿Que es una colección en Java?
Se puede decir que las colecciones en Java en un contenedor de elementos de un solo tipo, en el cual podemos recoger varios objetos. Estos suelen ser del mismo tipo, se podría decir que tienen un padre en común.

# Su uso:
El poder almacenar, recuperar y manipular datos de una manera conjunta.
Suelen representar elementos que forman grupos naturales tanto en la realidad como en el mundo del software.
Estas colecciones nos van a ayudar a tratar problemas del mundo real.

**En java** las colecciones están disponibles desde la versión 2, recojidas en el paquete **java.util**.
A lo largo de las diferentes versiones, estas colecciones han tenido variaciones y novedades.

Los **Frameworks** de colecciones de java nos ofrecen una serie de elementos:
- Interfaces
- Implementaciones
- Algoritmos

# Tipos de colecciones 

### Iterable
```
Iterable<E>

```
Comenzando por la raíz nos remite al concepto de iterador, un iterador es un patrón de diseño que nos permite de alguna manera recorrer una sucesión o colección de elemetos.

Nos permite usar forEach y el bucle for-each.

### Set

```
Set<E>

```
Es un tipo de colección muy concreta que no permite elementos duplicados ya que es una abstracción del conjunto matemático de conjunto y tampoco nos permite el acceso posicional.

-Set<E>- tiene 3 implementaciones:
- HashSet<E>
- LinkedHashSet<E>
- TreeSet<E>  
  
### List 
```
List<E>

```
Se trata de un tipo de colección que si permite duplicados.
Añade a las funcionalidades de -Collection<E>-:
  - Acceso posicional
  - Búsqueda
  - Iteracion extendida
  - Operaciones sobre un rango de elementos de lista.
  
 Implementaciones de -List<E>-:
  
```
ArrayList<E>
Queue<E>
Deque<E>

```
### Map
```
Map<K,V>

```
Esta colección no hereda de _Collection<E>_
  - Maneja pares clave, valor. 
  - Para cada clave hay un solo valor 
  - Cada clave puede existir una sola vez en el -Map-
  - Podíamos tener una clave nula y multiples valore nulos

Es conocida como diccionario y al igual que las colecciones anteriores no permiten almacenar tipos primitivos, tendríamos que usar los tipos envoltorios en su lugar.

### Colecciones para situaciones especiales

Java también nos ofrece colecciones para situaciones especiales como las **colecciones no modificables** estas son colecciones que una vez creadas no se pueden modificar.

También están las **colecciones sincronizadas** aptas para un contexto multihilo, es una versión sincronizada de una colección no sincronizada.

#### Otras implementaciones menos usadadas

En el caso de _Set<E>_ tenemos:
  - EnumSet
  - CopyOnWriteArraySet_
  
En Map<E>:
  - IdentityHashMap
  
#### Algoritmos disponibles en la clase Collections:

  - Ordenar y desordenar
  - Búsqueda
  - Operaciones: max/min, la frecuencia...

  
  
  
  
  
  

