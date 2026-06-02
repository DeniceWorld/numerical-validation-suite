# Numerical Validation Suite

A Python project validating mathematical and physics computations
using NumPy, SciPy, and Pandas against known analytical solutions.

Built to demonstrate numerical validation skills for AI evaluation
and scientific computing roles.

## What's Inside

| Test | Method | Result |
|------|--------|--------|
| Projectile Motion | NumPy simulation | <0.0001% error |
| Statistical Distribution | SciPy normaltest() | p=0.847 → PASS |
| Numerical Integration | SciPy quad() | 2.84e-14 error |
| Root Finding | SciPy brentq() | -8.88e-16 error |

## Libraries Used

- Python 3.14
- NumPy 2.4.6
- SciPy 1.17.1
- Pandas 3.0.3
- Matplotlib 3.10.9

## How to Run

```bash
pip install numpy scipy pandas matplotlib notebook
jupyter notebook numerical_validation_suite.ipynb
```

## Author

Denice Lutorila Woolford  
denicelutorila@gmail.com