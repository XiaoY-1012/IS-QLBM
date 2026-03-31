# IS-QLBM
Supplementary code for the publication: Xiao Yang, Yang Liming, Dong Hao, Du Yinjie. Interpolation-supplemented quantum lattice Boltzmann method for incompressible flows with non-uniform mesh and curved boundary. Physical Review E. 2026, (https://doi.org/10.1103/gngn-d5dy).
# Abstract
In this work, an interpolation-supplemented quantum lattice Boltzmann method (IS-QLBM) is proposed to simulate incompressible flows with non-uniform meshes and curved boundaries. Owing to the constraint of lattice uniformity, existing quantum LBMs are restricted to uniform square meshes and regular geometries, which severely limit their practicality. To address this limitation, we introduce an interpolation strategy to reconstruct the distribution functions f at each mesh point from those at neighboring points, thereby formulating the entire streaming step into the form of A·f. The matrix A is then decomposed into unitary matrices via singular value decomposition (SVD) for quantum circuit implementation. Since A depends solely on the mesh point coordinates, IS-QLBM can be applied to arbitrary meshes and geometries. The proposed method is validated using two-dimensional incompressible isothermal and thermal flows. The results show that IS-QLBM agrees very well with its classical counterpart IS-LBM, and that quadratic or higher-order interpolation is recommended to ensure sufficient accuracy. To further improve computational efficiency, we develop a multi-circuit IS-QLBM framework that reduces computational cost to less than one-eighth of the single-circuit implementation without sacrificing accuracy.
# Citation
@article{gngn-d5dy,
  title = {Interpolation-supplemented quantum lattice Boltzmann method for incompressible flows with non-uniform mesh and curved boundary},
  author = {Xiao, Yang and Yang, Liming and Dong, Hao and Du, Yinjie},
  journal = {Phys. Rev. E},
  pages = {--},
  year = {2026},
  month = {Mar},
  publisher = {American Physical Society},
  doi = {10.1103/gngn-d5dy},
  url = {https://link.aps.org/doi/10.1103/gngn-d5dy}
}
