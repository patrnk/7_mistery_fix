# Quadratic Equations Solver

A small module that enables you to solve quadratic equations with real roots automatically.

# How to Use

Import `quadratic_equation` module and use `get_roots` function:
```
$ python3
>>> from quadratic_equation import get_roots
>>> get_roots(1, 2, -3)
(-3.0, 1.0)
>>>
```

The function returns a tuple of real roots. The first root in the tuple is always less than the second. If the equation has only one real root, the second root in the tuple is None. If the equation has no real roots, `(None, None)` is returned.

# How to Launch Tests

```bash
python tests.py
```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
