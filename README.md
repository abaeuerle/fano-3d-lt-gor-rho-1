# fano-3d-lt-gor-rho-1
A database of the non-toric, $\mathbb{Q}$-factorial, log terminal, Gorenstein, Fano threefolds of Picard number $1$ that admit an effective action of a two-dimensional torus.

For more information on the provided data see [arXiv:2108.03029](https://arxiv.org/abs/2108.03029). This dataset is also available at [Zenodo](https://zenodo.org/record/7298788#.Y2o6lXbMKUk).

## Description

The columns of the csv-file are labelled as follows:

- **ID**: The ID of the family within the database, numbered 1 through 538.
- **case**: Refers to the corresponding case in Proposition 2.24. Numbered 1 through 8.
- **format**: The format of the family as defined on page 13.
- **generator matrix**: The defining matrix $P$ as defined in Construction 2.2.
- **class group**: The isomorphy type of the class group. Presented as $[0, t_1, \dots, t_n]$ meaning $\mathbb{Z} \oplus (\mathbb{Z}/t_1 \mathbb{Z} \oplus \dots \oplus \mathbb{Z}/t_n \mathbb{Z})$.
- **gd matrix**: Grading matrix of the Cox ring. The $i$ th column is the degree of the $i$ th Cox ring generator.
- **relations**: Minimal generating set of the ideal of relations of the Cox ring.
- **relation degree**: Degree of the minimal generators of the ideal of relations.
- **anticanonical class**: The anticanonical class.
- **degree**: Anticanonical self-intersection number $-\mathcal{K}_X^3$.
- **gorenstein index**: The smallest positive $\iota \in \mathbb{Z}$ such that $\iota \mathcal{K}_X$ is Cartier. Here always equal to $1$.
- **fano index**: The largest $k \in \mathbb{Z}$ such that $kD = \mathcal{K}_X$ for some Cartier divisor $D$.
- **dimension**: The dimension of the corresponding variety. Here always equal to 3.
- **picard rank**: The rank of the Picard group. Here always equal to 1.
- **acr gd matrix**: Grading matrix of the anticanonical ring w.r.t. to a minimal system of generators. The $i$ th column is the degree of the $i$ th generator.
- **acr relations**: Minimal generating set of the ideal of relations of the anticanonical ring.
- **hsNum, hsDenom**: Numerator and denominator of the Hilbert-Poincaré series, i.e. ${\rm HP}_X(t) = {\rm hsNum}(t) / {\rm hsDenom}(t)$.
- **hs0 - hs7**: The $i$ th coefficient of the power series expansion of ${\rm HP}_X(t)$, i.e. ${\rm HP}_X(t) = {\rm hs0} + {\rm hs1}\ t + {\rm hs2}\ t^2 + \dots + {\rm hs7}\ t^7 + \dots$
- **codim**: The codimension of the embedding into a weighted projective space provided by the choice of generators of the anticanonical ring.
- **genus**: This equals $h^0(X,-\mathcal{K}_X) - 2$.

