# IKUN-Mechanism

A plug-in **crowding-aware diversity module** for any population-based meta-heuristic (PSO, DE/JADE, GA,CMA-ES, …).  
IKUN keeps a sliding-window KD-tree of recent solutions, estimates local density with *k*-nearest neighbors, and adds a repulsive potential  
\[
\Phi(\mathbf{x})=\lambda\,\hat\rho_k(\mathbf{x})
\]
