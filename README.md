# Book Example with a bit of maths

This is the first paragraph. Nice eh? All in markdown. Yeah! Awesome!

![Hello](/examples-degrees.svg)

Now this is the second paragraph. I will introduce a bit of maths. Don't worry, just doing some addition like \\(x+y=2\\) or \\(x^2+3-\zeta=\text{I don't even}\\).

Phew, we survived that, or not, don't know yet till we try. What about display maths? If \\[x^2+y^2=\int_0^\infty \sqrt[5]{x}\,\mathrm{d}x\\] appears in a separate paragraph, or doesn't get displayed at all, then oh no. It should look like

\\[x^2+y^2=\int_0^\infty \sqrt[5]{x}\,\mathrm{d}x\\]

What about dollar signs?

Let's see... $x$, $y$, and $z$.

$$x+y=0$$

Where did it go? $$x$$, $$y$$, $$z$$

## Align and Aligned

`$$\begin{aligned}`

$$\begin{aligned}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy\\
n_1\sin\theta_i & = n_2\sin\theta_r
\end{aligned}$$

`\begin{align*}`

\begin{align*}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy \\
n_1\sin\theta_i & = n_2\sin\theta_r
\end{align*}

Without subscripts and stars:

\begin{align}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{align}

with excaped slashes:

\\begin{align*}
\\dot{x} & = \\sigma(y-x) \\\\
\\dot{y} & = \\rho x - y - xz \\\\
\\dot{z} & = -\\beta z + xy \\\\
n_1\sin\theta_i & = n_2\sin\theta_r
\\end{align*}

that doesn't contain subscripts and stars:

\\begin{align}
\\dot{x} & = \\sigma(y-x) \\\\
\\dot{y} & = \\rho x - y - xz \\\\
\\dot{z} & = -\\beta z + xy
\\end{align}


[![Build Status](https://www.gitbook.io/button/status/book/ewon521/try-out-gitbook)](https://www.gitbook.io/book/ewon521/try-out-gitbook/activity)




