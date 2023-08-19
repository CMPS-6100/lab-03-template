# CMPS 6100  Lab 03

In this lab, you will practice and build up an intuition around asymptotic analysis.

Some prompts will require you to edit `main.py` and others will require answers to go in `answers.md`.

Refer back to the [README.md](README.md) for instruction on git, how to test your code, and how to submit properly to get all the points you've earned.

## Asymptotic Analysis Problems (14 pts)

Conventions: 


$$
\begin{aligned}
&\lg n  = \log_2 n      \nonumber \\
&\ln n = \log_e n       \nonumber \\
&\log n = \log_{10} n   \nonumber \\
&\log^c n = (\log n)^c  \nonumber \\
&\lg \lg n = \lg(\lg n) \nonumber
\end{aligned}
$$

Using the asymptotic definitions or the limit theorem, prove (or disprove) the following statements. Add all answers to `answers.md`. Each of the following problems are worth one point, except for 4 and 10 which are worth two points each.

1. $32n \in O(n)$

<br>

2. $\ln n \in \Omega(n)$

<br>

3. $\lg n \in \Theta(\ln n)$

<br>

4. $\log_c n \in \Theta(\ln n)$, $~~c > 1$

<br>

5. $n^2 \in O(2^n)$

<br>

6. $n^3 \in \Omega(n^2)$

<br>

7. $4^{\lg n} \in \Theta(n)$

<br>

8. $\ln^2 n \in O(n)$

<br>

9. $\ln^2 n \in O(\sqrt n)$

<br>

10. $\ln^c n \in O(n^k)$, $~~\forall ~ c,k > 0$ 

<br>

11. $\ln \ln n \in O(\ln n)$

<br>

12.  $2^n \in \Omega(2^{n+1})$

<br>

## Epilogue

In this lab, you have built up a facility in asymptotic analysis and an intuition around these common functions. I hope that you've noticed some common general patterns which you can broadly apply.

With experience and practice, you will be able to consider an algorithm, determine its runtime, and quickly rank it relative to other algorithms and runtimes. We will continue to work on this in the coming weeks.