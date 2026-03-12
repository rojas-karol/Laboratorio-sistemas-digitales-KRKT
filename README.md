# Laboratorio-sistemas-digitales-KRKT
Repositorio con el paso a paso del laboratorio en clase de sistemas digitales 
---
---
---
# Laboratorio 1 - Sistemas Digitales
Fundación Universitaria Compensar

Estudiantes:

Karol Vanessa Rojas Gil

Kevin Alejandro Tacha Herrera

---

## Introducción

En este laboratorio se desarrolló un circuito digital con el objetivo de comprender el funcionamiento de compuertas lógicas y circuitos integrados.

Se implementó un circuito para generar una onda cuadrada de 2 segundos y se realizaron pruebas con compuertas lógicas utilizando circuitos integrados de la serie 74HC.

---

## Objetivo del laboratorio

Reconocer el funcionamiento de diferentes compuertas lógicas y analizar su comportamiento dentro de un circuito digital.

---

## Materiales utilizados

- Circuito integrado 74HC04
- Circuito integrado 74HC02
- Protoboard
- Bateria 9V
- LM 7806
- TL 555
- Bombillos LED
- Resistencias
- Capacitores
- Cables de conexión
- Fuente de alimentación
  

  <table>
<tr>
<td align="center">

<img src="imagenes/materiales2.jpeg" width="500"><br>

</td>

<td align="center">

<img src="imagenes/materiales3.jpeg" width="500"><br>

</td>
</tr>
</table>


---

## Paso a paso del laboratorio

### Paso 1: Análisis del circuito

Primero se analizó el circuito necesario para generar una onda cuadrada de 2 segundos.

Se identificaron los componentes necesarios para controlar el tiempo de oscilación.

---

### Paso 2: Cálculo de los componentes

Se calcularon los valores de resistencias y capacitores necesarios para generar el tiempo de 2 segundos en la señal.

---

### Paso 3: Montaje del circuito

Se realizó el montaje del circuito en una protoboard conectando:

- El circuito integrado
- Resistencias
- Capacitores
- Alimentación

---

### Paso 4: Pruebas del circuito

Se realizaron pruebas para verificar:

- Funcionamiento de la onda cuadrada
- Comportamiento de las compuertas lógicas
- Tiempo de la señal

---

### Compuerta AND – Integrado 74HC08

<p align="center">
  <img src="imagenes/compuerta_and.png" width="500">
</p>

Pasos de Montaje:

1. Se conectó la fuente de alimentación de 5V a los rieles positivo y negativo de la protoboard.
2. Se colocó el circuito integrado 74HC08 en el centro de la protoboard para separar las dos mitades del circuito.
3. Se conectó el pin de alimentación del integrado al riel positivo y el pin de tierra al riel negativo.
4. Se utilizó un módulo de interruptores DIP para representar las entradas lógicas A y B.
5. Las salidas de los interruptores se conectaron a las entradas de la compuerta AND.
6. La salida de la compuerta se conectó a un LED para visualizar el resultado lógico.
7. Se agregó una resistencia en serie con el LED para limitar la corriente.
8. Se realizaron pruebas activando diferentes combinaciones de los interruptores para verificar el comportamiento de la compuerta.

<p align="center">
  <img src="imagenes/logica_and.png" width="500">
</p>

### Compuerta OR - Integrado 74HC32

<p align="center">
<img src="imagenes/compuerta_or.png" width="500">
</p>

Pasos de Montajee:

1. Se conectó la fuente de alimentación a la protoboard.
2. Se colocó el circuito integrado 74HC32 en la protoboard.
3. Se conectaron los pines de alimentación del integrado a los rieles de voltaje.
4. Se configuraron dos interruptores del DIP switch como entradas lógicas.
5. Cada interruptor se conectó a una de las entradas de la compuerta OR.
6. La salida de la compuerta se conectó a un LED indicador.
7. Se añadió una resistencia limitadora entre el LED y tierra.
8. Se probaron diferentes combinaciones de entrada para comprobar el funcionamiento de la compuerta OR.

<p align="center">
  <img src="imagenes/Logica_or.png" width="500">
</p>

### Compuerta NOT - Integrado 74HC04

<p align="center">
<img src="imagenes/compuerta_not.png" width="500">
</p>

---

## Resultados

El circuito logró generar una señal cuadrada con el tiempo esperado y permitió observar el comportamiento de las compuertas lógicas estudiadas.

---

## Conclusiones

El laboratorio permitió comprender el funcionamiento de los circuitos digitales y la aplicación de compuertas lógicas en la generación de señales.

---
---
---
