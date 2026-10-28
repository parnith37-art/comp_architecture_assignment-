# Computer Architecture Assignment

**Course:** Computer Architecture  
**Topic:** Problem Solving – Group 1

## Question 1: 8-bit 2's Complement Arithmetic

**File:** `2's_complement.py`

This program performs signed integer addition using 8-bit 2's complement representation.

### (a) (+20) + (+15)

```text
  00010100
+ 00001111
----------
  00100011 = +35
```

Overflow: No

### (b) (-20) + (-15)

```text
  11101100
+ 11110001
----------
1 11011101
```

Discard the carry beyond 8 bits.

Result: `11011101` = -35

Overflow: No

## Question 2: Floating-Point Subtraction

**File:** `floating_point.py`

Calculate 1.5 - 0.25 using binary representation.

```text
1.5  = 1.10₂
0.25 = 0.01₂

  1.10
- 0.01
------
  1.01₂
```

**Binary result:** `1.01₂`  
**Decimal result:** 1.25

## Technologies Used

- Python 3
- Binary arithmetic
- 8-bit 2's complement representation

## Conclusion

Both programs demonstrate binary arithmetic concepts used in Computer Architecture.
