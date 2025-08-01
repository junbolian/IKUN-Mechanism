# IKUN-Mechanism <br>*(Incremental **K**D-tree–based c**U**rowdi**N**g potential)*

A **drop-in diversity module** for any population-based meta-heuristic.  
IKUN keeps a sliding window of the last **W** populations in a KD-tree, estimates
the *k*-nearest–neighbor density ρ̂<sub>k</sub>(x), and adds the repulsive term  

&nbsp;&nbsp;**Φ(x) = λ ρ̂<sub>k</sub>(x)**  

to your update / selection rule—two extra lines in practice.
