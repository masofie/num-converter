# 🔢 Conversor de Sistemas Numéricos
<br>

- [🔢 Conversor de Sistemas Numéricos](#-conversor-de-sistemas-numéricos)
  - [🔢 Números Representados en los ``4`` Sistemas](#-números-representados-en-los-4-sistemas)
  - [🔢 1. Conversión de Decimal a Binario (10 bits)](#-1-conversión-de-decimal-a-binario-10-bits)
  - [🔢 1.2 Conversión de Decimal a Octal](#-12-conversión-de-decimal-a-octal)
  - [🔢 1.3 Conversión de Octal a Decimal](#-13-conversión-de-octal-a-decimal)
  - [🔢 1.4 Conversión de Octal a Hexadecimal](#-14-conversión-de-octal-a-hexadecimal)

> Repositorio dedicado a la conversión de números entre distintos sistemas numéricos.

<br>

## 🔢 Números Representados en los ``4`` Sistemas
<br>


- **🔍 Interpretación de los colores:**
  
  - 🟦 Decimal → sistema de numeración habitual ``base 10``.
  - 🟧 Octal → se usa ``base 8``.
  - 🟥 Hexadecimal → base 16 ``usando letras A–F``.
  - 🟩 Binario → base 2 ``solo ceros y unos``.

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

La fila superior muestra los **pesos** (potencias de 2). El bit `1` indica que se utiliza ese valor en la representación del número, mientras que `0` indica que no se utiliza.

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

👉 El decimal es ``base 10`` porque usamos ``10 dígitos``. Después del 9 se produce un acarreo a la siguiente posición.

~~~~
0, 1, 2, 3, 4, 5, 6, 7, 8, 9
~~~~

👉 El octal es ``base 8`` porque solo tiene ``8 dígitos``. Después del 7 se produce un acarreo a la siguiente posición.

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

<br>

## 🔢 1.3 Conversión de Octal a Decimal
<br>

**🔹 Explicación simple**

- El sistema octal es base 8.
- Cada posición vale una potencia de 8 (igual que en decimal cada posición vale una potencia de 10).

**👉 Ejemplo:**
  - En decimal 345 = ``(3×100) + (4×10) + (5×1)``
  - En octal 345₈ = ``(3×8²) + (4×8¹) + (5×8⁰)``

<br>

**🔹 Ejemplos fáciles**

|**🟧 Octal**| **🟦 Decimal** | **Explicación**                    |
|------------ |----------------|------------------------------------|
| 7           | 7              | 7 = (7×8⁰)                         |
| 10          | 8              | (1×8¹) + (0×8⁰) = 8                |
| 17          | 15             | (1×8¹) + (7×8⁰) = 8+7              |
| 31          | 25             | (3×8¹) + (1×8⁰) = 24+1             |
| 52          | 42             | (5×8¹) + (2×8⁰) = 40+2             |
| 144         | 100            | (1×8²) + (4×8¹) + (4×8⁰) = 64+32+4 |

<br>

## 🔢 1.4 Conversión de Octal a Hexadecimal
<br>

La conversión de `octal` ↔ `hexadecimal` se hace siempre pasando primero por binario, porque:

- Cada dígito ``octal (0–7)`` se representa con ``3 bits`` en binario.
- Cada dígito ``hexadecimal (0–F)`` se representa con ``4 bits`` en binario.

Así, puedes convertir ``Octal → Binario → Hexadecimal`` (y viceversa).

<br>

**🔹 Explicación**

👉 Ejemplo con octal ``236₈`` → hexadecimal

1. Escribir cada dígito octal en 3 bits binarios:

   - 2 = 010
   - 3 = 011
   - 6 = 110
   - → 236₈ = ``010 011 110 (binario)``

2. Agrupar en bloques de ``4 bits`` (para pasar a hexadecimal):
  
   - 0100 1110
  
3. Pasar cada bloque a Hex:

   - 0100 = 4
   - 1110 = E

✅ Resultado: 236₈ = ``4E₁₆``