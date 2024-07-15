HMM is defined by (T(tau), O, O(omega)):
  T -> set of states, including starn & end states
  O -> set of observation symbols
  O(omega) -> transition and emission parameters a_u,v & b_u(o)

a_u,v = count(u,v)/count(u); count(u,v) -> number of observed transitions from u to v, count(u) -> number of times state u is observed
b_u(o) = count(u->o)/count(u); count(u->o) -> number of times observation o generated from u is observed

Estimate of a_u,v (transition parameter):

$$\prod_{j=1}^{n} a_{y_j},y_{j+1}$$

Estimate of b_u(o) (emission parameter):

$$\prod_{j=1}^{n} b_{y_j}*x_j$$
