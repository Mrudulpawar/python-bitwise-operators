# python-bitwise-operators

This project demonstrates the use of **Bitwise Operators in Python** using simple examples and binary representations.

The practical work is performed in a Jupyter Notebook (`.ipynb`) and explains the basic working of different bitwise operators.

## 📌 Operators Covered

| Operator | Name        | Example    |   Output |     |
| -------- | ----------- | ---------- | -------: | --- |
| `&`      | Bitwise AND | `5 & 3`    |      `1` |     |
| `        | `           | Bitwise OR | `5 \| 3` | `7` |
| `^`      | Bitwise XOR | `5 ^ 3`    |      `6` |     |
| `~`      | Bitwise NOT | `~5`       |     `-6` |     |
| `<<`     | Left Shift  | `5 << 2`   |     `20` |     |
| `>>`     | Right Shift | `5 >> 2`   |      `1` |     |

## 🔹 Bitwise AND (`&`)

```python
print(5 & 3)
```

Binary representation:

```text
5 = 0101
3 = 0011
    ----
    0001
```

Output:

```text
1
```

## 🔹 Bitwise OR (`|`)

```python
print(5 | 3)
```

Binary representation:

```text
5 = 0101
3 = 0011
    ----
    0111
```

Output:

```text
7
```

## 🔹 Bitwise XOR (`^`)

```python
print(5 ^ 3)
```

Binary representation:

```text
5 = 0101
3 = 0011
    ----
    0110
```

Output:

```text
6
```

## 🔹 Bitwise NOT (`~`)

```python
print(~5)
```

Output:

```text
-6
```

The notebook also explains the binary representation and the use of **1's complement and 2's complement** to understand the negative result.

```text
5  = 0000 0101
~5 = 1111 1010
```

The most significant bit (MSB) is `1`, indicating a negative value in the signed representation being demonstrated.

## 🔹 Left Shift (`<<`)

```python
print(5 << 2)
```

Formula:

```text
number × 2^shift
```

Calculation:

```text
5 × 2^2 = 20
```

Output:

```text
20
```

## 🔹 Right Shift (`>>`)

```python
print(5 >> 2)
```

Formula:

```text
number // 2^shift
```

Calculation:

```text
5 // 2^2 = 1
```

Output:

```text
1
```

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* VS Code
* Bitwise Operators

## 📂 Project File

The main practical file is:

```text
bitwise_operators.ipynb
```

It contains the Python programs, outputs, binary calculations, and explanations of the bitwise operators.

## 🎯 Learning Objectives

Through this project, I practiced:

* Understanding bitwise operators in Python
* Working with binary numbers
* Performing AND, OR and XOR operations
* Understanding the Bitwise NOT operator
* Understanding MSB
* Understanding 1's complement and 2's complement
* Performing left and right shift operations
* Applying formulas for shift operators

## 👨‍💻 Author

**Mrudul Pawar**

B.Sc. Computer Science

