# 📌 Fundamentals of Functions

A function is a fundamental mathematical concept that establishes a relationship between inputs and outputs. Understanding functions is crucial for various fields, including algebra, calculus, and real analysis.

## 📖 Definition of a Function
A function $f$ is a rule that assigns each element from a set called the **domain** to exactly one element in another set called the **codomain**.

In mathematical notation, a function is written as:

\
f: D_f \to R_fn 
\

where:
- $D_f$ represents the **domain** (the set of all possible input values)
- $R_f$ represents the **range** (the set of all actual output values)

For a function $f$, if $x$ is an element of its domain, then the corresponding output is denoted as $f(x)$.

## 🔹 Properties of a Function
- Each input has **exactly one** output.
- Different inputs can have the same output.

### Example:
Let $f(x) = x^2$. If we evaluate:
- $f(2) = 4$
- $f(-2) = 4$

Even though different inputs (2 and -2) produce the same output (4), the function remains valid because each input maps to a single value.

---

## 📌 Determining the Domain
The **domain** of a function consists of all input values that do not violate mathematical constraints. To determine the domain:
1. **Avoid division by zero:** If a function has a denominator, ensure it is not zero.
2. **Ensure valid square roots:** The expression inside a square root must be non-negative in real numbers.
3. **Consider logarithms:** The argument inside a logarithm must be positive.

### Example:
For the function $f(x) = \frac{1}{x - 3}$:
- The denominator must not be zero: $x - 3 \neq 0$.
- Thus, the domain is $x \neq 3$ or $(-\infty, 3) \cup (3, \infty)$.

---

## 📌 Determining the Range
The **range** of a function consists of all possible output values. To determine the range:
1. Solve for $x$ in terms of $y$: Express $x$ as a function of $y$ and find constraints.
2. Analyze the function graph: Graphing the function helps visualize possible outputs.

### Example:
For $f(x) = x^2$:
- The function always produces non-negative outputs.
- The range is $[0, \infty)$.

---

## 📌 Characteristics of Functions
### 🔹 Odd Functions
A function $f(x)$ is **odd** if:
\[
f(-x) = -f(x)
\]

Example: $f(x) = x^3$ satisfies $(-x)^3 = -x^3$.

### 🔹 Even Functions
A function $f(x)$ is **even** if:
\[
f(-x) = f(x)
\]

Example: $f(x) = x^2$ satisfies $(-x)^2 = x^2$.

### 🔹 Neither Odd nor Even
If neither condition is satisfied, the function is neither odd nor even. (Circle Function)

### 🔹 Periodic Functions
A function is **periodic** if there exists a number $T > 0$ such that:
\[
f(x + T) = f(x)\]
for all $x$ in the domain.

Example: The sine function $f(x) = \sin x$ is periodic with period $T = 2\pi$.

---

## 📌 Types of Functions
### 🔹 Polynomial Functions
A **polynomial function** has the form:
\[
p(x) = a_n x^n + a_{n-1} x^{n-1} + ... + a_1 x + a_0\]
where $a_n, ..., a_0$ are constants.

#### 🔹 Linear Function
A first-degree polynomial:
\[
f(x) = ax + b\]
- Graph: Straight line.
- Domain: $(-\infty, \infty)$.

#### 🔹 Quadratic Function
A second-degree polynomial:
\[
f(x) = ax^2 + bx + c\]
- Graph: Parabola.
- Domain: $(-\infty, \infty)$.

#### 🔹 Cubic Function
A third-degree polynomial:
\[
f(x) = ax^3 + bx^2 + cx + d\]
- Graph: S-shaped curve.
- Domain: $(-\infty, \infty)$.

### 🔹 Root Functions
Functions involving square or higher-order roots.

Example:
\[
f(x) = \sqrt{x}
\]
- Domain: $[0, \infty)$.
- Range: $[0, \infty)$.

### 🔹 Rational Functions
A **rational function** is of the form:
\[
f(x) = \frac{p(x)}{q(x)}
\]
where $p(x)$ and $q(x)$ are polynomials, and $q(x) \neq 0$.

#### 🔹 Asymptotes
- **Vertical asymptote** occurs at values where $q(x) = 0$.
- **Horizontal asymptote** depends on the degrees of $p(x)$ and $q(x)$.
- **Slant asymptote** occurs when the degree of $p(x)$ is one more than the degree of $q(x)$.

### 🔹 Exponential Functions
A function of the form:
\[
f(x) = a^x\]
where $a > 0$ and $a \neq 1$.

- Domain: $(-\infty, \infty)$.
- Range: $(0, \infty)$.

### 🔹 Logarithmic Functions
The inverse of exponential functions:
\[
f(x) = \log_a x\]
- Domain: $(0, \infty)$.
- Range: $(-\infty, \infty)$.

### 🔹 Absolute Value Function
Defined as:
\[
f(x) = |x|\]
- Domain: $(-\infty, \infty)$.
- Range: $[0, \infty)$.

### 🔹 Heaviside Function
A step function defined as:
\[
H(x) = \begin{cases} 
0, & x < 0 \\
1, & x \geq 0
\end{cases}
\]
