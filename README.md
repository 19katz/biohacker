# BioHacker ([PDF](http://lampwww.epfl.ch/~amin/doc/biohacker.pdf))
### Debugging biological networks to reach coherence, completeness and consistency

_"Mistakes are the portals of discovery."_ -- James Joyce (1882-1941)

A metabolic network is defined as the set of biochemical reactions that the enzymes coded for in an organism's genome are capable of catalyzing. When the network of an organism is derived from pathway databases, it needs to be debugged for

* incoherences
  e.g., the metabolic model must obey mass balance laws.

* incompleteness
  e.g., the metabolic model is missing known reactions, genes, or compounds

* inconsistencies
  e.g., the metabolic model is inconsistent with experimental results

Because of these issues, reconstructing metabolic networks from annotated genomes is currently a time-consuming, error-prone process.

We develop BioHacker, a debugger for metabolic networks. BioHacker not only detects these issues, but also generates explanations as to where the problems lie and generates hypotheses for how to fix them.

BioHacker is based on the wonderful book _[Building Problem Solvers](BPS)_.
