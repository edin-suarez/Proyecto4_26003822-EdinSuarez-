# Cotizador Automático de Seguros – TK-U

## Descripción general
Este proyecto consiste en el desarrollo de un cotizador automático para la
empresa de seguros TK-U, ubicada en la ciudad de Jedha. El objetivo principal
es automatizar el proceso de cotización que anteriormente se realizaba de
forma manual, lo cual generaba retrasos y una baja cantidad de cotizaciones
diarias.

El programa permite realizar múltiples cotizaciones de manera continua,
aplicando recargos según las características del asegurado, hasta que el
usuario decida salir del sistema.

---

## Funcionamiento del programa
El programa solicita los datos del asegurado mediante ventanas de entrada
(prompt) y calcula el precio final del seguro a partir de un precio base.
Durante la ejecución se pueden realizar tantas cotizaciones como se desee,
hasta que el usuario ingrese la palabra “Salir”.

El cálculo final se obtiene sumando todos los recargos aplicables al precio
base del seguro.

---

## Aspectos del problema que se consideran
Para realizar la cotización, el programa toma en cuenta los siguientes puntos:

- El asegurado debe ser mayor de edad.
- Recargo según la edad del asegurado.
- Recargo según el estado civil y la edad del cónyuge.
- Recargo según la cantidad de hijos.
- Recargo adicional según la cantidad de propiedades.
- Recargo adicional basado en el salario del asegurado.
- Control del flujo del programa para permitir múltiples cotizaciones.

---

## Posibles mejoras
Algunas mejoras que se podrían implementar en el futuro son:

- Validaciones más estrictas de los datos ingresados por el usuario.
- Uso de una interfaz gráfica en lugar de ventanas emergentes.
- Almacenamiento de las cotizaciones realizadas.
- Optimización del código utilizando funciones reutilizables.
- Implementación del programa en una aplicación web completa.

---

## Archivos incluidos
- `descripcion_problema.txt`: Explicación del problema en palabras propias.
- `algoritmo.txt`: Algoritmo paso a paso del procedimiento.
- `proyecto.js`: Código fuente del cotizador automático.
