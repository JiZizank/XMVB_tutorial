What is XMVB ?
==================

Xiamen Valence Bond (XMVB) is a quantum chemistry program for performing electronic structure calculations based on the non-orthogonal Valence Bond methods.
In the current arena of theoretical and computational chemistry, molecular orbital (MO) based methods undoubtedly are enjoying the overwhelming dominance, largely due to their high computational efficiencies. Apart from the MO theory, however, valence bond (VB) theory remains the widespread conceptual matrix for chemists, thus the development of novel algorithms and practical programs for the *ab initio* VB theory have been an endeavor for many of us.
The VB project at Xiamen University was initiated in 1986, when a spin-free form of VB
method was independently proposed. In 1989, we wrote a simple VB code and applied it to
H3 molecule. The systematic development of a complete and efficient VB code nevertheless
gained the momentum in 1992, when an algorithm based on the left coset decomposition of the
symmetric group was proposed and programmed. [#]_  [#]_ In 1995, we further developed an algorithm called the paired-permanent-determinant (PPD) approach, [#]_ [#]_ [#]_ [#]_ 
which is more efficient for
systems of many covalent bonds than the traditional Slater expansion algorithm, on which our
previous VB code, Xiamen-99, was based. In the last twenty years, we continued optimizing
the code and implementing some newly developed VB approaches into the code. To distinguish
our VB code from our city whose name is Xiamen, the code was renamed as XMVB [#]_ in 2002, beginning with Version 1.0. After ten years, Version 2.0 was released. XMVB 2.1 was released in 2015. Now, a new version of XMVB, XMVB 3.0, is released.

What’s New in Version 3.0 ?
============================

Compared with XMVB 2.0 and 2.1, the following features are available in XMVB 2.1:

*	More basis sets and elements supported for XMVB and PREINT.
*	Integrals can be calculated directly in XMVB calculations instead of read from file.
*	Cholesky decomposition for ERI is available.
*	Tensor-based VBSCF based on biothorgonal orbitals is implemented.
*	Seniority number constrained VBSCF is implemented.


What can be done with XMVB ?
=============================
*	Following ab initio VB methods are implemented in XMVB:

	*	Valence Bond Self-Consistent Field (VBSCF);
	*	Breathing Orbital Valence Bond (BOVB);
	*	Valence Bond Configuration Interaction (VBCI);
	*	Valence Bond Perturbation Theory (VBPT2);
	*	Density Functional Valence Bond (DFVB);
	*	Valence Bond Polarizable Continuum Model (VBPCM);
	*	Valence Bond Effective Fragment Potential (VBEFP);
	*	Combined Valence Bond Effective Fragment Potential Polarizable Continuum Model (VBEFP/PCM).

*	Many-electron wave function of computed system is written in terms of HLSP functions or Slater determinants. Both of structural coefficients and weights are provided.
*	The form of VB orbitals is flexible; they may be HAOs, BDOs, or OEOs, which are strictly localized, semi-localized, or fully delocalized.
*	Following population analysis properties of wave function are computed:

	*	Mulliken and Löwdin atomic charges;
	*	Atomic spin density polarization;
	*	Mayer’s bond order;
	*	Dipole moments.

*	Interface files for other programs, i.e. AIM2000 and MOLDEN, are provided for computing more properties or viewing VB orbitals


.. [#] Zhang, Q.; Li, X. Journal of Molecular Structure 1989, 198, 417.
.. [#] Wu, W.; Mo, Y.; Zhang, Q. Journal of Molecular Structure(Theochem) 1993, 283, 227.
.. [#] Wu, W.; Wu, A.; Mo, Y.; Zhang, Q. Science in China 1996, B39, 456.
.. [#] Wu, W.; Wu, A.; Mo, Y.; Lin, M.; Zhang, Q. International Journal of Quantum Chemistry 1998, 67, 287.
.. [#] Song, L.; Luo, Y.; Dong, K.; Wu, W.; Mo, Y.; Zhang, Q. Science in China 2001, B44, 561.
.. [#] Wu, W.; Mo, Y.; Cao, Z.; Zhang, Q. In Valence Bond Theory; Cooper, D. L., Ed.; Elsevier Science: Amsterdam., 2002; p 143.
.. [#] Song, L.; Mo, Y.; Zhang, Q.; Wu, W. Journal of Computational Chemistry 2005, 26, 514.


























































