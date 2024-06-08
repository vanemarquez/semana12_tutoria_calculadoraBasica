# Calculadora Básica

Esta es una calculadora básica desarrollada utilizando HTML, CSS y JavaScript. 

## Funcionalidades

La calculadora tiene las siguientes funcionalidades:

1.	***Operaciones Aritméticas:*** Puedes realizar operaciones básicas como suma `` (+)``, resta ``(-)``, multiplicación ``(*)`` y división ``(/)``.
2.	***Borrar Display:*** El botón ``AC ``limpia el contenido del display.
3.	***Borrar Último Carácter:*** El botón ``DE`` (Delete) elimina el último carácter del contenido del display.
4.	***Evaluación de Expresiones:*** Al presionar el botón igual ``(=)``, la calculadora evaluará la expresión matemática mostrada en el display y mostrará el resultado


## Métodos Utilizados

**1. document.querySelector()**

- Se utilizó para seleccionar el elemento con el id "display" para acceder y modificar su contenido.

**2. document.querySelectorAll()**
-	Se usó para seleccionar todos los elementos ``button``en el documento para asignarles un evento de click.

**3. addEventListener()**
-	Se utilizó para escuchar los clicks en los botones y ejecutar la lógica correspondiente según el botón presionado.

**4. eval()**
-	Se usó para evaluar la expresión matemática mostrada en el display y mostrar el resultado.

**5. slice()**
-	Se utilizó  para eliminar el último carácter del contenido del display al presionar el botón DE.



