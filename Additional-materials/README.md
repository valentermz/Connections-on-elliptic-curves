<!-- For correct rendering with Emacs: -->
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>

# Additional materials

The main notebook `../A-map-between-moduli-spaces.ipynb` follows the article closely. All computations are essentially performed over P1, and connections on C are represented by their pre-images under Phi.

The objective of `Universal-family-invariant.ipynb` is to perform the same computations for connections directly on C.
To do this, we work with a family of connections defining a 4-fold cover of the moduli space Con(C,T). This "universal" family is defined as the family of connections Nabla satisfying:

* Nabla is defined over a trivial rank 2 vector bundle.
* Nabla has two logarithmic poles over the points t1, t2 (with the same exponents).
* Nabla has two apparent singularities over a pair of poles in involution p1, p2 (with exponents +-1/2).
* Nabla is invariant under the elliptic involution iota : C ---> C.

Further, We choose coordinates z on the projectivized fibers such that:

* The parabolic over p1 corresponds to z=0,
* The parabolic over p2 corresponds to z=infinity,
* The parabolics over t1,t2 satisfy: z(t1)*z(t2) = 1.

Performin an elementary transformation at the apparent singularities brings the connection into a rank 2 bundle of the form `O(p1) + O(p2)` with poles only over `T = t1 + t2`. This represents a connection in Con(C,T).


### Push from C

In `Push-from-C/` we include computations for a different yet related construction: Instead of pulling back connections from P1 to C using the elliptic cover, we push rank 2 connections on C to obtain rank 4 connections on P1.

<!--Empty space at the bottom -->

&nbsp;

&nbsp;
