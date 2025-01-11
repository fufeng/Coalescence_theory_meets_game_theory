# Computer Code

> custom computer code that allows readers to reproduce the results.

***

### Evolution_of_Sociality.ipynb

#### Symbolic Calculation part

* ##### Setting

  * $n$ strategies in a well-mixed population under the Moran process

  * the interaction payoff of 

> 1. Compute the expressions in the article.
> 2. Compute and simplify expressions of the abundance density function, the independent distribution and population average of preferences $p$ and $q$.

* ##### Function

  * expressions: equations, solutions, ...
  * numerical computation
  * plotting

#### Visualization part

* ##### Setting

  * the same as the Symbolic Calculation part


> Plot some figures in the article.
>
> > **Fig. 2.**  The full set of conditions under which the population tends to
> > evolve more homophilic preferences.
> > **Fig. 3.** Abundance ranking of the four special binary preferences $[1,1]$,
> > $[1,0]$, $[0,1]$, and $[0,0]$ under the mutation-selection equilibrium.
> > **Fig. 4.** Heatmaps of the relative abundance density $\mathcal{D}(p,q)$ for different
> > payoff combinations.

* ##### Function

  * plotting

***

## Instructions

The code is organized into ipython notebooks. 

The software, module and hardware list is given below.

* Software

> Python 3.8.8 and above

* Module

| name          | version |
| ------------- | :------ |
| numpy         | 1.24.3  |
| sympy         | 1.11.1  |
| matplotlib    | 3.7.2   |
| colormaps     | 3.0.1   |
| yuxin_helpers |         |
| mpl_toolkits  |         |
| warnings      |         |

> If we have matplotlib installed, we would be able to import mpl_toolkits directly.

* OS

> Mac OS X, Windows, or Linux

We use Anaconda GUI to run our code (which comes with the packages automatically installed). Otherwise, we may run `pip install` with the name and version for every candidate item.

### How to Obtain the Expressions and Figures

More detailed explanations are given in the comments and markdown notes (for ipython notebooks).