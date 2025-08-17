# 🔢 Convertidor Numérico
<br>

- [🔢 Convertidor Numérico](#-convertidor-numérico)
  - [🔢 1. Conversión de Decimal a Binario (10 bits)](#-1-conversión-de-decimal-a-binario-10-bits)
  - [🔢 1.2 Conversión de Decimal a Octal](#-12-conversión-de-decimal-a-octal)

> Un repositorio para convertir números entre distintos sistemas numéricos

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

El sistema **octal (base 8)** usa los dígitos del ``0`` al ``7``.

| Decimal | Octal |
|---------|-------|
| 5       | 5     |
| 8       | 10    |
| 15      | 17    |
| 25      | 31    |
| 42      | 52    |
| 64      | 100   |
| 100     | 144   |
| 173     | 255   |
| 255     | 377   |
| 512     | 1000  |
