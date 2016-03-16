---
author:
- Dennis Stassen 906208
title: 'Numerical simulation: Presentation of old assignment'
...

Exercise A
==========

i
--------

Assume a Diamond model as described in the reader where the consumer
has preferences $U_t=c^y_tc^o_{t+1}$, there is no technological progress
and production is described by $y_t=k^\alpha$.*



Compute the capital-labour ratio in the steady state. What is the
effect of an increase in $\alpha$ on the steady-state capital-labour
ratio?

In accordance with the reader the budget constraints in both periods of
an individual are defined as: $$c^y_t=w_t-s_t$$
$$c^o_{t+1}=(1+r_{t+1})s_t$$ Then the lifetime budget constraint is
expressed as: $$w_t=c^y_t + \frac{1}{1+r}c^o_{t+1}$$ Hence,
$U_t=(w_t-s_t)((1+r_{t+1})s_t)$. We take the first order condition of
this function with respect to $s$, $\frac{\partial U}{\partial s_t}=0$.
$$\begin{aligned}
U_t'=&0 \\
\leftrightarrow& (w_t-s_t)(1+r_{t+1})-((1+r_{t+1})s_t)=0 \\
\leftrightarrow& w_t+w_tr_{t+1}-s_t-s_tr_{t+1}-s_t-s_tr_{t+1}=0 \\
\leftrightarrow& 2s_t+2s_tr_{t+1}=w_t+w_tr_{t+1} \\
\leftrightarrow& 2s_t(1+r_{t+1})=w_t(1+r_{t+1}) \\
\leftrightarrow& 2s_t=w_t \\\end{aligned}$$ $$s_t=\frac{w_t}{2}$$

i
--------

Since a standard neoclassical production function is assumed, marginal
products equal factor prices and clearly: $$w_t=f(k_t)-k_tf'k_t)$$
$$r_t=f'(k)-\delta$$ Every young person works one time unit in the
economy. Thus, $L_t=N_t$. Since capital is the only asset it is implied
that: $$F(K_t,L_t)=N_tc^y_t+N_{t-1}c^o_t+I_t$$ where $I_t$ is gross
investment and equal to $K_{t+1}-(1-\delta)K_t$, so:
$$F(K_t,L_t)=N_tc^y_t+N_{t-1}c^o_t+K_{t+1}-(1-\delta)K_t$$ Since
$F(K_t,L_t)$ equals the sum of the marginal products this can be
rewritten as:
$$w_tN_t+(r_t+\delta)K_t=N_tc^y_t+N_{t-1}c^o_t+K_{t+1}-(1-\delta)K_t$$
Using the budget constraints (1) and (2) we derive: $$\begin{aligned}
&w_tN_t+(r_t+\delta)K_t=N_t(w_t-s_t)+N_{t-1}((1+r_{t})s_{t-1})+K_{t+1}-(1-\delta)K_t \\
\leftrightarrow& w_tN_t+r_tK_t+\delta K_t=N_tw_t-N_ts_t+N_{t-1}s_{t-1}+N_{t-1}r_{t}s_{t-1}+K_{t+1}-K_t+\delta K_t \\
\leftrightarrow&K_{t+1}=N_ts_t-N_{t-1}s_{t-1}-N_{t-1}r_{t}s_{t-1}+K_t+r_tK_t\end{aligned}$$
This can only hold if $K_{t}=N_{t-1}s_{t-1}$ and likewise
$r_tK_t=N_{t-1}r_{t}s_{t-1}$. We then get: $$K_{t+1}=N_ts_t-0=N_ts_t$$

i
--------

Since $N_t=L_t$ equation (10) is equivalent to $$K_{t+1}=s_tL_t$$

Now, $(1+g)$ is defined as $L_{t+1}/L_t$, hence:

$$\begin{aligned}
& K_{t+1}=s_tL_t \\
& \leftrightarrow \frac{K_{t+1}}{L_{t+1}}=s_t\frac{L_t}{L_{t+1}} \\
& \leftrightarrow \frac{K_{t+1}}{L_{t+1}}=\frac{s_t}{L_{t+1}/L_{t}}\end{aligned}$$

$$k_{t+1}=\frac{s_t}{1+g}$$

i
--------

Combining this result with (4) and (5) leads to:
$$k_{t+1}=\frac{f(k_t)-k_tf'k_t}{2(1+g)}$$ We know that in the steady
state, per definition, the change in capital stock (${k_{t+1}}-{k_t}$)
equals zero, or likewise $k_{t+1}=k_t$. Using the production function as
described in the assignment (13) boils down to: $$\begin{aligned}
k&=\frac{k^\alpha-k\alpha k^{\alpha-1}}{2(1+g)} \\
k&=\frac{k^\alpha-\alpha k^{\alpha-1+1}}{2(1+g)} \\
k&=\frac{k^\alpha-\alpha k^{\alpha}}{2(1+g)} \\
k&=\frac{(1-\alpha) k^\alpha}{2(1+g)} \\
\frac{k}{k^\alpha}&=\frac{(1-\alpha)}{2(1+g)}\\
k^{1-\alpha}&=\frac{(1-\alpha)}{2(1+g)}\\\end{aligned}$$
$$k^*=\frac{(1-\alpha)}{2(1+g)}^{\frac{1}{1-\alpha}} \\$$ 

i
--------

Equation (14)
describes the capital labour ratio in the steady state. Now let’s see
how k is dependent on $\alpha$. If $\alpha$ increases, the term
$1-\alpha$ decreases. This has an effect on $k$ through two channels.
First, through the nominator: $(1-\alpha)$. Secondly, through the power:
$\frac{1}{1-\alpha}$. As stated above when $\alpha$ increases, the
nominator decreases. The power increases, and since $0<\alpha<1$ and
thus $\frac{1-\alpha}{2(1+g)}<1$ the increase of the power is negatively
related with $k$ as well. Thus, an increase in $\alpha$ would result in
a decrease of $k$. This also seems intuitively correct; if capital has a
higher rate of return the capital-labour ratio in the steady state is
lower.


ii
--------

*ii. Suppose the government introduces a tax τ on interest income. All
revenues of this tax are transferred to the elderly in the same period
as a pension benefit. So the budget constraints become:*

$$\begin{aligned}
c^y_t&=w-s_t \\
c^o_{t+1}&=(1+(1-\tau)r)s_t+T\end{aligned}$$

*Note that the level of the pension benefit T is given for the
individual and cannot be affected by saving more or less. Derive the
Euler equation.*\
\

ii
--------

Given the budget constraint as defined by (15) and (16) the utility
function can be written as $$U_t=(w-s_t)((1+(1-\tau)r)s_t+T)$$

The Euler equation is defined as the ratio of partial derivatives with
respect to savings of consumption when old and consumption when young.
Define $u(c^y_t) = w-s_t$ and $u(c^o_{t+1}) = (1+(1-\tau)r)s_t+T$. Such
that $U_t=u(c^y_t)u(c^o_{t+1})$. Hence:

$$\frac{u'(c^y_t)s_t}{u'(c^o_{t+1})s_t}=\frac{-1}{(1+(1-\tau)r}$$


iii
--------

*Derive the effect of a marginal increase in the tax rate $\tau$
(starting from $\tau=0$) on lifetime utility, assuming that the pension
benefit is adjusted (i.e. assuming that $T = \tau rs$ but that the
individual does not take this into account when deciding how much to
save). Interpret your answer.*


$$\begin{aligned}
\frac{\partial U}{\partial s_t}&=(w-s_t)(1+r-\tau r)-(1+(1-\tau)r)s_t-T=0 \\
&\leftrightarrow w(1+r-\tau r)-s_t-s_t r +s_t \tau r -s_t -s_t r + s_t \tau r -T =0 \\
2s_t+2s_t r-2s_t \tau r &=w(1+r-\tau r)-T \\
2s_t(1+r-\tau r)&=w(1+r-\tau r) -T \\
2s_t&=w-\frac{T}{1+r-\tau r)}\\\end{aligned}$$

$$s_t=\frac{w-\frac{T}{1+r-\tau r)}}{2}$$

iii
--------

\
The marginal effect of $\tau$ starting from $\tau=0$ is equal to the
difference of the derivative of the lifetime utility functions including
and excluding $\tau$. Combining equations (4) and (19) gives us the
marginal effect of $\tau$, when it is initially zero:

$$\delta s_t = \frac{w}{2} - \frac{w-\frac{T}{1+r-\tau r)}}{2}$$

Substituting $T=\tau r s$:
$$\delta s_t = \frac{w}{2} - \frac{w-\frac{\tau r s}{1+r-\tau r)}}{2}$$\
When we introduce a tax that is paid out to the elderly we observe that
people will save less income. The problem is that when everyone saves
less this will lower the benefit in the end. People have thus
disincentives to save which has a negative effect on the benefits paid
out ($\tau r s$).



Exercise B
==========

i
--------

*Assume a Solow-Swan model as described in the reader, with a
Cobb-Douglas production function $Y =1.5K^{0.5} \tilde{L}^{0.5}$ and
$x = 0.5, n = 0.5, \delta = 0.25, \sigma = 0.5$.*

*Compute the capital-labour ratio $\tilde{k}$ in the steady state.*

We know that $1+g=(1+x)(1+n)$ so $1+g=(1.5^2)=2.25$. Since the
production function features CRS we also know that we can write it in
intensive form as $y=1.5k^{0.5}$. In the steady state we know that
depreciation equals investment and hence that the capital labour ratio
is constant. Therefore, we use and put it equal to zero.

$$\begin{aligned}
\frac{\sigma f(k_t) -(\delta+g)k_t}{1+g} &= 0 \rightarrow \\
\frac{\sigma 1.5k_t^{0.5} -(\delta+g)k_t}{1+g} &= 0 \rightarrow \\
\sigma 1.5k_t^{0.5} -(\delta+g)k_t &= 0 \rightarrow \\
\sigma 1.5k_t^{0.5} -\delta k_t - g k_t &= 0 \rightarrow \\
0.5 \times 1.5k_t^{0.5} -0.25k_t - 1.25k_t &= 0 \rightarrow \\
0.75k_t^{0.5} -0.25k_t - 1.25k_t &= 0 \rightarrow \\
0.25k_t(3k^{-0.5}-1-5)&=0 \rightarrow \\ \\
k=0 \vee 3k^{-0.5}-1-5&=0 \rightarrow \\
k=0 \vee 3k^{-0.5}&=6 \rightarrow \\
k=0 \vee k^{-0.5}&=2 \rightarrow \\
k^*=0 \vee k^*=\sqrt[-0.5]2&=0.25\end{aligned}$$

ii
--------

*Is this steady state dynamically efficient or dynamically inefficient?*

For this question to answer we first need to derive the golden rule
steady state level and compare this to the previous found level of
$k^*=0.25$. $$\begin{aligned}
f(k) &=1.5k^{0.5}\\
f'(k) -\delta - g &=0 \rightarrow \\
0.75k^{-0.5} -0.25 - 1.25 &=0 \rightarrow \\
0.75k^{-0.5} &=1.5 \rightarrow \\
k^{-0.5} &=2 \rightarrow \\
k_{GR} &= 0.25\end{aligned}$$ We see that the capital level of the
golden rule equals the capital level of the current steady state. This
means that this steady state is dynamically efficient.

iii
--------


*What is the effect of a decrease in population growth from $n = 0.5$ to
$n = 0$ on the steady-state capital-labour ratio?*

Since $n$ changes to 0, $g=0.5$. Using the same derivation as in
question (i) we find:

$$\begin{aligned}
\sigma 1.5k_t^{0.5} -\delta k_t - g k_t &= 0 \rightarrow \\
0.75k_t^{0.5} - 0.25 k_t - 0.5 k_t &=0 \rightarrow \\
0.25k_t(3k^{-0.5}-1-2)&=0 \rightarrow \\ \\
k=0 \vee 3k^{-0.5}-1-2&=0 \rightarrow \\
k=0 \vee 3k^{-0.5}&=3 \rightarrow \\
k=0 \vee k^{-0.5}&=1 \rightarrow \\
k^{**}=0 \vee k^{**}=\sqrt[-0.5]1&=1\end{aligned}$$

Hence, the steady state capital-labour ratio increases with 0.75.
