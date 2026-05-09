# SCGFM
This repository is the official implementation of "Structure-Centric Graph Foundation Model via Geometric Bases" accpeted by ICML 2026.

<p align="center">
  <img src="figures/Model.pdf" width="850">
</p>

<p align="center">
  <b>\textbf{Overall framework of SCGFM}.
      In Geometric Bases Pre-training, trainable geometric bases are optimized via the Sliced Gromov-Wasserstein (SGW) distance to map each source-domain graph to a structural coordinate.
      In \textbf{Downstream Projection}, a target graph is matched to the bases to obtain a structural coordinate vector and a GW transport plan for projecting the feature matrix.
      The final graph embedding is the concatenation of the structural coordinate $\mathbf{\textbf{w}}$, decoder output $f(\mathbf{\textbf{w}})$, and projected feature $\mathbf{\textbf{H}}$ for downstream tasks.</b>
</p>




# Code will be realesed after cleanup