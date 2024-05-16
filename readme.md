# JAVASCRIPT

## OBJETOS

1. creacion de objetos: Se crea con let / const el nombre del valor y { y dentro la clave y valor}

2. acceder a los valores: Se accede mediante el . es decir pones el nombre del objeto, seguido del . y luego el valor al que quieres acceder

3. agregar valores: Sería de la misma manera solo que se agrega el = y el valor que quieres añadir

4. modificar valor:  Igual que el paso 3

5. eliminar valores: Segria poner delete y luego el objeto.clave que quieres borrar

6. congelar: Object.freeze() y dentro del parentecis el objeto que quieres congelar, con eso ya no puedes eliminar ni modificar valores

7. sellar: Object.seaal() y dentro del parentecis el objeto que quieres sellar, con eso ya no puedes eliminar pero si puedes modificar valores

8. unir objetos: Se puede hacer de dos maneras
usando object.asign() y dentro de los aprentesis pones los dos objetos seguidos de una coma.

9. palabra reservada this en objeto literal: E cuando dentro de un objeto hay una función y usas la palabra reservada this, hará referencia al objeto

10. recorrer: se puede hacer  con Object.keys para obtener un array de las claves del objeto, tambien usando Ibject.values para los valores del objeto y Object.Entries para obtener un array de un array de clave valor

## Arrays
1. Mutables: cuando tienes un array puedes llamar funciones que permiten modificar su estructura inicial como pop push 

2. Inmutable: Cuando se clona el array y se hace un pop o push a ese nuevo array, no se va a afectar al array que clonaste, solo afecta al nuevo array

## FUNCIONES

1. Funcion declarativa aquellas que se llaman con function y son aquellas que cumplen con hoisting porque optienen prioridad y pasa a declararse al inicio antes de compilar

2. Funcion expresion es aquella que se asigna a un valor y no cumple con hoisting pues si se llama a esa función antes de declararla, saldrá un error
