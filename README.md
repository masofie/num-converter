# 🔢 Convertidor Numérico
<br>

- [🔢 Convertidor Numérico](#-convertidor-numérico)
  - [🔢 Números Representados en los ``4`` Sistemas](#-números-representados-en-los-4-sistemas)
  - [🔢 1. Conversión de Decimal a Binario (10 bits)](#-1-conversión-de-decimal-a-binario-10-bits)
  - [🔢 1.2 Conversión de Decimal a Octal](#-12-conversión-de-decimal-a-octal)

> Un repositorio para convertir números entre distintos sistemas numéricos

<br>

## 🔢 Números Representados en los ``4`` Sistemas
<br>

- **Bases:**
  - Binario
  - Decimal
  - Octal
  - Hexadecimal

- **🚀 Características:**
  - ✔️ Conversión rápida entre bases numéricas  
  - ✔️ Ejemplos claros de uso  
  - ✔️ Código modular y bien documentado  


- **🔍 Explicación de los colores:**
  - 🟦 Decimal → nuestro sistema habitual (base 10).
  - 🟧 Octal → base 8.
  - 🟥 Hexadecimal → base 16 (usando letras A–F).
  - 🟩 Binario → base 2 (solo ceros y unos).

<br>

| **🟦 Decimal** | **🟧 Octal** | **🟥 Hexadecimal** | **🟩 Binario**|
|------------|----------|----------------|---------------|
| 124        | 174      | 7C             | 1111100       |
| 500        | 764      | 1F4            | 111110100     |
| 256        | 400      | 100            | 100000000     |
| 400        | 620      | 190            | 110010000     |
| 158        | 236      | 9E             | 10011110      |
| 179        | 263      | B3             | 10110011      |
| 450        | 702      | 1C2            | 111000010     |
| 479        | 737      | 1DF            | 111011111     |
| 79         | 117      | 4F             | 1001111       |
| 91         | 133      | 5B             | 1011011       |
| 762        | 1362     | 2FA            | 1011111010    |
| 90         | 132      | 5A             | 1011010       |
| 398        | 616      | 18E            | 110001110     |
| 432        | 660      | 1B0            | 110110000     |
| 420        | 644      | 1A4            | 110100100     |

<br>

## 🔢 1. Conversión de Decimal a Binario (10 bits)
<br>

La fila superior muestra los **pesos** (potencias de 2). El bit ``1`` indica que el número contiene ese valor, y ``0`` que no lo contiene.

| Decimal | 512 | 256 | 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 | Binario     |
|---------|-----|-----|-----|----|----|----|---|---|---|---|-------------|
| 5       | 0   | 0   | 0   | 0  | 0  | 0  | 0 | 1 | 0 | 1 | 0000000101  |
| 19      | 0   | 0   | 0   | 0  | 0  | 1  | 0 | 0 | 1 | 1 | 0000010011  |
| 42      | 0   | 0   | 0   | 0  | 1  | 0  | 1 | 0 | 1 | 0 | 0000101010  |
| 85      | 0   | 0   | 0   | 1  | 0  | 1  | 0 | 1 | 0 | 1 | 0001010101  |
| 173     | 0   | 0   | 1   | 0  | 1  | 0  | 1 | 1 | 0 | 1 | 0010101101  |
| 255     | 0   | 0   | 1   | 1  | 1  | 1  | 1 | 1 | 1 | 1 | 0011111111  |
| 341     | 0   | 1   | 0   | 1  | 0  | 1  | 0 | 1 | 0 | 1 | 0101010101  |
| 512     | 1   | 0   | 0   | 0  | 0  | 0  | 0 | 0 | 0 | 0 | 1000000000  |

<br>


## 🔢 1.2 Conversión de Decimal a Octal
<br>

👉 El decimal es ``base 10`` porque usamos ``10 dígitos``. Cuando llegamos al 9, ya no tenemos más dígitos…

~~~~
0, 1, 2, 3, 4, 5, 6, 7, 8, 9
~~~~

👉 El octal es ``base 8`` porque solo tiene ``8 dígitos``. Cuando llegamos al 7, ya no hay más dígitos… 

~~~~
0, 1, 2, 3, 4, 5, 6, 7
~~~~

**🔹 Ejemplos fáciles**

| Decimal | Octal |
|---------|-------|
| 5       | 5     |
| 8       | 10    |
| 15      | 17    |
| 25      | 31    |
| 42      | 52    |
