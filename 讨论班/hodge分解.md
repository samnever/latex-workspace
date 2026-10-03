# Complex and Hermitian Structures on Vector Spaces

## Complex Structures

In the following, $V$ shall denote a finite-dimensional real vector
space.

::: definition
**Definition 1**. *An endomorphism $I:V\rightarrow V$ with
$I^2=-\mathrm{id}$ is called an **almost complex structure** on $V$.*
:::

::: {#hh .lemma}
**Lemma 2**. *If $I$ is an almost complex structure on a real vector
space $V$, then $V$ admits in a natural way the structure of a complex
vector space.*
:::

::: proof
*Proof.* The $\mathbb{C}$-module structure on V is defined by
$(a+ib)\cdot v=a\cdot v+b\cdot I(v)$. ◻
:::

For a real vector space $V$ the complex vector space
$V\otimes_{\mathbb{R}}\mathbb{C}$ is denoted by $V_{\mathbb{C}}$.

::: definition
**Definition 3**. *Let $I$ be an almost complex structure on a real
vector space $V$ and let $I:V_{\mathbb{C}} \rightarrow V_{\mathbb{C}}$
be its $\mathbb{C}$-linear extension. Then the $\pm i$ eigenspaces are
denoted $V^{1,0}$ and $V^{0,1}$, respectively, i.e.
$$V^{1,0} =\{v\in V_{\mathbb{C}}\mid I(v)=i\cdot v\}\ and\ V^{0,1} =\{ v\in V_{\mathbb{C}}\mid I(v)=-i\cdot v\}.$$*
:::

::: lemma
**Lemma 4**. *Let $V$ be a real vector space endowed with an almost
complex structure $I$. Then $$V_{\mathbb{C}} =V^{1,0} \oplus V^{0,1}.$$
Complex conjugation on $V_{\mathbb{C}}$ induces an $\mathbb{R}$-linear
isomorphism $V^{1,0} \cong V^{0,1}$.*
:::

::: proof
*Proof.* The first assertion follows from the
map$$v\rightarrow \frac{1}{2}(v-iI(v))\oplus\frac{1}{2}(v+iI(v)).$$ For
the second assertion we write $v\in V_{\mathbb{C}}$ as $v=x+iy$ with
$x,y\in V$. Then
$\overline{(v-iI(v))}=(x-iy+iI(x)+I(y))=(\bar{v}+iI(\bar{v}))$.Hence the
complex conjugation interchange the two facotrs. ◻
:::

One should be aware of the existence of two almost complex structures on
$V_{\mathbb{C}}$. One is given by $I$ and the other one by $i$. They
coincide on the subspace $V^{1,0}$ but differ by a sign on
$V^{0,1}$.Obviously, $V^{1,0}$ and $V^{0,1}$ are complex subspaces of
$V_{\mathbb{C}}$ respect to both almost complex structures. In the
sequel, we will always regard $V_{\mathbb{C}}$ as the complex space with
respect to $i$.

If $V^{1,0}$ and $V^{0,1}$ are considered with the complex structure
$i$, then the compositions $V\subset V_{\mathbb{C}}\rightarrow V^{1,0}$
and $V\subset V_{\mathbb{C}} \rightarrow V^{0,1}$ are complex linear
respectively complex antilinear. Here, $V$ is endowed with the almost
complex structure $I$.

::: lemma
**Lemma 5**. *Let $V$ be a real vector space endowed with an almost
complex structure $I$. Then the dual space
$V^{*}=\mathrm{Hom}_{\mathbb{R}}(V,\mathbb{R})$ has a natural almost
complex structure given by $I(f)(v)=f(I(v))$. The induced decomposition
on
$V^{*}_{\mathbb{C}}=\mathrm{Hom}_{\mathbb{R}}(V,\mathbb{C})=(V_{\mathbb{C}})^{*}$
is given by $$\begin{aligned}
        &(V^{*})^{1,0}\ =\{f\in (V_{\mathbb{C}})^{*}\mid f(I(v))=if(v)\}\ =(V^{1,0})^{*}\\
        &(V^{*})^{0,1}=\{f\in (V_{\mathbb{C}})^{*}\mid f(I(v))=-if(v)\}=(V^{0,1})^{*}.
    
\end{aligned}$$ Also note that
$(V^{*})^{1,0}=\mathrm{Hom}_{\mathbb{C}}((V,I),\mathbb{C})$.[^1]*
:::

If $V$ is a real vector space of dimension $d$, the natural
decomposition of its exterior algebra is of the
form$$\bigwedge\nolimits^k V=\bigoplus_{k=0}^{d}\bigwedge\nolimits^k V.$$

Analogously, $\bigwedge^{*}V_{\mathbb{C}}$ denotes the exterior algebra
of the complex vector space $V_{\mathbb{C}}$, which decomposes
as$$\bigwedge\nolimits^k V_{\mathbb{C}}=\bigoplus_{k=0}^{d}\bigwedge\nolimits^k V_{\mathbb{C}}.\label{hhh}$$Moreover,
$\bigwedge^{*}V_{\mathbb{C}}=(\bigwedge^{*}V)\otimes_{\mathbb{R}}\mathbb{C}$
and $\bigwedge^{*}V$ is the real vector subspace of
$\bigwedge^{*}V_{\mathbb{C}}$ that is left invariant under complex
conjugation.

::: definition
**Definition 6**.
*$$\bigwedge\nolimits^{p,q}V:=\bigwedge\nolimits^p V^{1,0}\otimes_{\mathbb{C}}\bigwedge\nolimits^q V^{0,1},$$where
the exterior products of $V^{1,0}$ and $V^{0,1}$ are taken as exterior
products of complex vector spaces. An element
$\alpha \in \bigwedge^{p,q}V$ is of bidegree $(p,q)$.*
:::

::: proposition
**Proposition 7**. *For a real vector space $V$ endowed with an almost
complex structure $I$ one has:*

(i) *$\bigwedge^{p,q}V$ is in a canonical way a subspace of
    $\bigwedge^{p+q}V_{\mathbb{C}}$.*

(ii) *$\bigwedge^{k}V_{\mathbb{C}}=\bigoplus\limits_{p+q=k}\bigwedge^{p,q}V$.*

(iii) *Complex conjugation on $\bigwedge^{*}V_{\mathbb{C}}$ defines a
      ($\mathbb{C}$-antilinear) isomorphism
      $\bigwedge^{p,q}V\cong\bigwedge^{q,p}V$, i.e.
      $\overline{\bigwedge^{p,q}V}=\bigwedge^{q,p}V$.*

(iv) *The exterior product is of bidegree $(0,0)$, i.e.
     $(\alpha,\beta)\mapsto\alpha\wedge\beta$ maps
     $\bigwedge^{p,q}V\times \bigwedge^{r,s}V$ to the subspace
     $\bigwedge^{p+r,q+s}V$.*
:::

Any vector $v\in V_{\mathbb{C}}$ can be written as $v=x+iy$ with
$x,y\in V$. Assume that $z_i=\frac{1}{2}(x_i-iy_i)\in V^{1,0}$ is a
$\mathbb{C}$-basis of $V^{1,0}$ with $x_i,y_i\in V$. Since
$I(z_i)=iz_i$, one finds $y_i=I(x_i)$ and $x_i=-I(y_i)$. Moreover,
$x_i,y_i\in V$ form a real basis of $V$ and, therefore, a basis of the
complex vector spaces $V_{\mathbb{C}}$. A natural basis of the complex
vector spaces $V^{0,1}$ is then provided by
$\bar{z}_i=\frac{1}{2}(x_i+iy_i)$.[^2]

Let $\langle x^i,y^i\rangle$be the basis of $V^{*}$ dual to
$\langle x_i,y_i\rangle$. Then, $z^i=x^i+iy^i$ and $\bar{z}^i=x^i-iy^i$
are the basis of $V^{1,0^*}$ and $V^{0,1^*}$ dual to
$\langle z_i\rangle$ respectively $\langle \bar{z}_i \rangle$.

Note that $I(x^i)=-y^i$ and $I(y^i)=x^i$. We tacitly use the natural
isomorphism $\bigwedge^{k}V^{*}\cong(\bigwedge^{k}V)^*$ given by
$(\alpha_1\wedge\dots\wedge\alpha_k)(v_1\wedge\dots\wedge v_k)=\det(\alpha_i(v_j))_{i,j}$.

::: {#rop .definition}
**Definition 8**. *With respect to the direct sum decomposition
[\[hhh\]](#hhh){reference-type="eqref" reference="hhh"} and the
proposition above one defines the natural
projections$$\mathnormal{\Pi}^{k}:\bigwedge\nolimits^*V_{\mathbb{C}}\longrightarrow\bigwedge\nolimits^k V_{\mathbb{C}}\ and\ \mathnormal{\Pi}^{p,q}:\bigwedge\nolimits^* V_{\mathbb{C}}\longrightarrow\bigwedge\nolimits^{p,q}V.$$Besides,$$\mathrm{\mathbf{I}}:=\sum_{p,q}i^{p-q}\cdot \mathnormal{\Pi}^{p,q}.$$*
:::

The operator $\mathnormal{\Pi}^{k}$ does not depned on the almost
complex structure $I$, but the operators $\mathrm{\mathbf{I}}$ and
$\mathnormal{\Pi}^{p,q}$ certainly do. Note that $\mathrm{\mathbf{I}}$
is the multiplicative extension of the almost complex structure $I$ on
$V_{\mathbb{C}}$. Since $I$ is defined on the real vector space $V$,
also $\mathrm{\mathbf{I}}$ is an endomorphism of the real exterior
algebra $\bigwedge^* V$.

We donte the corresponding operators on the dual space
$\bigwedge^* V_{\mathbb{C}}^{*}$ also by
$\mathnormal{\Pi}^{k},\mathnormal{\Pi}^{p,q}$, respectively
$\mathrm{\mathbf{I}}$. Note that
$\mathrm{\mathbf{I}}(\alpha)(v_1,\dots,v_k)=\alpha(I(v_1),\dots,I(v_k))$
for $\alpha\in \bigwedge^k V_{\mathbb{C}}$ and $v_i\in V_{\mathbb{C}}$.

## Hermitian Structures

Let $(V,\langle\ ,\ \rangle)$ be finite-dimensional euclidian vector
space, i.e. $V$ is a real vector space and $\langle\ ,\ \rangle$ is a
positive definite symmetric bilinear form. 

::: definition
**Definition 9**. *An almost complex structure $I$ on $V$ is
**compatible** with the scalar product $\langle\ ,\ \rangle$ if
$\langle I(v),I(w)\rangle=\langle v,w\rangle$ for all $v,w\in V$.*
:::

::: {#gc .definition}
**Definition 10**. *The **fundamental form** associated to
$(V,\langle\ ,\ \rangle,I)$ is the
form$$\omega := -\langle(\ ),I(\ )\rangle=\langle I(\ ),(\ )\rangle.$$*
:::

One considers the extension of the scalar product $\langle\ ,\ \rangle$
to a positive definite hermitian form $\langle\ ,\ \rangle_{\mathbb{C}}$
on $V_{\mathbb{C}}$. This is defined
by$$\langle v\otimes \Lambda, w\otimes\mu\rangle_{\mathbb{C}}:=(\lambda\bar{\mu})\cdot\langle v,w\rangle$$for
$v,w\in V$ and $\lambda,\mu\in\mathbb{C}$. Note that $\omega$ can be
extended to $\omega_{\mathbb{C}}$ on $V_{\mathbb{C}}$, too.

::: lemma
**Lemma 11**.
*$\omega\in \bigwedge^{2}V^*,\omega_{\mathbb{C}}\in\bigwedge^{1,1}V^*$.*
:::

Recall that $\bigwedge^{2}V^*$ is a real vector space and
$\bigwedge^{1,1}V^*$ is a complex vector space.

::: proof
*Proof.* For all
$v,w\in V$,$$\langle v,I(w)\rangle=\langle I(v),I(I(w))\rangle=-\langle I(v),w\rangle=-\langle w,I(v)\rangle \Rightarrow \omega \in \bigwedge\nolimits^2 V^*.$$
For all
$v,w\in V_{\mathbb{C}}$,$$(\mathrm{\mathbf{I}}\omega)(v,w)_{\mathbb{C}}=\omega(I(v),I(w))_{\mathbb{C}}=\langle I(I(v)),I(w)\rangle=\omega(v,w)_{\mathbb{C}} \Rightarrow \omega\in\bigwedge\nolimits^{1,1}V^*.$$ ◻
:::

One can regard $\omega$ as the restriction of $\omega_{\mathbb{C}}$ to
$V$. For convenience I just use $\omega$ to denote $\omega_{\mathbb{C}}$
later. (Of course, this is abuse of notation.)

Note that two of the three structures
$\lbrace\langle\ ,\ \rangle,I,\omega\rbrace$ determine the remaining
one.

::: lemma
**Lemma 12**. *If $(V,\langle\ ,\ \rangle)$ is an euclidian vector space
with a compatible almost complex structure $I$. Then
$V_{\mathbb{C}}=V^{1,0}\oplus V^{0,1}$ is an orthogonal decomposition
with respect to the hermitian product
$\langle\ ,\ \rangle_{\mathbb{C}}$.*
:::

::: proof
*Proof.* Let $v-iI(v)\in V^{1,0}$ and $w+iI(w)\in V^{0,1}$ with
$v,w\in V$. Then an easy calculation shows
$\langle v-iI(v),w+iI(w)\rangle_{\mathbb{C}}=0$. ◻
:::

::: definition
**Definition 13**. *Let $(V,\langle\ ,\ \rangle)$ be an euclidian vector
space and let $I$ be a compatible almost complex structure. Furthermore,
let $\omega$ be the associated fundamental form. Then the **Lefschetz
operator**
$L:\bigwedge^{*}V_{\mathbb{C}}^{*}\rightarrow\bigwedge^* V_{\mathbb{C}}^{*}$
is given by $\alpha\mapsto \omega\wedge\alpha$.*
:::

::: remark
**Remark 14**.

(i) *$L$ is the $\mathbb{C}$-linear extension of the real operator
    $\bigwedge^{*}V^{*}\rightarrow \bigwedge^{*}V^{*},\alpha\mapsto\omega\wedge\alpha$.
    Note that $\omega\in\bigwedge^{2}V^{*}$.*

(ii) *$L(\bigwedge^{p,q}V^*)\subset\bigwedge^{p+1,q+1}V^*$. Note that
     $\omega\in\bigwedge^{1,1}V^*$.*
:::

Let $(V,\langle\ ,\ \rangle)$ be an oriented euclidian vector space of
dimension $d$, then $\langle\ ,\ \rangle$ defines scalar products on all
the exterior powers $\bigwedge^{k}V$. Explicitly, if
$e_1,\dots,e_d\in V$ is an orthonormal basis of $V$, then
$e_I\in\bigwedge^k V$ with $I=\{i_1\le\dots\le i_k
\}$ is an orthonormal basis of $\bigwedge^k V$. Let
$\mathrm{vol}\in \bigwedge^d V$ be the orientation of $V$ of norm $1$
given by $\mathrm{vol}=e_1\wedge\dots\wedge e_d$.[]{#wds label="wds"}

::: definition
**Definition 15**. *The **Hodge** $*$**-operator** is defined
by$$\alpha\wedge *\beta=\langle\alpha,\beta\rangle\cdot\mathrm{vol}$$for
$\alpha,\beta\in\bigwedge^* V$.*
:::

This determines $*$, for the exterior product defines a nondegenerate
pairing
$\bigwedge^k V\times \bigwedge^{d-k}V\rightarrow\bigwedge^d V=\mathrm{vol}\cdot\mathbb{R}$.
One easily sees that $*:\bigwedge^k V\rightarrow \bigwedge^{d-k}V$.

::: proposition
**Proposition 16**. *Any almost complex structure on $V$ induces a
natural orientation on $V$. The orientation is well-defined, as it does
not change under $\mathbb{C}$-linear automorphisms.*
:::

::: proof
*Proof.* By [2](#hh){reference-type="ref" reference="hh"} we just need
to consider $\mathbb{C}^n$. When $n=1$ we use the orientation given by
the basis $\{1,i\}$. When $n>1$ we construct likewise. ◻
:::

::: remark
**Remark 17**. *Using the natural orientation, the Hodge $*$-operator is
well-defined.*
:::

::: proposition
**Proposition 18**. *Notation as above, we have:*

(i) *If $\{i_1,\dots,i_k,j_1,\dots,j_{d-k} \}=\{1,\dots,d\}$ one
    has$$*(e_{i_1}\wedge\dots\wedge e_{i_k})=\epsilon\cdot e_{j_1}\wedge\dots\wedge e_{j_{d-k}},$$where
    $\epsilon=\mathrm{sgn}(i_1,\dots,i_k,j_1,\dots,j_{d-k})$. In
    particular, $*1=\mathrm{vol}$.*

(ii) *$\langle\alpha,*\beta\rangle=(-1)^{k(d-k)}\langle*\alpha,\beta\rangle$
     for $\alpha\in\bigwedge^k V$.*

(iii) *$*^2|_{\bigwedge^k V}=(-1)^{k(d-k)}$.*

(iv) *Hodge $*$-operator is an isometry on
     $(\bigwedge^* V,\langle\ ,\ \rangle)$.*
:::

In following situation we will usually have $d=2n$ and
$*,\langle\ ,\ \rangle$ will be considered **on the dual space**
$\bigwedge^* V^*$.[^3]

::: definition
**Definition 19**. *The **dual Lefschetz operator**
$\varLambda:\bigwedge^* V^*\rightarrow\bigwedge^* V^*$ is adjoint to $L$
with respect to $\langle\ ,\ \rangle$, i.e. $\Lambda\alpha$ is uniquely
determined by the
condition$$\langle\varLambda\alpha,\beta\rangle=\langle\alpha,L\beta\rangle\ for\ all\ \beta\in\bigwedge\nolimits^* V^*.$$The
$\mathbb{C}$-linear extension
$\bigwedge^* V_{\mathbb{C}}^*\rightarrow\bigwedge^*V_{\mathbb{C}}^*$ of
the dual Lefschetz operator will also be denoted by $\varLambda$.*
:::

::: lemma
**Lemma 20**.
*$\varLambda(\bigwedge^k V^*)\subset\bigwedge^{k-2}V^*$.Moreover, one
has $\varLambda=*^{-1}\circ L\circ *$.*
:::

::: proof
*Proof.*
$$\langle\alpha,L\beta\rangle\cdot\mathrm{vol}=\langle L\beta,\alpha\rangle\cdot\mathrm{vol}=L\beta\wedge*\alpha=\omega\wedge\beta\wedge*\alpha=\beta\wedge(\omega\wedge*\alpha)=\langle\beta,*^{-1}(L(*\alpha))\rangle\cdot\mathrm{vol}.$$ ◻
:::

The Hodge $*$-operator associated to $(V,\langle\ ,\ \rangle)$ can be
extended $\mathbb{C}$-linearly to
$*:\bigwedge^k V_{\mathbb{C}}^*\rightarrow\bigwedge^{2n-k}V_{\mathbb{C}}^*$.
On $\bigwedge^* V_{\mathbb{C}}^*$ we
have$$\alpha\wedge*\bar{\beta}=\langle\alpha,\beta\rangle_{\mathbb{C}}\cdot\mathrm{vol}.$$Still,
$L$ and $\varLambda$ are adjoint to each other with respect to
$\langle\ ,\ \rangle_{\mathbb{C}}$ after $\mathbb{C}$-linear extension
and $\varLambda=*^{-1}\circ L\circ *$ on $\bigwedge^* V_{\mathbb{C}}^*$.

::: lemma
**Lemma 21**. *Let $\langle\ ,\ \rangle_{\mathbb{C}},\ \varLambda$, and
$*$ be as above. Then*

(i) *The decomposition
    $\bigwedge^k V_{\mathbb{C}}^*=\bigoplus\bigwedge^{p,q}V^*$ is
    orthogonal with respect to $\langle\ ,\ \rangle_{\mathbb{C}}$.*

(ii) *The Hodge $*$-operator maps $\bigwedge^{p,q}V^*$ to
     $\bigwedge^{n-q,n-p}V^*$, where
     $n=\mathrm{dim}_{\mathbb{C}}(V,I)$.*

(iii) *$\varLambda(\bigwedge^{p,q}V^*)\subset\bigwedge^{p-1,q-1}V^*$.*
:::

::: definition
**Definition 22**. *$$H:=\sum_{k=0}^{2n}(k-n)\cdot\varPi^k.$$*
:::

We use the notation $[A,B]=A\circ B-B\circ A$.

::: proposition
**Proposition 23**. *Let $(V,\langle\ ,\ \rangle,I)$ be as above.
Consider the following three linear operators on $\bigwedge^* V^*$:
$L,\ \varLambda,\ H$. They
satisfy:$$[H,L]=2L,[H,\varLambda]=-2\varLambda,[L,\varLambda]=H.$$*
:::

::: corollary
**Corollary 24**. *$(V,\langle\ ,\ \rangle,I)$. The action of
$L,\varLambda,H$ defines a natural
$\mathfrak{sl}(2,\mathbb{R})$-representation on $\bigwedge^* V^*$.The
$\mathfrak{sl}(2,\mathbb{C})$-representation is obtained by tensorizing
with $\mathbb{C}$.*
:::

::: definition
**Definition 25**. *$(V,\langle\ ,\ \rangle,I)$. An element
$\alpha\in\bigwedge^k V^*$ is called **primitive** if
$\varLambda\alpha=0$. The linear subspace of all primitve elements
$\alpha\in\bigwedge^k V^*$ is denoted by $P^k\subset\bigwedge^k V^*$.*
:::

Accordingly, an element $\alpha\in\bigwedge^k V_{\mathbb{C}}^*$ is
called primitive if $\varLambda\alpha=0$. Clearly the subspace of those
is just the complexification of $P^k$.

::: {#prd .proposition}
**Proposition 26**. *$(V,\langle\ ,\ \rangle,I)$, dimension $2n$.*

(i) *Lefschetz
    decomposition:$$\bigwedge\nolimits^k V^*=\bigoplus_{i\geqslant 0}L^i(P^{k-2i}).$$The
    decomposition is orthogonal with respect to $\langle\ ,\ \rangle$.*

(ii) *If $k>n$, $P^k=0$.*

(iii) *$L^{n-k}:P^k\rightarrow \bigwedge^{2n-k}V^*$ is injective for
      $k\leqslant n$.*

(iv) *$L^{n-k}:\bigwedge^k V^*\rightarrow \bigwedge^{2n-k}V^*$ is
     bijective for $k\leqslant n$.*

(v) *If $k\leqslant n$, then
    $P^k=\{\alpha\in\bigwedge^k V^*\mid L^{n-k+1}\alpha=0\}$.*
:::

::: proof
*Proof.* Use the theory of representation of
$\mathfrak{sl}(2,\mathbb{R})$. ◻
:::

::: remark
**Remark 27**. *Since $L,\varLambda,H$ are of pure type
$(1,1),(-1,-1),(0,0)$, respectively, and the Lefschetz decomposition is
compatible with the bidegree decomposition. Thus,
$P^k_{\mathbb{C}}=\bigoplus_{p+q=k}P^{p,q}$, where
$P^{p,q}=P^k_{\mathbb{C}}\cap\bigwedge^{p,q}V^*$. Since $\varLambda,L$
are real, one also has $\overline{P^{p,q}}=P^{q,p}$.*
:::

# Complex Structures on Manifolds

## Local Situtation

A real manifold $M$ is studied by means of its tangent bundle $TM$, the
collection of all tangent spaces $T_x M$ for $x\in M$, and its $k$-form
bundle $\bigwedge^k T^* M$. We now apply the linear algebra developed
previously to the form bundles of an open subset $M=U\in\mathbb{C}^n$.

Let $U\in\mathbb{C}^n$ be an open subset. Thus, $U$ can in particular be
considered as a $2n$-dimensional real manifold. For $x\in U$ we have its
real tangent space $T_x U$ at the point $x$ which is of real dimension
$2n$. A canonical basis of $T_x U$ is given by the tangent
vectors$$\frac{\partial}{\partial x_1},\dots,\frac{\partial}{\partial x_n},\frac{\partial}{\partial y_1},\dots,\frac{\partial}{\partial y_n},$$where
$z_1=x_1+iy_1,\dots,z_n=x_n+iy_n$ are the standard coordinates on
$\mathbb{C}^n$. Moreover, the vectors
$\frac{\partial}{\partial x_1},\dots,\frac{\partial}{\partial y_n}$ are
global trivializing setctions of $TU$.

Each tangent space $T_x U$ admits a natural almost complex structure
defined
by$$I:T_x U\rightarrow T_x U,\ \frac{\partial}{\partial x_i}\mapsto\frac{\partial}{\partial y_i},\ \frac{\partial}{\partial y_i}\mapsto -\frac{\partial}{\partial x_i},$$which
is compatible with the global trivialization. We shall regard $I$ as a
vector bundle endomorphism of the real vector bundle $TU$ over $U$.

The dual basis of $T_x^* U$ is denoted by
$dx_1,\dots,dx_n,dy_1,\dots,dy_n$. Recall that the induced almost
complex structure on $T_x^* U$ in terms of this dual basis is described
by $I(dx_i)=-dy_i,\ I(dy_i)=dx_i$.

Previous result yields the following

::: proposition
**Proposition 28**. *The complexified tangent bundle
$T_{\mathbb{C}}U:=TU\otimes\mathbb{C}$ decomposes as a direct sum of
complex vector bundles$$T_{\mathbb{C}}U=TU^{1,0}\oplus TU^{0,1},$$such
that the complex linear extension of $I$
statisfies$$I|_{TU^{1,0}}=i\cdot\mathrm{id}\ and\ I|_{TU^{0,1}}=-i\cdot\mathrm{id}.$$The
vector bundles $TU^{1,0}$ and $TU^{0,1}$ are trivialized by the sections
$\frac{\partial}{\partial z_i}:=\frac{1}{2}(\frac{\partial}{\partial x_i}-i\frac{\partial}{\partial y_i})$
and
$\frac{\partial}{\partial\bar{z_i}}:=\frac{1}{2}(\frac{\partial}{\partial x_i}+i\frac{\partial}{\partial y_i})$,
$i=1,\dots,n$, respectively.*
:::

The complexified bundle $T_{\mathbb{C}}^* U:=T^* U\otimes\mathbb{C}$
admits an analogous decomposition
$T_{\mathbb{C}}^* U=T^* U^{1,0}\oplus T^* U^{0,1}$ and $T^* U^{1,0}$ and
$T^* U^{0,1}$ are trivialized by the dual basis $dz_i:=dx_i+idy_i$ and
$d\bar{z}_i:=dx_i-idy_i$, $i=1,\dots,n$, respectively.

::: definition
**Definition 29**. *Let $U\in\mathbb{C}^n$ be an open
subset.$$\bigwedge\nolimits^{k}_{\mathbb{C}}U:=\bigwedge\nolimits^{k} T_{\mathbb{C}}^* U,\ \bigwedge\nolimits^{p,q}U:=(\bigwedge\nolimits^p T^* U^{1,0})\otimes_{\mathbb{C}}(\bigwedge\nolimits^q T^* U^{0,1}).$$By
$\mathcal{A}^{k}_{\mathbb{C}}(U)$ and $\mathcal{A}^{p,q}(U)$ we donted
the spaces of sections of $\bigwedge^{k}_{\mathbb{C}}U$ and
$\bigwedge^{p,q} U$, respectively.*
:::

::: corollary
**Corollary 30**. *There are natural decompositions
$\bigwedge^{k}_{\mathbb{C}}U=\oplus_{p+q=k}\bigwedge^{p,q}U$ and
$\mathcal{A}^{k}_{\mathbb{C}}(U)=\oplus_{p+q=k}\mathcal{A}^{p,q}(U)$.*
:::

As before, the projection operators will be donoted by $\varPi^{p,q}$.

::: definition
**Definition 31**. *Let
$d:\mathcal{A}^{k}_{\mathbb{C}}(U)\rightarrow\mathcal{A}^{k+1}_{\mathbb{C}}(U)$
be the complex linear extension of the usual exterior differential.
Then$$\partial: \mathcal{A}^{p,q}(U)\longrightarrow\mathcal{A}^{p+1,q}(U)\ and\ \bar{\partial}:\mathcal{A}^{p,q}(U)\longrightarrow\mathcal{A}^{p,q+1}(U)$$are
defined as $\partial:\varPi^{p+1,q}\circ d$ and
$\bar{\partial}:\varPi^{p,q+1}\circ d$.*
:::

For any local function $f$ one
has$$df=\sum_{i}\frac{\partial f}{\partial x_i}dx_i+\sum_{i}\frac{\partial f}{\partial y_i}dy_i=\sum_{i}\frac{\partial f}{\partial z_i}dz_i+\sum_{i}\frac{\partial f}{\partial \bar{z}_i}d\bar{z}_i.$$

::: lemma
**Lemma 32**.

(i) *$d=\partial+\bar{\partial}.$*

(ii) *$\partial^{2}=\bar{\partial}^{2}=0,\ \partial\bar{\partial}=-\bar{\partial}\partial.$*

(iii) *$$\partial(\alpha\wedge\beta)=\partial(\alpha)\wedge\beta+(-1)^{p+q}\alpha\wedge\partial(\beta),\ \bar{\partial}(\alpha\wedge\beta)=\bar{\partial}(\alpha)\wedge\beta+(-1)^{p+q}\alpha\wedge\bar{\partial}(\beta)$$for
      $\alpha\in\mathcal{A}^{p,q}(U)$ and
      $\beta\in\mathcal{A}^{r,s}(U)$.*
:::

In the following, $B$ shall denote a polydisc $B_{\varepsilon}$ which
can be unbounded, i.e. $\varepsilon_{i}=\infty$ is allowed.[^4]

::: {#plm .lemma}
**Lemma 33**. ***($\bar{\partial}$-Poincaré lemma on the open disc)** If
$\alpha\in\mathcal{A}^{p,q}(B)$ is $\bar{\partial}$-closed and $q>0$,
then there exists $\beta\in\mathcal{A}^{p,q-1}(B)$ with
$\alpha=\bar{\partial}\beta$.*
:::

## Global Situation

::: definition
**Definition 34**. *An **almost complex manifold** is a differentiable
manifold $X$ together with a vector bundle
endomorphism$$I:TX\longrightarrow TX,\ with\ I^2=-\mathrm{id}.$$Here,
$TX$ is the real tangent bundle of the underlying real manifold. $I$ is
called the **almost complex structure** on $X$.*
:::

::: proposition
**Proposition 35**. *Any complex manifold $X$[^5] admits a natural
almost complex structure.*
:::

::: remark
**Remark 36**. *Not every real manifold of even dimension admits an
almost complex structure.*
:::

$T_{\mathbb{C}}X:=TX\otimes\mathbb{C}$. We emphasize that even for a
complex manifold $X$ the bundle $T_{\mathbb{C}}X$ is a priori just a
complex vector bundle without a holomorphic structure.

::: proposition
**Proposition 37**.

(i) *Let $X$ be an almost complex manifold.
    Then$$T_{\mathbb{C}}X=TX^{1,0}\oplus TX^{0,1}.$$And$$I|_{TX^{1,0}}=i\cdot\mathrm{id}\ and\ I|_{TX^{0,1}}=-i\cdot\mathrm{id}.$$*

(ii) *If $X$ is a complex manifold, then $T^{1,0}X$ is naturally
     isomorphic (as a complex vector bundle) to the holomorphic tangent
     bundle $\mathcal{T}_X$.*
:::

::: definition
**Definition 38**. *The bundles $T^{1,0}X$ and $T^{0,1}X$ are called the
**holomorphic** respectively the **antiholomorphic tangent bundle** of
the (almost) complex manifold $X$.*
:::

We tacitly use the isomorphism of vector bundles:
$(TX^{1,0})^*\cong(T^*X)^{1,0},\ (TX^{0,1})^*\cong(T^*X)^{0,1}$.

::: definition
**Definition 39**. *Let $X$ be an almost complex
manifold.$$\bigwedge\nolimits^{k}_{\mathbb{C}}X:=\bigwedge\nolimits^{k} T_{\mathbb{C}}^* X,\ \bigwedge\nolimits^{p,q}X:=(\bigwedge\nolimits^p T^* X^{1,0})\otimes_{\mathbb{C}}(\bigwedge\nolimits^q T^* X^{0,1}).$$Their
sheaves of sections are denoted by $\mathcal{A}^{k}_{X,\mathbb{C}}$ and
$\mathcal{A}^{p,q}_{X}$, respectively. Elements in
$\mathcal{A}^{p,q}_{X}(X)$, i.e. global sections of
$\mathcal{A}^{p,q}_{X}$, are called forms of type (or bidegree)
$(p,q)$.*
:::

::: {#decom .proposition}
**Proposition 40**. *There exists a natural direct sum
decomposition$$\bigwedge\nolimits^k_{\mathbb{C}}X=\bigoplus_{p+q=k}\bigwedge\nolimits^{p,q}X\ and\ \mathcal{A}^k_{X,\mathbb{C}}=\bigoplus_{p+q=k}\mathcal{A}_{X}^{p,q}.$$*
:::

**Projections**
$\varPi^{k}:=\mathcal{A}^*_{X,\mathbb{C}}\rightarrow\mathcal{A}^{k}_{X,\mathbb{C}}$
and
$\varPi^{p,q}:=\mathcal{A}^*_{X,\mathbb{C}}\rightarrow\mathcal{A}^{p,q}_{X}$.

::: definition
**Definition 41**. *$X$ almost complex manifold.
$d:\mathcal{A}^{k}_{X,\mathbb{C}}\rightarrow\mathcal{A}^{k+1}_{X,\mathbb{C}}$
is the $\mathbb{C}$-linear extension of the exterior differential,
then$$\partial:=\varPi^{p+1,q}\circ d:\mathcal{A}^{p,q}_{X}\longrightarrow\mathcal{A}^{p+1,q}_{X},\ \bar{\partial}:=\varPi^{p,q+1}\circ d:\mathcal{A}^{p,q}_{X}\longrightarrow\mathcal{A}^{p,q+1}_{X}.$$*
:::

As above,
$\partial(\alpha\wedge\beta)=\partial(\alpha)\wedge\beta+(-1)^{p+q}\alpha\wedge\partial(\beta)$
holds, so does $\bar{\partial}$.

**Bundles of holomorphic $p$-forms**: $\varOmega^p_X$.

::: {#abc .proposition}
**Proposition 42**. *The space $H^0(X,\varOmega^p_X)$ of holomorphic
$p$-forms on a complex manifold $X$ is the subspace
$\{\alpha\in \mathcal{A}^{p,0}_X(X)\mid \bar{\partial}\alpha=0\}$.*
:::

We next wish to discuss what an almost complex structure needs in order
to be induced by a complex one.

::: proposition
**Proposition 43**. *$X$ almost complex manifold. Then the following two
conditions are equivalent:*

(i) *$d\alpha=\partial(\alpha)+\bar{\partial}(\alpha),\ \forall\alpha\in\mathcal{A}^*_{X,\mathbb{C}}(X).$*

(ii) *On $\mathcal{A}^{1,0}_{X,\mathbb{C}}(X)$ one has
     $\varPi^{0,2}\circ d=0$.*

*Both conditions hold true if $X$ is a complex manifold.*
:::

::: definition
**Definition 44**. *An almost complex structure $I$ on $X$ is called
**integrable** if above two equivalent conditions are satisfied.*
:::

::: proposition
**Proposition 45**. *If $I$ is an integrable almost complex structure,
then $\partial^2=\bar{\partial}^2=0$ and
$\partial\bar{\partial}=-\bar{\partial}\partial$.*
:::

::: theorem
**Theorem 46**. ***(Newlander-Nierenberg)** Any integrable almost
complex structure is induced by a complex structure.*
:::

Thus, complex manifolds and differentiable manifolds endowed with an
integrable almost complex structure are describing the same geometrical
object!

::: definition
**Definition 47**. *$X$, endowed with an almost complex structure. Then
the **(p,q)-Dolbeault cohomology** is the vector
space$$H^{p,q}(X):=H^q(\mathcal{A}^{p,\bullet}_X(X),\bar{\partial})=\frac{\mathrm{Ker}(\bar{\partial}:\mathcal{A}^{p,q}_X(X)\rightarrow\mathcal{A}^{p,q+1}_X(X))}{\mathrm{Im}(\bar{\partial}:\mathcal{A}^{p,q-1}_X(X)\rightarrow\mathcal{A}^{p,q}_X(X))}.$$*
:::

By $\bar{\partial}$-Poincaré lemma [33](#plm){reference-type="ref"
reference="plm"} and [42](#abc){reference-type="ref" reference="abc"} we
have the following exact sequence of sheaves on
$X$:$$0\longrightarrow\varOmega^{p}_X\longrightarrow\mathcal{A}^{p,0}_X\longrightarrow\mathcal{A}^{p,1}_X\longrightarrow\dots.$$

::: lemma
**Lemma 48**.
*$H^k(X,\mathcal{A}^{p,q}_X)=0,\ \forall k>0,p\geqslant 0,q\geqslant 0.$*
:::

::: proposition
**Proposition 49**. *The Dolbeault cohomology of $X$ computes the
cohomology of the sheaf $\varOmega^P_X$:
$H^{p,q}(X)\cong H^q(X,\varOmega^p_X)$.*
:::

# Kähler Manifolds

## Kähler Identities

Let $X$ be a complex manifold. We donote the induced almost complex
structure by $I$. A local version of the following definition has
already been discussed in Section 1.2.

::: definition
**Definition 50**. *A Riemann metric $g$ on $X$ is an **hermitian
structure** on $X$ if $\ \forall x\in X$ the scalar product $g_x$ on
$T_x X$ is compatible with the almost complex structure $I_x$. The
induced real $(1,1)$-form $\omega:=g(I(\ ),(\ ))$ is called the
**fundamental form**.*
:::

It can be computed that locally the fundamental form $\omega$ if of the
form$$\omega=\frac{i}{2}\sum_{i,j=1}^n h_{ij}dz_i\wedge d\bar{z}_j,$$where
$\forall x\in X$ the matrix $(h_{ij}(x))$ is a positive definite
hermitian matrix. The complex manifold $X$ endowed with an hermitian
structure $g$ is called an **hermitian manifold**. Note that the
hermitian structure $g$ is uniquely determined by $I$ and $\omega$:
$g(\ ,\ )=\omega(\ ,I(\ ))$.

In analogy to the theory developed in Section 1.2, one defines the
following vector bundle homomorphisms on any hermitian manifolds of
complex dimension $n$:

(i) The **Lefschetz
    operator**$$L:\bigwedge\nolimits^k X\rightarrow \bigwedge\nolimits^{k+2}X,\ \mathcal{A}^{k}_X\rightarrow\mathcal{A}^{k+2}_X,\ \alpha\rightarrow\alpha\wedge\omega$$is
    an operator of degree $2$, bidegree $(1,1)$.

(ii) The **Hodge
     $*$-operator**$$*:\bigwedge\nolimits^k X\rightarrow \bigwedge\nolimits^{2n-k}X,\ \mathcal{A}^k_X\rightarrow\mathcal{A}^{2n-k}_X,\ \mathcal{A}^{p,q}_X\rightarrow\mathcal{A}^{n-q,n-p}_X$$is
     induced by the metric $g$ and the natural orientation of the
     complex manifold $X$. Here, $2n$ is the real dimension of $X$.

(iii) The **dual Lefschetz
      operator**$$\varLambda:=*^{-1}\circ L\circ *:\bigwedge\nolimits^k X\rightarrow\bigwedge\nolimits^{k-2}X,\ \mathcal{A}^k_X\rightarrow\mathcal{A}^{k-2}_X$$is
      an operator of degree $-2$ and depneds on the Kähler form $\omega$
      and the metric $g$.

All three operators can be extended $\mathbb{C}$-linearly to the
complexified bundles $\bigwedge^k_{\mathbb{C}}X$. By abuse of notation,
those will again be called $L,*,\varLambda$, respectively.Also, **Keep
in mind the connection between vector bundles and locally free
sheaves.**

$P^{k}X:=\mathrm{Ker}(\varLambda:\bigwedge^{k}X\rightarrow\bigwedge^{k-2}X)$,
$P^k_{\mathbb{C}}X:=\mathrm{Ker}(\varLambda:\bigwedge^{k}_{\mathbb{C}}X\rightarrow\bigwedge^{k-2}_{\mathbb{C}}X)$.

::: corollary
**Corollary 51**. *$(X,g)$ hermitian manifold. Then*

(i) *$$\bigwedge\nolimits^k X=\bigoplus_{i\geqslant 0} L^i(P^{k-2i}X)$$*

(ii) *$$\bigwedge\nolimits^k_{\mathbb{C}} X=\bigoplus_{i\geqslant 0}L^i(P^{k-2i}_{\mathbb{C}}X)$$*

(iii) *$$P^k_{\mathbb{C}}X=\bigoplus_{p+q=k}P^{p,q}X$$*

(iv) *$$\bigwedge\nolimits^{p,q}X=\bigoplus_{i\geqslant 0}L^i(P^{p-i,q-i}X)$$*
:::

Recall [40](#decom){reference-type="ref" reference="decom"}.
Then$$H:=\sum^{2n}_{k=0}(k-n)\cdot\varPi^k,\ \mathrm{\mathbf{I}}=\sum^{n}_{p,q=0}i^{p-q}\cdot\varPi^{p,q}.$$And
$\mathrm{\mathbf{I}}$ is also in fact a real operator on
$\mathcal{A}^*_X$ (cf. [8](#rop){reference-type="ref" reference="rop"}).

We now pass from linear operators to differential operators. On an
Hermitian manifold $(X,g)$ the **adjoint operator $d^*$** is defined as
$$d^*=-*\circ\ d\circ *:\mathcal{A}^k_{X,\mathbb{C}}\rightarrow \mathcal{A}^{k-1}_{X,\mathbb{C}}$$and
the **Laplace operator** is given
by$$\varDelta=d^* d+dd^*.$$Analogously, we have

::: definition
**Definition 52**. *$(X,g)$.
$$\partial^*:=-*\circ \bar{\partial}\circ *,\ \mathcal{A}^{p,q}_X\rightarrow\mathcal{A}^{p-1,q}_X;\ \bar{\partial}^*:=-*\circ\partial\circ *,\ \mathcal{A}^{p,q}_X\rightarrow\mathcal{A}^{p,q-1}_X.$$*
:::

::: lemma
**Lemma 53**.
*$d^*=\partial^*+\bar{\partial}^*,\ \partial^2=\bar{\partial}^{*2}=0.$*
:::

::: definition
**Definition 54**.
*$(X,g)$.$$\varDelta_{\partial}:=\partial^* \partial+\partial\partial^*,\ \mathcal{A}^{p,q}_X\rightarrow\mathcal{A}^{p,q}_X;\ \varDelta_{\bar{\partial}}:=\bar{\partial}^*\bar{\partial}+\bar{\partial}\bar{\partial}^*,\ \mathcal{A}^{p,q}_X\rightarrow\mathcal{A}^{p,q}_X.$$*
:::

All these linear and differential operators behave especially well if a
further compatibility condition on the Riemann metric and the complex
structure is imposed. This is the famous Kähler condition formulated for
the first time by Kähler.

::: definition
**Definition 55**. *A **Kähler structure** (or **Kähler metric**) is an
hermitian structure $g$ for which the fundamental form $\omega$ is
closed, i.e. $d\omega=0$. In this case, the fundamental form $\omega$ is
called the **Kähler form**.*
:::

The complex manifold endowed with the Kähler structure is called a
**Kähler manifold**. Generally, when a complex manifold admits Kähler
structures which may be without actually fixing one, we call it a Kähler
manifold.

::: remark
**Remark 56**. *Kähler structures do not always exist.*
:::

::: example
**Example 57**. *Projective manifolds are Kähler.*
:::

::: proposition
**Proposition 58**. ***(Kähler identities)** $(X,g)$ a Kähler manifold.*

(i) *$[\bar{\partial},L]=[\partial,L]=0,\ [\partial^*,\varLambda]=[\bar{\partial}^*,\varLambda]=0.$*

(ii) *$[\bar{\partial}^*,L]=i\partial,\ [\partial^*,L]=-i\bar{\partial};\ [\varLambda,\bar{\partial}]=-i\partial^*,\ [\varLambda,\partial]=i\bar{\partial}^*.$*

(iii) *$\varDelta_{\partial}=\varDelta_{\bar{\partial}}=\frac{1}{2}\varDelta$
      and $\varDelta$ commutes with
      $*,\ \partial,\ \bar{\partial},\ \partial^*,\ \bar{\partial}^*,\ L,\ \varLambda$.*
:::

## Hodge structures

Let's digeress a bit and talk about the general Hodge structures. We are
interested in rational and integral Hodge structures. In this
subsection, $V$ always stands for either a free $\mathbb{Z}$-module of
finite rank or a finite-dimensional vector space over $\mathbb{Q}$. By
$V_{\mathbb{R}}$ and $V_{\mathbb{C}}$ we dontoe the real and complex
vector spaces obtained by scalar extension. And we consider
$V_{\mathbb{C}}$ as a complex vector space with almost complex structure
induced by multiplying $i$.

::: definition
**Definition 59**. *A **Hodge structure of weight $n\in \mathbb{Z}$** on
$V$ is given by a direct sum decomposition of the complex vector space
$V_{\mathbb{C}}$$$V_{\mathbb{C}}=\bigoplus_{p+q=n}V^{p,q}$$such that
$\overline{V^{p,q}}=V^{q,p}$.*
:::

Note that $n$ can be negetive!

For a Hodge structure $V$ (integral or rational) of even weight $n=2k$
the intersection $V\cap V^{k,k}$ is called the space of **Hodge
classes** in $V$.

::: definition
**Definition 60**. *A **sub-Hodge structure** of a Hodge structure $V$
of weight $n$ is given by a $\mathbb{Q}$-linear subspace (resp.
submodule) $V'\subset V$ such tha the Hodge structure on $V$ induces a
Hodge structure on $V'$, i.e.
$V_{\mathbb{C}}'=\bigoplus(V_{\mathbb{C}}'\cap V^{p,q})$.*

*A sub-Hodge structure $V'\subset V$ of an integral Hodge structure $V$
is called primitive if $V/V'$ is torsion free. Any Hodge structure that
doesn't contain any non-trivial proper and primitive (in the integral
case) Hodge structure $V'\subset V$ is called **irreducible**.*
:::

::: example
**Example 61**. *The **Tate Hodge structure**
$\mathbb{Z}(1):= (2\pi i)\mathbb{Z}$ is the Hodge structure of weight
$-2$, on which
$\mathbb{Z}(1)_{\mathbb{C}}=\mathbb{C}=\mathbb{Z}(1)^{-1,-1}$. So
$\mathbb{Z}(1)^{-2,0}$, $\mathbb{Z}(1)^{0,-2}$ and all other components
are all zero. Similarly, one defines the rational Tate Hodge structure
$\mathbb{Q}(1)$.*
:::

Most of the standard linear algebra constructions have analogues in
Hodge theory.

(i) The **direct sum** $V\oplus W$ of two Hodge structures $V$ and $W$
    of the same weight $n$ is endowed again with a Hodge structure of
    weight $n$ by setting$$(V\oplus W)^{p,q}=V^{p,q}\oplus W^{p,q}.$$

(ii) The **tensor product** $V\otimes W$ of Hodge structures $V$ and $W$
     of weight $n$ and $m$, respectively, comes naturally with a Hodge
     structure of weight $n+m$ by
     putting$$(V\otimes W)^{p,q}=\bigoplus_{p_1+p_2=p,q_1+q_2=q}V^{p_1,q_1}\otimes W^{p_2,q_2}.$$

(iii) For a Hodge structure $V$ of weight $n$, one defines a Hdoge
      structure of weight $-n$ on the dual
      $V^*:=\mathrm{Hom}_{\mathbb{Z}}(V,\mathbb{Z})$ (or
      $=\mathrm{Hom}_{\mathbb{Q}}(V,\mathbb{Q})$ if $V$ is rational)
      by$$V^{*-p,-q}:=\mathrm{Hom}_{\mathbb{C}}(V^{p,q},\mathbb{C})\subset \mathrm{Hom}_{\mathbb{C}}(V_{\mathbb{C}},\mathbb{C})=V^*_{\mathbb{C}}.$$

::: example
**Example 62**. *Applying to the Tate Hodge structure, we get the Hodge
structure $\mathbb{Z}(-1):=\mathbb{Z}(1)^*$ of weight $2$ and the Hodge
structures $\mathbb{Z}(k):=\mathbb{Z}(1)^{\otimes k}$ for $k>0$ and
$\mathbb{Z}(k):=\mathbb{Z}(-1)^{\otimes -k}$ for $k<0$, which are of
weight $-2k$. Explicitly,
$\mathbb{Z}(k)_{\mathbb{C}}=\mathbb{C}=\mathbb{Z}(k)^{-k,-k}$, with
other components being zero.*

*For an arbitrary integral or rational Hodge structure $V$ of weight $n$
one defines the Hodge structure of weight
$n-2k$$$V(k):=V\otimes \mathbb{Z}(k)\ or\ V(k):=V\otimes \mathbb{Q}(k)$$respectively,
for which $V(k)^{p,q}=V^{p+k,q+k}$.*
:::

## Hodge Theory on Kähler Manifolds

In this section we will focus on compact hermitian and Kähler manifolds.
The compactness allows us to apply Hodge theory for real manifolds.

If $X$ is a complex manifold with an hermitian structure $g$, we denote
the hermitian extension of $g$ to $\bigwedge^*_{\mathbb{C}}X$ by
$g_{\mathbb{C}}$ (cf. [10](#gc){reference-type="ref" reference="gc"} and
footnote [3](#dual){reference-type="ref" reference="dual"}).

::: definition
**Definition 63**. *$(X,g)$ a compact hermitian manifold. Define a
**hermitian product** on $\mathcal{A}^*_{X,\mathbb{C}}(X)$
by$$(\alpha,\beta):=\int_{X} g_{\mathbb{C}}(\alpha,\beta)*\mathrm{1}.$$*
:::

::: proposition
**Proposition 64**. *$(X,g)$. Following decompositions are orthogonal
with respect to $(\ ,\ )$:*

(i) *$\mathcal{A}^*_{X,\mathbb{C}}(X)=\bigoplus_k\mathcal{A}^k_{X,\mathbb{C}}(X)$*

(ii) *$\mathcal{A}^k_{X,\mathbb{C}}=\bigoplus_{p+q=k}\mathcal{A}^{p,q}_{X}(X)$*

(iii) *$\mathcal{A}^k_{X,\mathbb{C}}(X)=\bigoplus_{i\geqslant 0}L^i \mathcal{P}^{k-2i}_{X,\mathbb{C}}(X).$*

*Here $\mathcal{P}^k_{X,\mathbb{C}}$ is the sheaf of complex primitve
$k$-form on $X$.*
:::

::: lemma
**Lemma 65**. *$(X,g)$. Then with respect to hermitian product $(\ ,\ )$
the operators $\partial^*,\ \bar{\partial}^*\ ,d^*$ are the formal
adjoints of $\partial,\ \bar{\partial},\ d$, respectively.*
:::

::: definition
**Definition 66**. *Let $(X,g)$ be an hermitian complex manifold. A form
$\alpha\in\mathcal{A}^k_{X,\mathbb{C}}(X)$ is called
**$\bar{\partial}$-harmonic** if $\varDelta_{\bar{\partial}}(\alpha)=0$.
Moreover,
$$\mathcal{H}^k_{\bar{\partial}}(X,g):=\{\alpha\in\mathcal{A}^k_{X,\mathbb{C}}(X)\mid \varDelta_{\bar{\partial}}(\alpha)=0\},\ \mathcal{H}^{p,q}_{\bar{\partial}}(X,g):=\{\alpha\in\mathcal{A}^{p,q}_{X}(X)\mid \varDelta_{\bar{\partial}}(\alpha)=0\}.$$
Analogously, **$\partial$-harmonic** forms,
$\mathcal{H}^k_{\partial}(X,g),\ \mathcal{H}^{p,q}_{\partial}(X,g)$ and
**(d-)harmonic** forms,
$\mathcal{H}^k(X,g):=\{\alpha\in\mathcal{A}^k_{X}(X)\mid \varDelta(\alpha)=0\},\ \mathcal{H}^k_{\mathbb{C}}(X,g):=\{\alpha\in\mathcal{A}^k_{X,\mathbb{C}}(X)\mid \varDelta(\alpha)=0\},\ \mathcal{H}^{p,q}(X,g):=\{\alpha\in\mathcal{A}^{p,q}_{X}(X)\mid \varDelta(\alpha)=0\}$.*
:::

::: {#aaa .lemma}
**Lemma 67**. *$(X,g)$ a compact hermitian manifold. A form $\alpha$ is
$\bar{\partial}$-harmonic (resp. $\partial$-harmonic, harmonic) if and
only if $\bar{\partial}\alpha=\bar{\partial}^*\alpha=0$ (resp.
$\partial\alpha=\partial^*\alpha=0$, $d\alpha=d^*\alpha=0$).*
:::

::: proof
*Proof.*
$(\varDelta_{\bar{\partial}}(\alpha),\alpha)=\|\bar{\partial}^*(\alpha)\|^2+\|\bar{\partial}(\alpha)\|^2$. ◻
:::

::: proposition
**Proposition 68**. *$(x,g)$ an hermitian manifold, not necessarily
compact. Then*

(i) *$\mathcal{H}^k_{\bar{\partial}}(X,g)=\bigoplus_{p+q=k}\mathcal{H}^{p,q}_{\bar{\partial}}(X,g),\ \mathcal{H}^k_{\partial}(X,g)=\bigoplus_{p+q=k}\mathcal{H}^{p,q}_{\partial}(X,g)$.*

(ii) *If $(X,g)$ is Kähler then
     $\mathcal{H}^{p,q}_{\partial}(X,g)=\mathcal{H}^{p,q}_{\bar{\partial}}(X,g)=\mathcal{H}^{p,q}(X,g)$,
     $\mathcal{H}^k_{\bar{\partial}}(X,g)=\mathcal{H}^k_{\partial}(X,g)=\mathcal{H}^k_{\mathbb{C}}(X,g)$
     and
     $\mathcal{H}^k_{\mathbb{C}}(X,g)=\bigoplus_{p+q=k}\mathcal{H}^{p,q}(X,g)$.*
:::

::: remark
**Remark 69**. *For an arbitrary hermitian manifold, the bidegeree
decomposition of $\mathcal{H}^{k}_{\mathbb{C}}(X,g)$ may not hold.*
:::

::: {#sd .remark}
**Remark 70**.

(i) *Let $(X,g)$ be an hermitian manifold, not necessarily compact. Then
    by calculation we get $*$ is commutative with $\varDelta$. Using
    this, $*$ induces $\mathbb{C}$-linear
    isomorphism$$*:\mathcal{H}^{p,q}(X,g)\cong\mathcal{H}^{n-q,n-p}(X,g).$$Also
    note that complex conjugation interchange $\mathcal{H}^{p,q}(X,g)$
    and $\mathcal{H}^{q,p}(X,g)$.*

(ii) *Let $(X,g)$ be a compact hermitian manifold. Then the
     pairing$$\mathcal{H}^{p,q}(X,g)\times\mathcal{H}^{n-p,n-q}(X,g)\longrightarrow \mathbb{C},\ (\alpha,\beta)\longmapsto\int\nolimits_{X}\alpha\wedge\beta$$is
     non-degenerate. Indeed, if $0\neq\alpha\in\mathcal{H}^{p,q}(X,g)$
     then $*\bar{\alpha}\in\mathcal{H}^{n-p,n-q}(X,g)$ and
     $\int\alpha\wedge*\bar{\alpha}=\|\alpha\|^2>0$. This yields **Serre
     duality** on the level of harmonic
     forms:$$\mathcal{H}^{p,q}(X,g)\cong\mathcal{H}^{n-p,n-q}(X,g)^*.$$*

(iii) *If $(X,g)$ is a (possibly non-compact) Kähler manifold of complex
      dimension $n$, then for
      $\forall k\geqslant n,\ 0\geqslant p\geqslant k$, the Lefschetz
      operator induces an
      isomorphism$$L^{n-k}:\mathcal{H}^{p,k-p}(X,g)\cong\mathcal{H}^{n-k+p,n-p}(X,g).$$Here
      one uses $[L,\varDelta]=0$, $[\varLambda,\varDelta]=0$ and some
      representation theory to prove the bijection. However, we cannot
      expect anything for arbitrary hermitian manifolds, as the product
      of an harmonic form with the fundamental form will hardly be
      closed (let alone harmonic) if the fundamental form is not
      closed.*
:::

::: theorem
**Theorem 71**. ***(Hodge decomposition)** Let $(X,g)$ be a compact
hermitian manifold. Then there exist two natural orthogonal
decompositions$$\mathcal{A}^{p,q}_{X}(X)=\partial\mathcal{A}^{p,q-1}_{X}(X)\oplus\mathcal{H}^{p,q}_{\partial}(X,g)\oplus\partial^*\mathcal{A}^{p+1,q}_{X}(X)$$and$$\mathcal{A}^{p,q}_{X}(X)=\bar{\partial}\mathcal{A}^{p,q-1}_{X}(X)\oplus\mathcal{H}^{p,q}_{\partial}(X,g)\oplus\bar{\partial}^*\mathcal{A}^{p+1,q}_{X}(X).$$*
:::

Whereas the orthogonality of the decomposition is easy to verify, the
crucial fact is the existence of the direct sum decomposition.

::: corollary
**Corollary 72**. *$(X,g)$ a compact hermitian manifold. Then the
canonical projection
$\mathcal{H}^{p,q}_{\bar{\partial}}(X,g)\rightarrow H^{p,q}(X)$ is an
isomorphism.*
:::

::: proof
*Proof.* Since any $\alpha\in\mathcal{H}^{p,q}_{\bar{\partial}}(X,g)$ is
$\bar{\partial}$-closed ([67](#aaa){reference-type="ref"
reference="aaa"}), mapping $\alpha$ to its Dolbeault cohomology class
$[\alpha]\in H^{p,q}(X)$ defines a map
$\mathcal{H}^{p,q}_{\bar{\partial}}(X,g)\rightarrow H^{p,q}(X)$.
Moreover,
$\mathrm{Ker}(\bar{\partial}:\mathcal{A}^{p,q}_{X}(X)\rightarrow\mathcal{A}^{p,q+1}_{X}(X))=\bar{\partial}(\mathcal{A}^{p,q-1}_{X})\oplus\mathcal{H}^{p,q}_{\bar{\partial}}(X,g)$,
as $\bar{\partial}\bar{\partial}^*\beta=0$ if and only if
$\bar{\partial}^*\beta=0$. Indeed,
$\bar{\partial}\bar{\partial}^*\beta=0$ implies
$0=(\bar{\partial}\bar{\partial}^*\beta,\beta)=\|\bar{\partial}^*\beta\|^2$.
Thus $\mathcal{H}^{p,q}_{\bar{\partial}}(X,g)\rightarrow H^{p,q}(X)$ is
an isomorphism. ◻
:::

::: corollary
**Corollary 73**. *Let $(X,g)$ be a compact Kähler manifold. Then there
exists a
decomposition$$H^k(X,\mathbb{C})=\bigoplus_{p+q=k}H^{p,q}(X).$$This
decomposition doesn't depend on the chosen Kähler structure. Moreover,
with respect to complex conjugation on
$H^*(X,C)=H^*(X,\mathbb{R})\otimes\mathbb{C}$ one has
$\overline{H^{p,q}(X)}=H^{q,p}(X)$ and Serre duality yields
$H^{p,q}(X)\cong H^{n-p,n-q}(X)^*$.*
:::

::: proof
*Proof.* The decomposition is induced
by$$H^k(X,\mathbb{C})=\mathcal{H}^k_{\mathbb{C}}(X,g)=\bigoplus_{p+q=k}\mathcal{H}^{p,q}(X,g)=\bigoplus_{p+q=k}H^{p,q}(X),$$which
a priori might depend on the Kähler metric $g$. Let $g'$ be a second
Kähler metric. The two groups $\mathcal{H}^{p,q}(X,g)$ and
$\mathcal{H}^{p,q}(X,g')$ are naturally identified by
$\mathcal{H}^{p,q}(X,g)\cong H^{p,q}(X)\cong \mathcal{H}^{p,q}(X,g')$.
Let $\alpha\in\mathcal{H}^{p,q}(X,g)$ and denote the corresponding
element in $\mathcal{H}^{p,q}(X,g')$ by $\alpha'$. We have to show that
the associated de Rham cohomology classes
$[\alpha],\ [\alpha']\in H^k(X,\mathbb{C})$ coincide.

Since $\alpha$ and $\alpha'$ induce the same element in $H^{p,q}(X)$,
they differ by some $\bar{\partial}\gamma$, i.e.
$\alpha'=\alpha+\bar{\partial}\gamma$. But then
$d\bar{\partial}\gamma=d(\alpha'-\alpha)=0$. Moreover,
$\bar{\partial}\gamma$ is orthogonal to
$\mathcal{H}^k_{\mathbb{C}}(X,g)$. By Hodge decomposition with respect
to the ordinary exterior differential $d$ this yields
$\bar{\partial}\gamma\in d(\mathcal{A}^{k-1}_{X,\mathbb{C}}(X))$. Thus,
$[\alpha]=[\alpha']\in H^k(X,\mathbb{C})$. For the second assertion
see [70](#sd){reference-type="ref" reference="sd"}. ◻
:::

## Lefschetz Theorems

Let $X$ be a compact Kähler manifold. $\mathcal{O}$ is the sheaf of
holomorphic functions on $X$. $\mathcal{O}^*$ is the sheaf of nowhere
vanishing holomorphic functions on $X$.

Recall that the exponential sequence is a natural short exact sequence
of
sheaves:$$0\longrightarrow \mathbb{Z}\longrightarrow\mathcal{O}\longrightarrow\mathcal{O}^*\longrightarrow 0.$$Take
the long exact sequence of sheaf cohomology we get a canonical boundary
map $Pic(X)\cong H^1(X,\mathcal{O}^*)\rightarrow H^2(X,\mathbb{Z})$
which can be composed with
$H^2(X,\mathbb{Z})\rightarrow H^2(X,\mathbb{C})$ induced by the
inclusion $\mathbb{Z}\subset\mathbb{C}$.

::: lemma
**Lemma 74**. *Let $X$ be a compact Kähler manifold. The two natural
maps $H^k(X,\mathbb{C})\rightarrow H^k(X,\mathcal{O})$, induced by
$\mathbb{C}\subset\mathcal{O}$, and
$H^k(X,\mathbb{C})\rightarrow H^{0,k}(X)$, given by the bidegree
decomposition, coincide.*
:::

So image of $Pic(X)$ in $H^2(X,\mathbb{C})$ is contained in
$\mathrm{Ker}(H^2(X,\mathbb{C})\rightarrow H^2(X,\mathcal{O}))=\mathrm{Ker}(\varPi^{0,2}:H^2(X,\mathbb{C})\rightarrow H^{0,2}(X))=H^{2,0}(X)\oplus H^{1,1}(X)$.

$$H^{1,1}(X,\mathbb{Z}):=\mathrm{Im}\big(H^2(X,\mathbb{Z})\longrightarrow H^2(X,\mathbb{C})\big)\cap H^{1,1}(X).$$

::: proposition
**Proposition 75**. ***(Lefschetz theorem on (1,1)-classes)** X a
compact Kähler manifold. Then $Pic(X)\rightarrow H^{1,1}(X,\mathbb{Z})$
is surjective.*
:::

::: corollary
**Corollary 76**. *Let $(X,g)$ be a compact Kähler manifold. Then the
Lefschetz operator $L$ adn its dual $\varLambda$ define natural
operators on
cohomology$$L: H^{p,q}(X)\longrightarrow H^{p+1,q+1}(X),\ \varLambda:H^{p,q}(X)\longrightarrow H^{p-1,q-1}(X).$$Moreover,
$L$ and $\varLambda$ only depend on the Kähler class
$[\omega]\in H^{1,1}(X)\cap H^2(X,\mathbb{R})$.*
:::

::: definition
**Definition 77**. *Let $(X,g)$ be a compact Kähler manifold. Then the
**primitive cohomology** is defined as
$$H^k_{\mathfrak{p}}(X,\mathbb{R}):=\mathrm{Ker}\big(\varLambda: H^k(X,\mathbb{R})\longrightarrow H^{k-2}(X,\mathbb{R})\big),\ H^k_{\mathfrak{p}}(X,\mathbb{C}):=\mathrm{Ker}\big(\varLambda: H^k(X,\mathbb{C})\longrightarrow H^{k-2}(X,\mathbb{C})\big)$$and$$H^{p,q}_{\mathfrak{p}}(X):=\mathrm{Ker}\big(\Lambda:H^{p,q}(X)\longrightarrow H^{p-1,q-1}(X)\big).$$*
:::

$\varLambda$ respects the bidegeree decomposition, so
$H^k_{\mathfrak{p}}(X,\mathbb{C})=\bigoplus_{p+q=k}H^{p,q}_{\mathfrak{p}}(X)$.

::: proposition
**Proposition 78**. ***(Hard Lefschetz theorem)** Let $(X,g)$ be a
compact Kähler manifold of complex dimension $n$. Then for
$k\leqslant n$$$L^{n-k}: H^k(X,\mathbb{R})\cong H^{2n-k}(X,\mathbb{R}),\ H^k(X,\mathbb{C})\cong H^{2n-k}(X,\mathbb{C})$$and
for
$\forall k$$$H^k(X,\mathbb{R})=\bigoplus_{i\geqslant 0}L^i H^{k-2i}_{\mathfrak{p}}(X,\mathbb{R}),\ H^k(X,\mathbb{C})=\bigoplus_{i\geqslant 0}L^i H^{k-2i}_{\mathfrak{p}}(X,\mathbb{C}).$$Besides,
both assertions respect the bidegree decomposition,
i.e.$$L^{n-k}:H^{p,q}(X)\cong H^{n-q,n-p}(X),\ H^{p,q}(X)=\bigoplus_{i\geqslant 0}L^i H^{p-i,q-i}_{\mathfrak{p}}(X).$$*
:::

::: proof
*Proof.* Consider on the level of harmonic forms
([70](#sd){reference-type="ref" reference="sd"}) and use previous
results ([26](#prd){reference-type="ref" reference="prd"}). ◻
:::

::: definition
**Definition 79**. ***Hodge numbers**
$h^{p,q}(X):=\mathrm{dim}_{\mathbb{C}}(H^{p,q}(X))$.*
:::

The Hodge numbers of a compact Kähler manifold $X$ of complex dimension
$n$ are visualized by the **Hodge diamond**, whose symmetry is given by
Serre duality, Hodge $*$-operator and conjugation.

## Polarized Hodge Structure

The intersection pairing on the middle primitive cohomology or more
geneally the Hodge-Riemann pairing with respect to a (rational or
integral) Kähler class is formalized by the notion of a polarization.

Now $V$ again stands for either a free $\mathbb{Z}$-module of finite
rank or a finite-dimensional vector space over $\mathbb{Q}$. For the
following we shall need the notion of the **Weil operator** $C$, which
acts on $V^{p,q}$ by multiplication with $i^{p-q}$. It clerly preserves
the real vector space $(V^{p,q}\oplus V^{q,p})\cap V_{\mathbb{R}}$.

::: definition
**Definition 80**. *A **polarization** of a rational Hodge structure $V$
of weight $n$ is a morphism of Hodge
structures$$\psi:V\otimes V\longrightarrow \mathbb{Q}(-n)$$such that its
$\mathbb{R}$-linear extension yields a positive definite symmetric
form$$(v,w)\longmapsto \psi(v,Cw)$$on the real part of
$V^{p,q}\oplus V^{q,p}$. Then $(V,\psi)$ is called a **polarized Hodge
structure**. A Hodge structure is called **polarizable** if it admits a
polarization. An isomorphism $V_1\cong V_2$ of Hodge structures that is
compatible with given polarization $\psi_1$ resp. $\psi_2$ is called a
**Hodge isometry**.*
:::

Note that $\psi$ as a morphism of Hodge structures is a pairing on $V$
whosse $\mathbb{C}$-linear extension has the property that
$\psi(v_1,v_2)=0$ for $v_i\in V^{p_i,q_i}$ except possibly when
$(p_1,q_1)=(q_2,p_2)$. Integral polarizations are defined analogously.

We come back to the Hodge structure $H^n(X,\mathbb{C})$ of a compact
Kähler manifold.

::: proposition
**Proposition 81**. ***(Hodge-Riemann bilinear relation)** Let $(X,g)$
be a compact Kähler manifold of complex dimension $d$ with Kähler class
$[\omega]$ and let $0\neq \alpha \in H^{p,q}_{\mathfrak{p}}(X)$.
Then$$i^{p-q}(-1)^{\frac{(p+q)(p+q-1)}{2}}\int\nolimits_X \alpha\wedge\bar{\alpha}\wedge[\omega]^{d-(p+q)}>0.$$*
:::

Then define on $H^n(X,\mathbb{C})$ with $n\leqslant d$ the
**Hodge-Riemann
pairing**$$(v,w)\longmapsto (-1)^{\frac{n(n-1)}{2}}\int\nolimits_{X}v\wedge \bar{w}\wedge [\omega]^{d-n},$$which
defines a polarization on $H^n_{\mathfrak{p}}(X,\mathbb{C})$.

To be consistent with the above definition, one should take suitable
$[\omega]\in H^2(X,\mathbb{Q})$ and make some argument changing the base
field from $\mathbb{C}$ to $\mathbb{Q}$. But in general rational Kähler
class may not exist, in this case we can only modify the above argument
from $\mathbb{C}$ to $\mathbb{R}$.

[^1]: *Here we indentify $(V,I)$ with $(V^{1,0},i)$.*

[^2]: Recall that in Complex Analysis, we have
    $\frac{\partial}{\partial z_i}=\frac{1}{2}(\frac{\partial}{\partial x_i}-i\frac{\partial}{\partial y_i})$
    and
    $\frac{\partial}{\partial \bar{z}_i}=\frac{1}{2}(\frac{\partial}{\partial x_i}+i\frac{\partial}{\partial y_i})$.
    I think this may help to understand the decomposition.

[^3]: From now on, the main object become to $\bigwedge^* V^*$ from
    $\bigwedge^* V$. Recall that if we have $\langle\ ,\ \rangle$ on $V$
    then there is a natural $\langle\ ,\ \rangle$ on $V^*$ therefore on
    $\bigwedge^* V^*$.[]{#dual label="dual"}

[^4]: $B_{\varepsilon}=\{(z_i)\in\mathbb{C}^n\mid |z_i|<\varepsilon_i,\ \forall i\}.$

[^5]: *Recall that transition maps on complex manifolds are all
    holomorphic.*
