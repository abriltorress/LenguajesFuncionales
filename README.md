# Lenguajes Funcionales
### ¿Qué son?
Los lenguajes funcionales son una categoría de lenguajes de programación que se basan en el paradigma de programación funcional. Este paradigma se centra en la evaluación de funciones y evita el uso de estado mutable y efectos secundarios. En lugar de alterar datos y estados, los programas funcionales se construyen mediante la aplicación de funciones a valores y el encadenamiento de estas funciones.
## Caracteristicas claves
- Funciones como Ciudadanos de Primera Clase:
> Las funciones pueden ser asignadas a variables, pasadas como argumentos y retornadas como resultados de otras funciones.
- Inmutabilidad:
> Los datos son inmutables por defecto. En lugar de modificar los datos, se crean nuevas versiones de estos.
- Funciones Puras:
> Las funciones puras son aquellas que, dado un mismo conjunto de entradas, siempre retornan el mismo resultado y no tienen efectos secundarios (como modificar una variable global o realizar operaciones de entrada/salida).
-Composición de Funciones:
> Las funciones se pueden combinar o componer para formar nuevas funciones. Esto permite construir soluciones complejas a partir de funciones más simples.
-Expresiones y Evaluación:
> Los lenguajes funcionales suelen usar expresiones en lugar de declaraciones. Cada construcción en el lenguaje es una expresión que devuelve un valor.
- Recursión:
> Dado que los lenguajes funcionales evitan el uso de bucles imperativos (como for o while), la recursión es una técnica común para iterar o repetir procesos.
- Evaluación Perezosa (Lazy Evaluation):
> Algunos lenguajes funcionales usan evaluación perezosa, donde las expresiones no se evalúan hasta que se necesitan. Esto puede mejorar la eficiencia y permitir el uso de estructuras de datos infinitas.
## Ejemplos de Lenguajes funcionales:
- Haskell:
> Es un lenguaje funcional puro, lo que significa que todo en Haskell es una función y no hay efectos secundarios.
- Erlang:
> Diseñado para sistemas concurrentes y distribuidos, con un fuerte enfoque en la programación funcional.
- Scala:
> Aunque es un lenguaje híbrido (funcional y orientado a objetos), ofrece muchas características funcionales y se puede usar para programación funcional.
- F#:
> Un lenguaje funcional que se ejecuta en la plataforma .NET y proporciona características tanto funcionales como orientadas a objetos.
- Elixir:
> Un lenguaje funcional que se ejecuta sobre la máquina virtual de Erlang, conocido por su soporte para la concurrencia y la distribución.
## Ejemplo basico de un Lenguaje funcional:
*un ejemplo simple en Haskell para ilustrar*
~~~
-- Definición de una función pura que calcula el factorial de un número
factorial :: Int -> Int
factorial 0 = 1
factorial n = n * factorial (n - 1)

-- Uso de la función
main = print (factorial 5)  -- Salida: 120
~~~
