[Home](https://nvenkov1.github.io/index.html) l __R&D__ l [Lab](https://nvenkov1.github.io/lab.html) l [Resume](https://nvenkov1.github.io/vita.html) l [GitHub](https://github.com/nvenkov1/)

## Gallery of recent works 

### FFT-based solver for nonlinear periodic Lippmann-Schwinger equations:

- [Source code repository](https://github.com/nvenkov1/fft-visco-hom) (C++)
- Sample results of small elasto-viscoplastic deformations and stress flow:

  <center> <img src="m_p.gif" alt="Viscoplastic flow in anisotropic polycrystal" width="31%" title="Viscoplastic flow in anisotropic polycrystal"/><img src="./m_s_norm_Poro_Biaxialb_viscoplast_c_0.0025_1024/test.gif" alt="Viscoplastic flow in medium with random defects" title="Viscoplastic flow in medium with random defects" width="31.8%"/><img src="./disordered_plastification/plastified/test.gif" alt="Plastification of a disordered porous medium" title="Plastification of a disordered porous medium" width="27.5%"/></center>

---

### Dynamic computation of 2D elastic Green functions and their gradients in anisotropic media:

A semi-analytical bottom-up dynamic programming algorithm is developed, implemented and validated for quick evaluation of high order gradients of Green's functions in 2D  anisotropic elastic media. Following a polar representation of the 2D linear elastic stiffness tensor, analytical expressions of the Barnett-Lothe integrands and their derivatives are obtained for anisotropic, orthotropic, R0-orthotropic, square symmetric and isotropic media. Analytical expressions of the complete Barnett-Lothe integrals are only obtained for isotropic media. In the case of anisotropy and other elastic symmetries, those integrals are evaluated numerically. The recursive relations are derived making use of the separability of angular and distance dependences of Green's functions, which remains true irrespectively of material symmetry and lack thereof. The method makes use of the complete Barnett-Lothe integrals and the derivatives of the corresponding integrands. Verification and validation of the method are successfully carried over analytically, and numerically.

- [Source code repository](https://github.com/nvenkov1/green-anisotropic) (C++)
- [Supporting document](https://github.com/nvenkov1/green-anisotropic/blob/master/GreenAnisotropic2D.pdf) (PDF)
- Sample results:


<center><img src="figPolar_isym0_100.gif" alt="Generalized elastic moduli of anisotropic medium" title="Generalized elastic moduli of anisotropic medium" width="30%" height="30%"/>

<img src="figTvM_isym0_100.gif" alt="Traction field on random closed curve in anisotropic medium" title="Traction field on random closed curve in anisotropic medium" width="33%" height="33%"/></center>

---

### Piecewise polynomial approximation scheme based on the Hashin-Shtrikman variational principle:

- [Source code repository](https://github.com/nvenkov1/hs-polynomial) (C++)
- Poster:


<center>
<img src="MACH2018_no_header.png" alt="MACH2018" width="100%" title="MACH2018"/>

</center>

------

### Domain decomposition preconditioners:

- [Source code repository](https://github.com/nvenkov1/julia-fem/tree/master/Fem) (Julia)
- Sample results:

<center><img src="https://nvenkov1.github.io/XFEM_ex1p_24cores.png" alt="DomainDecomposition" width="27%" title="DomainDecomposition" class="center"/></center>



---

### Sweeping algorithm for Voronoi diagrams of ellipses:

- [Source code repository](https://github.com/nvenkov1/bnd-solve-minkowski) (C++)
- Illustration of diffeomorphism from evolving tessellation to circular space-time representation:

<center><img src="./010c.png" alt="diffeormorphism" width="30%" title="diffeomorphism"/></center>

---

### Iterative methods for Gaussian process regression:

- [Jupyter notebook](https://github.com/nvenkov1/ml-gp-reg/blob/master/ml_gp.ipynb) (Python)
- Sample results:

<center><img src="./picture_ml_gp.png" alt="ml_gp" width="90%" title="ml_gp"/></center>

---

### Circulant embedding matrices for Gaussian processes:

- [Source code repository](https://github.com/nvenkov1/julia-gp-circulant-embedding) (Julia)
- Illustration of matrix-vector product with block symmetric circulant matrix with symmetric circulant blocks:

<center> <img src="./CirculantEmbedding.png" alt="matrix-vector product of BSCSCB" width="60%" title="matrix-vector product of BSCSCB"/></center>

---

### High-order morphological characterization of digital polycrystals:

- [Source code repository](https://github.com/nvenkov1/bnd-solve-minkowski) (C++)

- Sample results:

  <center> <img src="./GrainMinkowski_26.png" alt="Minkowski tensors" width="60%" title="Minkowski tensors"/></center>

---

### Parallel stochastic simulation of random fields using domain decomposition:

- [Source code repository](https://github.com/nvenkov1/julia-fem/tree/master/Fem) (Julia)
- Sample results:

<center> <img src="./random-fields/Example2.png" alt="Realizations of anisotropic random field" width="95%" title="Realizations of anisotropic random field"/></center>

------

### Estimation of N-point correlation functions of random fields:

- [Source code repository](https://github.com/nvenkov1/n-pcf) (C++)
- Sample results:



<center> <img src="./S3_45deg.png" alt="3-points correlation" width="85%" title="3-points correlation"/></center>





------

### Krylov subspace recycling for stochastic elliptic PDEs:

- Source code repositories (Python) : [1D](https://github.com/nvenkov1/deflation-precond-strategies-sde), [2D](https://github.com/nvenkov1/py-fenics-spde)

- Poster:

- <center> <img src="./jdd_cerfacs.jpg" alt="Krylov subspace recycling for stochastic elliptic PDEs" width="95%" title="Krylov subspace recycling for stochastic elliptic PDEs"/></center>

