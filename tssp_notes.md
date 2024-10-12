Example 2.

$X_n$ are iid Unif[0;1]

$$
Y_n = \frac{nX_1 + X_2 +X_3 + \ldots +X_n}{n}
$$

Find $\plim Y_n$.

Write $Y_n$ as
$$
Y_n = X_1 + \frac{X_2 +X_3 + \ldots +X_n}{n} = X_1 + \frac{X_2 +X_3 + \ldots +X_n}{n - 1} \cdot \frac{n-1}{n}
$$

Observe that $\plim X_1 = X_1$ by law of large numbers, $\plim \bar X = E (X_1) = 1/2$, $\plim (n - 1) / n = 1$.

Hence, $\plim Y_n = X_1 + 0.5$. 

No one in the Observable part of the Milky Way galaxy knows how to find limits of all sequences. 
General ideas are:

* Split the limit into simple parts and solve these parts. 

* Find the source of randomness that has higher and higher weight in the sequence. 