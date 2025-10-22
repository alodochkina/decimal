# decimal

Implementation of conversion functions between a binary Decimal representation and C integral/float types.

## Features
- Convert int -> decimal, float -> decimal, decimal -> int, decimal -> float.
- Unit tests using Check.
- CI workflow with style, tests and coverage.

## Implemented functions
- [`s21_from_int_to_decimal`](s21_from_int_to_decimal.c)
- [`s21_from_float_to_decimal`](s21_from_float_to_decimal.c)
- [`s21_from_decimal_to_int`](s21_from_decimal_to_int.c)
- [`s21_from_decimal_to_float`](s21_from_decimal_to_float.c)

Decimal type definition: see [`s21_decimal.h`](s21_decimal.h).

## Build
Use the included Makefile:

```sh
make s21_decimal.a
```
