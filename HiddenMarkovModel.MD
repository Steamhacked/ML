HMM is defined by (T(tau), O, O(omega)):
  T -> set of states, including starn & end states
  O -> set of observation symbols
  O(omega) -> transition and emission parameters a_u,v & b_u(o)

a_u,v = count(u,v)/count(u); count(u,v) -> number of observed transitions from u to v, count(u) -> number of times state u is observed
b_u(o) = count(u->o)/count(u); count(u->o) -> number of times observation o generated from u is observed

$$\prod_{j=1}^{n} a_y_j,y_j+1$$
