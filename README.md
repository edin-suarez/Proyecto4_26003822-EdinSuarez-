# Cotizador Automático de Seguros – TK-U

## Descripción del proyecto
Este proyecto consiste en el desarrollo de un cotizador automático para la
empresa de seguros TK-U, ubicada en la ciudad de Jedha. El objetivo principal
es automatizar el proceso de cotización, el cual anteriormente se realizaba de
forma manual, provocando retrasos, pérdida de tiempo y una cantidad limitada
de cotizaciones diarias.

El programa fue desarrollado en JavaScript y permite calcular el precio final
de un seguro a partir de un precio base, aplicando distintos recargos según
las características del asegurado.

---

## Funcionamiento del programa
El programa solicita los datos del asegurado mediante entradas de texto y
realiza los cálculos correspondientes para obtener el precio final de la
cotización.

El sistema permite realizar múltiples cotizaciones de forma continua hasta
que el usuario ingrese la palabra **“Salir”**, momento en el cual el programa
finaliza su ejecución.

Cada cotización se calcula sumando al precio base los recargos que aplican
según las condiciones ingresadas por el usuario.

---

## Aspectos del problema que se consideran
Para el cálculo de la cotización, el programa toma en cuenta los siguientes
factores:

- El asegurado debe ser mayor de edad.
- Recargo según la edad del asegurado.
- Recargo según el estado civil y la edad del cónyuge.
- Recargo por la cantidad de hijos.
- Recargo adicional por la cantidad de propiedades del asegurado.
- Recargo adicional basado en el salario del asegurado.
- Control del flujo del programa para permitir varias cotizaciones en una
  sola ejecución.

Todos los recargos se calculan de acuerdo con los porcentajes definidos en los
requerimientos del problema.

---

## Posibles mejoras del programa
Algunas mejoras que podrían implementarse en el futuro son:

- Validar mejor los datos ingresados para evitar errores de usuario.
- Separar el código en funciones para mejorar la legibilidad y reutilización.
- Implementar una interfaz gráfica en lugar de usar ventanas emergentes.
- Guardar el historial de cotizaciones realizadas.
- Adaptar el programa para su uso en una aplicación web o móvil.

---

## Contenido del repositorio
El repositorio contiene los siguientes archivos:

- Un archivo de texto con la descripción del problema.
- Un archivo de texto con el algoritmo del procedimiento.
- El archivo `proyecto.js` con la solución implementada en JavaScript.
