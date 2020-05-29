# Honors Thesis (from Mark M @ UNC Dept of Computer Science)

Many automated theorem proving applications rely on the DPLL
algorithm for deciding the satisfiability of a set of propositional logic
formulae. For first-order logic formulae, ground clauses within the
Herbrand universe may be exhaustively enumerated below an incrementing size-bound and fed as input to DPLL. From even a cursory
investigation of these enumerated clauses, it is evident that many of
them have multiple repeated terms. Here, we explore a potential
method for exploiting the size-bound by “cheating in” larger clauses
with many repeating terms that may be relevant to the proof.


The full notebook is viewable on github. For an in-depth discussion, I've included a copy of the final paper.

If anyone is interested in exploring or continuing this work: Try setting `Repeat`s `length` to `1` :)
