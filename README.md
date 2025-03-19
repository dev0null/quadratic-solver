# Description
Shell script utility that solve quadratic equations by using the quadratic formula inside the **Real numbers set** (no complex roots).

$$
x = \frac{-b ± \sqrt{b^2 - 4ac}}{2a}
$$

It returns results based on the 𝚫(delta) value:
- $\boldsymbol{𝚫 > 0}$: 2 unique solutions
- $\boldsymbol{𝚫 < 0}$: no real root solution
- $\boldsymbol{𝚫 = 0}$: 1 solution (1 repeated real root)

## Installation

[![GitHub](https://img.shields.io/badge/Clone_on-GitHub-blue?logo=github)](https://github.com/dev0null/quadratic-solver.git)
[![Codeberg](https://img.shields.io/badge/Clone_on-Codeberg-orange?logo=codeberg)](https://codeberg.org/dev0null/quadratic-solver.git)


Clone this repository from **GitHub**:
```sh
git clone https://github.com/dev0null/quadratic-solver.git
```
Clone this repository from **Codeberg**: 
```sh
git clone https://codeberg.org/dev0null/quadratic-solver.git
```

Make it executable:

```sh
chmod +x quadratic-solver
```

Run it:

```sh
./quadratic-solver
```
---
## Equation formatting rules
To make the equation solver work, the equation must adhere to the following rules:

1. the equation must be submitted in the **standard form**: $\mathbf{ax^2 + bx + c}$

2. the coefficients MUST be **explicit** when equal to 1:
    - $x^2 + x + 5 = 0$, should be written as $\mathbf1x^2 + \mathbf1x + 5 = 0$

3. the '$\mathbf a$' coefficient or leading coefficient MUST be a **non-zero** value

4. the right member MUST be 0 and CAN be omitted:
    - $2x^2 + 9x + 5 = 0\quad \text{or} \quad2x^2 + 9x + 5$ 

Example of some correct inputs:
```sh
# Without spaces and right with member
$ Type the equation here: 2x^2-5x+4=0

# With spaces, no right member
$ Type the equation here: -2k^2 - 5k + 4
```