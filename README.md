# 🧪 Kata FizzBuzz - TDD en Java

## 📌 Descripción

Este proyecto implementa la clásica Kata FizzBuzz aplicando la metodología **TDD (Test Driven Development)** en Java utilizando JUnit 5.

La función debe cumplir las siguientes reglas:

- Si el número es múltiplo de 3 → devolver "Fizz"
- Si el número es múltiplo de 5 → devolver "Buzz"
- Si el número es múltiplo de 3 y 5 → devolver "FizzBuzz"
- Si no cumple ninguna condición anterior → devolver el número como texto

---

# 📂 Estructura del Proyecto

```
FizzBuzzTDD/
│
├── pom.xml
├── README.md
│
└── src/
    ├── main/java/
    │   ├── FizzBuzz.java
    │   └── Main.java
    │
    └── test/java/
        └── FizzBuzzTest.java
       
       ---

# ⚙️ Implementación

## Clase FizzBuzz

Contiene el método:

```java
public String convert(int number);
```

Este método aplica las reglas de negocio siguiendo el orden correcto:

1. Primero verifica múltiplos de 3 y 5.
2. Después múltiplos de 3.
3. Después múltiplos de 5.
4. Finalmente devuelve el número como String.

---

## Clase Main

Permite ejecutar la aplicación mostrando por consola los números del 1 al 15 transformados según las reglas.

Resultado esperado en consola:

```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```

---

# 🧪 Desarrollo de Tests (TDD Paso a Paso)

Se aplicó el ciclo de TDD:

1. 🔴 Escribir un test que falle
2. 🟢 Implementar el código mínimo para hacerlo pasar
3. 🔵 Refactorizar manteniendo los tests en verde
4. Repetir el proceso

## Orden de creación de los tests

### 1️⃣ check_1_to_1

Verifica que el número 1 devuelve "1".

```java
@Test
public void check_1_to_1() {
    assertEquals("1", new FizzBuzz().convert(1));
}
```

---

### 2️⃣ check_2_to_2

Verifica que el número 2 devuelve "2".

```java
@Test
public void check_2_to_2() {
    assertEquals("2", new FizzBuzz().convert(2));
}
---

# ⚙️ Implementación

## Clase FizzBuzz

Contiene el método:

```java
public String convert(int number);
```

Este método aplica las reglas de negocio siguiendo el orden correcto:

1. Primero verifica múltiplos de 3 y 5.
2. Después múltiplos de 3.
3. Después múltiplos de 5.
4. Finalmente devuelve el número como String.

---

## Clase Main

Permite ejecutar la aplicación mostrando por consola los números del 1 al 15 transformados según las reglas.

Resultado esperado en consola:

```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```

---

# 🧪 Desarrollo de Tests (TDD Paso a Paso)

Se aplicó el ciclo de TDD:

1. 🔴 Escribir un test que falle
2. 🟢 Implementar el código mínimo para hacerlo pasar
3. 🔵 Refactorizar manteniendo los tests en verde
4. Repetir el proceso

## Orden de creación de los tests

### 1️⃣ check_1_to_1

Verifica que el número 1 devuelve "1".

```java
@Test
public void check_1_to_1() {
    assertEquals("1", new FizzBuzz().convert(1));
}
```

---

### 2️⃣ check_2_to_2

Verifica que el número 2 devuelve "2".

```java
@Test
public void check_2_to_2() {
    assertEquals("2", new FizzBuzz().convert(2));
}



```
![Captura de pantalla 2026-03-04 094916.png](src/Captura%20de%20pantalla%202026-03-04%20094916.png)

```