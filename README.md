**Proposition:** If $\log{K}=m\phi+n$, 

$\hat{\phi}=\frac{\sum{\phi_i h_i}}{\sum{h_i}}$, and 

$\hat{K}=\frac{\sum{K_i h_i}}{\sum{h_i}}$ such that $K_i, \phi_i, h_i > 0$ for all $i \in \mathbb{Z}$, then

$\log{\hat{K}} \neq m\hat{\phi}+n$.

**Proof:**

$\hat{\phi} = \frac{\sum{\phi_i h_i}}{\sum{h_i}} = \frac{\sum{\frac{\log{K_i}-n}{m}h_i}}{\sum{h_i}} = \frac{1}{m\sum{h_i}}\sum{h_i \log{K_i}} - \frac{n \sum{h_i}}{m \sum{h_i}}$

hence,

$\hat{\phi} = \frac{1}{m} \frac{\sum{h_i \log{K_i}}}{\sum{h_i}} - \frac{n}{m}$.

Since, $K_i < 10^{K_i}$, $\forall K_i \in \mathbb{R}$ and $K_i>0$,

$\frac{\sum{h_i \log{K_i}}}{\sum{h_i}} < \frac{\sum{K_i h_i}}{\sum{h_i}}$. $\blacksquare$

**Note:**

The correct expression for $\hat{K}$ such that,
$\log{\hat{K}} = m\hat{\phi}+n$ is 
$10^\frac{\sum{h_i \log{K_i}}}{\sum{h_i}}$.
