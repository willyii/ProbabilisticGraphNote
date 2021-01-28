# Independencies in Bayesian Networks

##  Independence & Factorization

Factorization of a distribution $P$ implies independencies that hold in $P$.
Then, if $P$ factorizes over $G$, can we read these independencies from the
structure of $G$?

### Flow of Influence & d-separation

Definition: $X$ and $Y$ are d-separated in $G$ given $Z$ if there is no active
trail in $G$ between $X$ and $Y$ given $Z$. Notation: $d-sep_G(X,Y|Z)$

Theorem: If $P$ factorizes over $G$, and $d-sep_G(X,Y|Z)$ then $P$ satisfies
$(X \perp Y|Z)$
