### Computing Riemann Integral

This is a simple Python implementation of the Riemann Integral using first principles.

### Example:

```python
obj = riemann_integral('x^2', 0, 1)
obj.integral_value()
```
### Output:
```python
Upper sum U(f, 500) = 0.334334
Lower sum L(f, 500) = 0.332334
Integral is: 0.333334
```
In the example, `n=500` where `n` is the number of partition points.