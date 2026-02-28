# Laboratorio TDD - FizzBuzz

## Descripción

En este laboratorio se aplicó la metodología TDD (Test-Driven Development) para construir la función `fizzbuzz(int n)` en Java.

Se siguió el ciclo:

1. **Red**: escribir una prueba que falla.
2. **Green**: implementar el código mínimo para pasar la prueba.
3. **Refactor**: mejorar el código manteniendo todas las pruebas en verde.

## Objetivo

Implementar una función que retorne:

- El número como texto cuando no es múltiplo de 3 ni de 5.
- `Fizz` cuando el número es múltiplo de 3.
- `Buzz` cuando el número es múltiplo de 5.
- `FizzBuzz` cuando el número es múltiplo de 3 y 5.

## Trabajo realizado

### 1) Primera prueba

Se creó la prueba inicial para validar que el caso básico retorna el número:

- `fizzbuzz(1)` debe retornar `"1"`.

### 2) Implementación mínima

Se implementó la función `fizzbuzz(int n)` con el comportamiento mínimo para satisfacer la primera prueba.

### 3) Nuevas pruebas

Se agregaron pruebas para los casos principales:

- `fizzbuzz(3)` retorna `"Fizz"`.
- `fizzbuzz(5)` retorna `"Buzz"`.
- `fizzbuzz(15)` retorna `"FizzBuzz"`.

### 4) Ajuste de la lógica

Se actualizó la lógica de la función para cumplir todos los casos anteriores en este orden:

1. Múltiplo de 3 y 5.
2. Múltiplo de 3.
3. Múltiplo de 5.
4. Caso por defecto (número).

## Ejecución de pruebas

Comando usado:

```bash
mvn test
```

Resultado esperado: todas las pruebas deben pasar.

## Conclusión

El laboratorio cumple el enfoque TDD: primero se definieron pruebas, luego se implementó código mínimo, y finalmente se extendió la funcionalidad guiada por nuevas pruebas hasta cubrir todos los escenarios requeridos de FizzBuzz.
