$$
\min\limits_{\mathbf{x}\in{\lbrace0,1\rbrace}^n} q \mathbf{x}^{\intercal}\mathbf{\Sigma} \mathbf{x}-\mathbf{\mu}^{\intercal}\mathbf{x} \\
\text{subject to: } \sum\limits_{i=1}^n x_i = B
$$

The risk factor $q\in\left[0,1\right]$ determines the risk preference of the investor:

- $q=1$ would be a fully risk adverse investor (chooses the lowest risk portfolio irrespective of the returns)
- $q=0$ would be an an aggressive investor (chooses the highest return portfolio and does not care about risk at all)

> [!IMPORTANT]
> Simplifications:
