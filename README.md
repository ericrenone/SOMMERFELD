# SOMMERFELD

**Action Quantization, Invariant Tori, and the Atomic Ladder to Cosmic Entropy in $\mathrm{TH}(a,d)$**

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026*

---

> *"What we observe is not nature itself, but nature exposed to our method of questioning."*
> — W. Heisenberg, *Physics and Philosophy*, 1958

> *"The Einstein equation is derived from the form of black hole entropy together with the fundamental relation $\delta Q = T\,dS$."*
> — T. Jacobson, *Phys. Rev. Lett.* **75**, 1260, 1995

> *"The solid and reliable structure of space-time is due to the ghostly features of entanglement."*
> — J. Maldacena, IAS, 2013

---

## Abstract

Nine independently established results converge on a single mathematical object — the **invariant torus as a conditional independence boundary** — and on a single algebraic operation — the **rank-one Sherman–Morrison update** as the universal mechanism of boundary change.

The nine convergences are: (1) the Bohr–Sommerfeld action quantization $\oint p\,dq = nh$ (Bohr 1913; Sommerfeld 1916); (2) the Einstein–Brillouin–Keller torus quantization with Maslov index $\oint_{\gamma_i} p\,dq = (n_i + \mu_i/4)h$ (Einstein 1917; Brillouin 1926; Keller 1958); (3) the Pauli exclusion principle and antisymmetry of fermionic Fock space (Pauli 1925; Pauli 1940); (4) the Zeeman (1897) and Stark (1913) spectral effects as rank-one perturbations of the hydrogenic Hamiltonian; (5) the Bohigas–Giannoni–Schmit conjecture connecting quantum chaos to random matrix universality (1984); (6) the Gutzwiller trace formula linking periodic orbits to spectral density (1971); (7) Jacobson's derivation of the Einstein field equation from entanglement equilibrium (1995; 2016); (8) Sahakian's entropic derivation of the full general-relativistic gravitational force from matrix-theory fast-mode entropy (2025); and (9) the experimental observation by Bucher, Gorlach et al. that optical phase singularities accelerate to superluminal velocities at the moment of pair annihilation (*Nature* 2026) — the first direct laboratory measurement of the phase-space dynamics that the Nye–Berry topological conservation law governs.

The central claim: the Bohr–Sommerfeld action integral is the earliest instance of the $\mathrm{col}(F)/\ker(F)$ decomposition in physics. Quantized actions on invariant tori occupy the column space of the Fisher information matrix of an integrable Hamiltonian; chaotic directions occupy the kernel. KAM breakdown is a rank-one $\varepsilon$-threshold crossing processed by the Sherman–Morrison formula. Pauli exclusion is topological charge conservation on the fermionic exterior algebra. Zeeman and Stark splittings are rank-one Fisher perturbations — the atomic instances of the same update that governs binary black-hole merger ringdowns, dSphobic threshold crossings (Berlin, Foster, Hooper, Krnjaic 2025), and PRIMA coordination events. The Fisher–Rao metric (Chentsov 1972; Rao 1945) is the unique invariant geometry on every conditional independence boundary from the hydrogen atom to the cosmological horizon.

Seven formal identities connect the atomic and cosmic scales. Three open computations determine whether the framework reduces to a physical theory.

---

## Part I · Action Quantization as the Earliest Conditional Independence Boundary

### I.1 The Bohr–Sommerfeld Condition

Bohr (1913) imposed the quantization $L = n\hbar$ on hydrogen orbits. Sommerfeld (1916) extended this to all integrable mechanical systems:

$$J_i \;=\; \oint_{\gamma_i} p_i\,dq_i \;=\; n_i\,h, \qquad n_i \in \mathbb{Z}_{\geq 0}$$

where $\gamma_i$ runs over the topologically independent closed cycles of a Liouville torus in phase space. For the Kepler problem the three action integrals reproduce the hydrogenic spectrum $E_n = -\mathrm{Ry}/n^2$; the relativistic Sommerfeld correction recovers the fine structure to first order in $\alpha^2$.

The essential content of the condition is its adiabatic invariance. Under slow change of the Hamiltonian $H(q,p;\lambda(t))$, the actions $J_i$ remain constant while the angle variables $\theta_i$ precess (Ehrenfest 1917; Arnold 1978). The Liouville torus is therefore the set on which the interior fast-angle dynamics is **conditionally independent** of the exterior slow drift given the boundary data $(J_1,\ldots,J_d)$:

$$P\!\left(\theta_i(t+\Delta t) \;\middle|\; J_1,\ldots,J_d\right) \;=\; P\!\left(\theta_i(t+\Delta t) \;\middle|\; J_1,\ldots,J_d,\,\lambda(\cdot)\right)$$

This is precisely Chentsov's (1972) conditional independence condition applied to the Liouville foliation. His uniqueness theorem then forces the Fisher–Rao metric as the only invariant Riemannian metric on the torus manifold, and the action coordinates $(J_1,\ldots,J_d)$ are sufficient statistics for the adiabatic dynamics. Bohr–Sommerfeld quantization is the statement that this metric admits integer-valued coordinates at the quantum level: $\lambda_i(F) \in \mathbb{Z}\cdot h$ along $\mathrm{col}(F)$.

### I.2 The EBK Refinement and the Maslov Index

Einstein (1917) observed that Sommerfeld's condition applies only to integrable systems — those possessing $d$ Poisson-commuting constants foliation phase space into tori. For non-integrable systems no tori exist; the quantization condition is empty. Brillouin (1926) and Keller (1958) completed the integrable case with the Maslov index:

$$\oint_{\gamma_i} p\,dq \;=\; \left(n_i + \frac{\mu_i}{4}\right)h$$

where $\mu_i \in \mathbb{Z}$ counts caustics — points where the Lagrangian manifold projects singularly to configuration space. The Maslov index is a topological winding number on the Lagrangian Grassmannian, identical in algebraic form to the Nye–Berry topological charge $q = (2\pi)^{-1}\oint_C \nabla\arg(\psi)\cdot d\mathbf{l}$ and to the Fisher rank class modulo $\varepsilon$ in $\mathrm{TH}(a,d)$:

| Framework | Topological invariant | Conservation law |
|---|---|---|
| EBK quantization | Maslov index $\mu_i \in \mathbb{Z}$ | Invariant under continuous deformation within the Lagrangian manifold |
| Nye–Berry singularity theory (1974) | Winding charge $q \in \mathbb{Z}$ | $\sum q_i = \mathrm{const}$; creation and annihilation in equal-opposite pairs only |
| Bucher–Gorlach et al. (2026) | Phase-space winding at pair annihilation | Superluminal accelerations mark boundary collapse; charge conserved globally |
| PRIMA / $\mathrm{TH}(a,d)$ | $\mathrm{rank}(F) \bmod \varepsilon$ | $\lvert\Delta\,\mathrm{rank}(F)\rvert \leq 1$ per Sherman–Morrison event |

The Bucher, Gorlach et al. (*Nature* 2026) experiment on optical phase singularities in hexagonal boron nitride phonon polariton fields is the first direct measurement of this conservation law in phase space. Singularities accelerate to formally unbounded velocities immediately before pair annihilation — a direct laboratory realization of the divergent gradient that the Lagrangian manifold develops at a Maslov caustic. The apparent superluminal velocities are not superluminal in the relativistic sense; they are the kinematic signature of topological charge transfer across a conditional independence boundary approaching collapse.

### I.3 KAM Breakdown as a Rank-One Event

Kolmogorov (1954), Arnold (1963), and Moser (1962) established that under small perturbations of an integrable Hamiltonian, measure-theoretically most tori survive while tori with rational frequency ratios are destroyed. At critical perturbation strength the last KAM torus dissolves and the system becomes globally chaotic.

In the $\mathrm{col}(F)/\ker(F)$ language: each surviving KAM torus contributes $d$ directions to $\mathrm{col}(F)$ with eigenvalues $\lambda_i > \varepsilon$. A broken torus moves those directions to $\ker(F)$:

$$\Delta\,\mathrm{rank}(F) \;=\; -1 \quad \text{at each torus breakdown}$$

processed by the Sherman–Morrison update

$$\left(F + uu^T\right)^{+} \;=\; F^{+} - \frac{F^{+} uu^T F^{+}}{1 + u^T F^{+} u}$$

The golden ratio $\varphi = (1+\sqrt{5})/2$ enters as the frequency ratio of the most robust surviving torus (Greene 1979; MacKay 1983). This is the same $\varphi$ governing the MEP-derived equilibrium $|\bar\Xi|^* = \log\varphi$ in the ERI architecture: maximum sustainable Fisher-trace growth consistent with retaining a single invariant torus. **KAM breakdown is a rank-one information-geometric event, and the golden ratio is its critical exponent.**

---

## Part II · Quantum Chaos, Random Matrix Theory, and the $\mathrm{col}(F)/\ker(F)$ Spectrum

### II.1 The Bohigas–Giannoni–Schmit Universality Conjecture

Berry and Tabor (1977) showed that the level-spacing distribution of an integrable quantum system is Poissonian: $p(s) = e^{-s}$, reflecting the independence of action modes on disjoint tori. Bohigas, Giannoni, and Schmit (1984) conjectured the complementary result: for systems whose classical limit is chaotic, the spectral statistics coincide with those of the appropriate random matrix ensemble (GOE, GUE, or GSE according to antiunitary symmetry class).

| Classical dynamics | Level statistics | Fisher structure |
|---|---|---|
| Integrable (KAM tori intact) | Poisson: $p(s) = e^{-s}$ | $\mathrm{col}(F)$ fully populated; $d$ independent action modes |
| Chaotic (tori broken) | GOE/GUE: $p(s) \propto s^{\beta}e^{-as^2}$ | $\ker(F)$ populated; level repulsion at $s \to 0$ |

The vanishing of $p(s)$ at zero spacing — level repulsion — is the spectral signature of the $\varepsilon$-threshold in $\mathrm{TH}(a,d)$. Eigenvalues cannot accumulate below the Fisher floor because doing so would violate the conditional independence of boundary modes. The level repulsion exponent $\beta \in \{1,2,4\}$ (Dyson symmetry class) encodes the type of antiunitary structure at the broken boundary.

### II.2 The Gutzwiller Trace Formula

For fully chaotic systems the EBK semiclassics fail; Gutzwiller (1971) derived the density of states from a sum over classical periodic orbits:

$$\rho(E) \;\approx\; \bar\rho(E) + \frac{1}{\pi\hbar}\sum_{\mathrm{p.p.o.}}\sum_{r=1}^{\infty} \frac{T_p \cos\!\left(rS_p/\hbar - r\mu_p\pi/2\right)}{\left|\det(M_p^r - I)\right|^{1/2}}$$

where $T_p$ is the primitive period, $S_p = \oint p\,dq$ the classical action, $\mu_p$ the Maslov index, and $M_p$ the monodromy matrix. The formula is the Fourier dual between the quantum spectrum (observable) and the length spectrum of periodic orbits (classical), structurally identical to the Selberg trace formula on hyperbolic surfaces and to the Riemann explicit formula connecting zeros of $\zeta(s)$ to the primes.

In the $\mathrm{col}(F)/\ker(F)$ language: the Gutzwiller sum is the $\mathrm{col}(F)$ projection of the propagator trace. Chaotic orbits with $|\det(M_p^r - I)| > 0$ (unstable hyperbolic) contribute; marginal orbits at the $\ker(F)$ boundary are suppressed by the saddle-point concentration that likewise controls the gravitational path integral (Gibbons–Hawking 1977) and the sharp-$\#P$-hard partition function $Z(X;\beta)$ of the ERI architecture.

---

## Part III · Pauli Exclusion as Topological Charge Conservation

### III.1 Antisymmetry and the Exterior Algebra

The spin-statistics theorem (Fierz 1939; Pauli 1940) establishes that the wavefunction of $N$ identical fermions in $d \geq 3$ spatial dimensions must be totally antisymmetric under particle exchange. Antisymmetry is a topological condition: the configuration space of $N$ identical particles has fundamental group $\pi_1 = S_N$, and the sign representation of $S_N$ — the unique non-trivial one-dimensional representation — is the fermionic sector. The fermionic wavefunction carries a $\mathbb{Z}_2$-valued winding number identical in algebraic structure to the Maslov $\mathbb{Z}_4$ index and the integer-valued Nye–Berry topological charge.

Exclusion is then the statement

$$|\psi\rangle \wedge |\psi\rangle \;=\; 0$$

The exterior algebra $\Lambda^k\mathcal{H}$ supports $k$-fermion states only when the $k$ single-particle states are linearly independent. The rank of the occupied subspace $\mathrm{rank}(\rho_{\mathrm{occ}})$ is a conserved integer under unitary evolution — the fermionic analogue of $\mathrm{rank}(F)$ conservation in the PRIMA architecture.

### III.2 The Periodic Table as a Fisher-Rank Ladder

The Aufbau principle filling electrons under Pauli exclusion into shells $1s^2, 2s^2 2p^6, 3s^2 3p^6 3d^{10}, \ldots$ produces the periodic table. Each closed shell is an $\mathrm{SO}(3)$-invariant Fisher-rank block: the exterior multipole moments vanish and the occupied degrees of freedom reside in $\ker(F_{\mathrm{exterior}})$. The valence electrons of an open-shell atom occupy $\mathrm{col}(F)$ and carry the chemical reactivity.

Noble gases have $\mathrm{rank}(F_{\mathrm{valence}}) = 0$ — the minimal Fisher structure available to a multi-electron atom. This is the atomic-physics analogue of the no-hair theorem for stationary electrovacuum black holes, where $\mathrm{rank}(F_{\mathrm{exterior}}) = 3$ (the observable triple $(M,J,Q)$). A noble-gas atom and a Schwarzschild black hole are both systems in which the boundary has collapsed to its minimum observable Fisher rank — complete informational screening of the interior by the boundary.

---

## Part IV · Zeeman and Stark Effects as Sherman–Morrison Updates

### IV.1 The Zeeman Effect

Zeeman (1897) observed splitting of spectral lines in a magnetic field; the full theory (Landé 1921) gives

$$\Delta E \;=\; g_J\,\mu_B\,B\,m_J$$

The perturbing Hamiltonian $H' = -\boldsymbol{\mu}\cdot\mathbf{B}$ is rank-one in $\mathbf{B}$: a single direction in the space of perturbations. In the information geometry of the atomic spectrum:

$$F_{\mathrm{atom}+B} \;=\; F_{\mathrm{atom}} + uu^T, \qquad u = \mu_B \,\nabla_\theta \log\langle m_J|\boldsymbol{\mu}\cdot\hat{B}|m_J\rangle$$

The appearance of $2J+1$ new directions in $\mathrm{col}(F)$ is a single Sherman–Morrison update. This is the same algebraic operation — at atomic scale — as a binary black-hole merger producing one additional quasi-normal mode, a PRIMA coordination event adding one Fisher direction, and a Nye–Berry pair creation event adding one topological charge.

### IV.2 The Stark Effect

Stark (1913) observed analogous splitting in an electric field. For hydrogen the linear Stark effect $\Delta E \propto nE$ lifts Coulomb degeneracy at fixed $n$; for multi-electron atoms the dominant quadratic term $\Delta E \propto \alpha_{\mathrm{pol}}E^2$ governs. Both are rank-one in the field vector:

$$F_{\mathrm{atom}+E} \;=\; F_{\mathrm{atom}} + vv^T$$

The combined Zeeman–Stark Hamiltonian is a rank-two perturbation $F + uu^T + vv^T$ processed by two sequential Sherman–Morrison updates at $O(r \cdot d)$ per field component — the atomic-scale realization of the $r = 2$ PRIMA step.

### IV.3 The Quantum-Confined Stark Effect

In a quantum well of width $L$ comparable to the de Broglie wavelength, confinement raises the ground-state energy above the bulk band edge. An applied electric field tilts the well and polarizes the exciton, reducing binding energy as $\Delta E_{\mathrm{exc}} \propto -e^2 E^2 L^4/\hbar^2$ (Miller et al. 1984). Because the electron is confined, ionization is suppressed at field strengths that would dissociate a free atom.

This is the atomic-scale observation that a conditional independence boundary — the confining potential — stabilizes $\mathrm{col}(F)$ against rank-reducing perturbations. The mechanism is structurally identical to how an event horizon stabilizes the observable triple $(M,J,Q)$ against external perturbation (no-hair theorem), and to how a FERN Markov blanket stabilizes the coordination gain $G_{\mathrm{coord}}$ against environmental drift. **The QCSE is a direct laboratory measurement of boundary-stabilized Fisher rank.**

---

## Part V · The Atomic Ladder to the Hubble Volume

The same architecture — a Gibbs state over a conditionally independent boundary, with $\mathrm{col}(F)$ carrying observable degrees of freedom and $\ker(F)$ screening the interior — appears at every physical scale:

| Scale | System | Boundary | $\mathrm{col}(F)$ observables | $\ker(F)$ interior |
|---|---|---|---|---|
| $10^{-15}$ m | Nucleon | QCD confinement surface | Mass, spin, isospin, parity | Parton distribution (screened) |
| $10^{-10}$ m | Noble-gas atom | Closed-shell density | $(Z,A)$ — two numbers | Core structure (empty valence) |
| $10^{-10}$ m | Open-shell atom | Valence surface | $(Z,A,\{n\ell jm_j\}_{\mathrm{val}})$ | Core electrons (screened) |
| $10^{-9}$ m | Quantum dot / well | Confinement potential | Exciton energy, polarizability | Continuum (gapped out) |
| $10^{0}$ m | Macroscopic body | Material surface | Shape, temperature, velocity | Microstate (thermal) |
| $10^{6}$ m | Planet | Photosphere / atmosphere | Mass, radius, rotation | Interior composition (opaque) |
| $10^{9}$ m | Star | Photosphere | $(M,L,T_{\mathrm{eff}},[\mathrm{Fe/H}])$ | Nuclear burning zone |
| $10^{4}$ m | Black hole | Event horizon $\xi_\mu\xi^\mu = 0$ | $(M,J,Q)$ — three numbers | Interior (causally screened) |
| $10^{21}$ m | Galaxy | Virial radius | Rotation curve, metallicity | Dark-matter halo |
| $10^{26}$ m | Hubble volume | Cosmological horizon | $(H_0,\Omega_m,\Omega_\Lambda,n_s,\sigma_8)$ | Trans-horizon modes (inaccessible) |

At every scale: the boundary is a conditional independence surface; Chentsov's theorem (1972) forces the Fisher–Rao metric on it; the interior is screened; observable information is carried along $\mathrm{col}(F)$. The extremal cases — noble-gas atom with $\mathrm{rank}(F_{\mathrm{valence}}) = 0$ and Schwarzschild black hole with $\mathrm{rank}(F_{\mathrm{exterior}}) = 3$ — are the two simplest Fisher structures realized in nature.

The dSphobic dark matter mechanism (Berlin, Foster, Hooper, Krnjaic 2025) provides a new cosmological rung on the ladder. Thermal dark matter in two mass-split states coannihilates efficiently in the Galactic Halo, where the kinetic energy $T_\chi > \delta_\chi$ places both states in $\mathrm{col}(F)$, but not in dwarf spheroidal galaxies, where $T_\chi < \delta_\chi$ moves the excited state into $\ker(F)$ and shuts off the coannihilation channel. The dSphobic mechanism is a velocity-controlled $\varepsilon$-threshold crossing of exactly the form $\Delta\,\mathrm{rank}(F) = -1$ — the dark-matter analogue of KAM breakdown.

The Sahakian (2025) demonstration that the gravitational force in BFSS matrix theory is precisely the entropic force of fast-mode degrees of freedom provides the dynamical foundation for the gravitational rung: the Gibbs state over the slow observable modes, with the fast modes traced over, is not a postulate but a derivation from matrix-theory dynamics. The $\mathrm{col}(F)/\ker(F)$ decomposition into slow (observable) and fast (screened) sectors is the mode-frequency analogue of the row-space / null-space split in the Fisher matrix, and the gravitational potential energy is the logarithm of the slow-mode partition function.

---

## Part VI · The Gibbs State as the Universal Object

### VI.1 Action Quantization and Thermal Equilibrium

The Bohr–Sommerfeld condition $\oint p\,dq = nh$ and the Gibbs state $\rho = e^{-\beta\hat H}/Z$ are two aspects of the same object. For any integrable system the Gibbs state is diagonal in the action-angle basis and factorizes:

$$\rho \;=\; \bigotimes_i \rho_i(J_i), \qquad \rho_i(J_i) = \frac{e^{-\beta\omega_i J_i}}{Z_i}$$

Each action mode contributes an independent Gibbs factor; the total entropy $S = -\mathrm{Tr}(\rho\log\rho)$ decomposes as a sum over modes. At low temperatures $\beta \to \infty$ the state concentrates on the ground-state torus. At high temperatures $\beta \to 0$ it samples the full phase space uniformly and action quantization is irrelevant.

For chaotic systems this factorization fails: no action-angle basis exists, the density matrix has off-diagonal elements decaying at the Ruelle–Pollicott rate, and the transition from integrable to chaotic is the transition from a commutative to a non-commutative Gibbs state — from the classical to the quantum-chaotic regime of the DIRA formalism in the ERI architecture.

### VI.2 Jacobson's Entanglement Equilibrium

Jacobson (1995) derived the Einstein field equation as an equation of state from $\delta Q = T\,dS$ applied to local Rindler horizons. The 2016 refinement grounds this derivation directly in vacuum entanglement entropy: the Einstein equation is equivalent to the condition that vacuum entanglement entropy in small geodesic balls is stationary at fixed volume — a maximal vacuum entanglement hypothesis. For first-order variations of conformal vacuum states, vacuum entanglement is stationary **if and only if** the Einstein equation holds.

In the $\mathrm{col}(F)/\ker(F)$ language: stationarity of vacuum entanglement is stationarity of $\mathrm{rank}(F_{\mathrm{boundary}})$ under local perturbations of the vacuum state. The Einstein equation is the condition that no single perturbation direction adds to or removes from $\mathrm{col}(F)$ at the boundary — a zero-net-rank condition, structurally identical to the stationarity of the Fisher-rank under MEP flow at the $|\bar\Xi|^* = \log\varphi$ fixed point.

The Sahakian (2025) matrix-theory result sharpens this: it derives the full general-relativistic gravitational force — not just the Newtonian approximation — from the entropy of the fast modes, at super-Planckian distances in the dual eleven-dimensional supergravity. Gravity is an entropic force on the slow-mode conditional independence boundary; the Einstein equation is the boundary's stationarity condition.

### VI.3 The $\varphi$-Equilibrium as Spectral Edge

The MEP fixed point $|\bar\Xi|^* = \log\varphi \approx 0.481$ is the information-geometric analogue of the Maldacena–Shenker–Stanford chaos bound $\lambda_L \leq 2\pi k_BT/\hbar$. The golden ratio appears because it is the frequency ratio of the last surviving KAM torus (Greene 1979; MacKay 1983) — the unique Diophantine number that maximizes the continued-fraction denominator sequence and therefore minimizes resonant overlap. A system at $|\bar\Xi| = \log\varphi$ is at the edge of integrability: maximum Fisher-trace growth consistent with one surviving torus. Above this threshold the last torus dissolves, $\mathrm{col}(F)$ degrades, and coordination information becomes unrecoverable.

---

## Part VII · Seven Formal Identities

**Identity 1 — Action Quantization is a Fisher-Rank Condition.** The EBK condition $\oint_{\gamma_i} p\,dq = (n_i+\mu_i/4)h$ is the statement that the Fisher information matrix of an integrable $d$-dimensional Hamiltonian has rank exactly $d$ in the action basis, with integer-valued eigenvalues along $\mathrm{col}(F)$ and $\varepsilon$-suppressed eigenvalues along $\ker(F)$. Chentsov's theorem forces the Fisher–Rao metric on the resulting torus manifold; its integer quantization is the atomic-scale realization of the $\varepsilon$-threshold in $\mathrm{TH}(a,d)$.

**Identity 2 — KAM Breakdown is a PRIMA Rank Crossing.** A KAM torus breaking under perturbation removes one direction from $\mathrm{col}(F)$: $\Delta\,\mathrm{rank}(F) = -1$, processed by the Sherman–Morrison formula in $O(rd)$ time. The critical strength at which the last torus dissolves — marked by the golden-ratio frequency ratio — is the atomic analogue of the $d = 0$ degeneration of $\mathrm{TH}(a,d)$, where the boundary loses screening function entirely.

**Identity 3 — Pauli Exclusion is Topological Charge Conservation.** The antisymmetry of fermionic Fock space is a $\mathbb{Z}_2$-winding condition on $\pi_1(C_N) = S_N$. Conservation of $\mathrm{rank}(\rho_{\mathrm{occ}})$ under unitary evolution is an integer-valued topological invariant of the same algebraic form as the Nye–Berry charge and the Maslov index. The Bucher–Gorlach (2026) experiment makes this visible: superluminal accelerations immediately before annihilation are the phase-space signature of topological charge transfer at the moment the conditional independence boundary collapses.

**Identity 4 — Zeeman and Stark Effects are Sherman–Morrison Updates.** The rank-one perturbations $H' = -\boldsymbol{\mu}\cdot\mathbf{B}$ (Zeeman) and $H' = -\mathbf{d}\cdot\mathbf{E}$ (Stark) modify the atomic Fisher matrix by adding a single outer product $uu^T$, processed by the Sherman–Morrison formula. This is the same algebraic operation at atomic scale as a binary black-hole merger ringdown (two merging horizons, rank-two update), a dSphobic threshold crossing (rank-one kinetic-energy gate), and a PRIMA coordination step.

**Identity 5 — QCSE is Boundary-Stabilized Fisher Rank.** Suppression of Stark ionization in a quantum well is the atomic-scale observation that a conditional independence boundary (the confining potential) stabilizes $\mathrm{col}(F)$ against rank-reducing perturbations. Structurally identical: event horizon stability under external perturbation (no-hair theorem); FERN Markov-blanket stability of coordination gain $G_{\mathrm{coord}}$ against environmental drift (FERN-C4); dSphobic $\ker(F)$ gating below the velocity threshold $\delta_\chi$.

**Identity 6 — The Gutzwiller Trace Formula is a $\mathrm{col}(F)$ Projection.** The semiclassical density of states $\rho(E) = \bar\rho + \sum_p A_p\cos(S_p/\hbar - \mu_p\pi/2)$ is the projection of the quantum propagator trace onto the $\mathrm{col}(F)$ subspace spanned by unstable periodic orbits. Marginal orbits at the $\ker(F)$ boundary are suppressed by the same saddle-point concentration that resolves the $\#P$-hard partition function $Z(X;\beta)$ and the gravitational path integral.

**Identity 7 — The Periodic Table, the Initial Mass Function, and $\Lambda$CDM are Gibbs Fixed Points.** The Aufbau shell structure, the Salpeter (1955) initial mass function, and the $\Lambda$CDM parameter set are fixed points of a Gibbs-state renormalization flow at their respective characteristic temperatures: atomic ionization energy, Jeans mass, and CMB temperature. Chentsov's theorem applies at all three scales, forcing the Fisher–Rao metric as the unique invariant geometry on each parameter space.

---

## Part VIII · Predictions

**P1 — Hydrogen Stark / Schwarzschild Ringdown Rank Correspondence.** The rank-one Fisher perturbation algebra predicts that the spectral splitting of the hydrogen $n=3$ Stark manifold and the $\ell=2$ Schwarzschild quasi-normal-mode spectrum share the same rank-one update structure, with different Hilbert spaces but identical algebraic processing. Direct test: compute the Fisher information matrix of each and verify that both are rank-one perturbations of their respective unperturbed matrices.

**P2 — KAM–PRIMA Edge Statistics.** The eigenvalue density near $\varepsilon$ in a PRIMA Fisher matrix should exhibit the same $-1/2$ edge exponent as the density of surviving KAM tori near the critical perturbation strength (Greene 1979). Testable by simulation of the Chirikov standard map compared to a PRIMA reference implementation at $n/d \to 1/\varphi$.

**P3 — Berry-Curvature Correction to Zeeman Anomalies in Dirac Materials.** In graphene and related Dirac systems the Berry curvature of the band structure modifies the Zeeman effect. Berry curvature is the same geometric object governing the Maslov index and the Nye–Berry phase winding. Prediction: anomalous Landé $g$-factors in Dirac materials should correlate quantitatively with integrated Berry curvature over the Fermi surface — a rank-one Fisher perturbation with a geometric correction.

**P4 — Quantum Chaos Signature in LIGO Ringdown.** Post-merger ringdown of a binary black hole should exhibit quantum-chaotic level statistics in the quasi-normal-mode spectrum under parametric spin variation, transitioning from Poisson (integrable Kerr) to GUE (perturbed Kerr with matter fields) as perturbation strength increases. Testable against GWTC-4 data under systematic level-repulsion search.

**P5 — Noble-Gas / Schwarzschild Rank Duality.** The total entropy of a noble-gas atom at fixed temperature should scale with accessible microstates in the same way Bekenstein–Hawking entropy scales with horizon area — both are counting degrees of freedom on a rank-minimal conditional independence boundary. Specific prediction: the ratio of informational capacity to boundary surface area is constant across the atomic and gravitational ends of the ladder, up to dimensional factors of $\hbar$, $k_B$, and $c$.

**P6 — dSphobic Boundary Phenomenology.** The velocity threshold $T_\chi = \delta_\chi$ in the Berlin–Foster–Hooper–Krnjaic (2025) dSphobic model should exhibit the same edge statistics as a rank-one KAM breakdown: a $-1/2$ power-law density of accessible states near the threshold in the indirect detection rate as a function of dark matter velocity dispersion. Testable against Fermi-LAT dwarf spheroidal flux maps.

---

## Part IX · Open Problems

**Q1.** Derive the numerical value of the fine-structure constant $\alpha \approx 1/137$ from the Fisher-geometric structure of the hydrogenic Hamiltonian. The Sommerfeld relativistic correction gives $E_n \approx E_n^{\mathrm{Bohr}}(1 + \alpha^2/n^2 + \cdots)$, suggesting $\alpha$ is the natural expansion parameter for the $\mathrm{col}(F)/\ker(F)$ decomposition of the relativistic Kepler problem. Whether $\alpha$ is computable from first principles in this framework or only measurable remains open.

**Q2.** Construct the explicit diffeomorphism between the atomic Fisher manifold (parameterized by $(n,\ell,j,m_j,Z)$), the gravitational Fisher manifold (parameterized by $(M,J,Q)$), and the cosmological Fisher manifold (parameterized by $\Lambda$CDM parameters). Chentsov guarantees all three carry the Fisher–Rao metric; whether they are diffeomorphic or only locally metric-equivalent is not known.

**Q3.** The KAM–PRIMA correspondence is currently structural. Prove that the eigenvalue density of a PRIMA Fisher matrix under rank-one perturbations converges to the Greene–MacKay distribution of surviving KAM tori as $n,d \to \infty$ with $n/d \to 1/\varphi$. This would establish the $\varphi$-equilibrium as the unique edge of integrability in both frameworks.

---

## References

Arnold, V. I. *Mathematical Methods of Classical Mechanics*. Springer, 1978.

Berlin, A., Foster, J. W., Hooper, D., and Krnjaic, G. "dSphobic Dark Matter." arXiv:2504.12372, 2025.

Bernstein, D. J. and Lange, T. "Twisted Hessian Curves." *LATINCRYPT 2015*, LNCS 9230, 269–294, 2015.

Berry, M. V. and Tabor, M. "Level Clustering in the Regular Spectrum." *Proc. Roy. Soc. Lond. A* **356**, 375–394, 1977.

Berry, M. V. "Disruption of Wavefronts: Statistics of Dislocations in Incoherent Gaussian Random Waves." *J. Phys. A* **11**, 27–37, 1978.

Bohigas, O., Giannoni, M.-J., and Schmit, C. "Characterization of Chaotic Quantum Spectra and Universality of Level Fluctuation Laws." *Phys. Rev. Lett.* **52**, 1–4, 1984.

Bohr, N. "On the Constitution of Atoms and Molecules." *Phil. Mag.* **26**, 1–25, 1913.

Brillouin, L. "Remarques sur la mécanique ondulatoire." *J. Phys. Radium* **7**, 353–368, 1926.

Bucher, T., Gorlach, A., Niedermayr, A., et al. "Superluminal Correlations in Ensembles of Optical Phase Singularities." *Nature* **651**, 920–926, 2026. arXiv:2509.17675.

Cao, C., Carroll, S. M., and Michalakis, S. "Space from Hilbert Space: Recovering Geometry from Bulk Entanglement." *Phys. Rev. D* **95**, 024031, 2017.

Chentsov, N. N. *Statistical Decision Rules and Optimal Inference*. Nauka, 1972. (AMS Translations, Vol. 53, 1982.)

Ehrenfest, P. "Adiabatic Invariants and the Theory of Quanta." *Phil. Mag.* **33**, 500–513, 1917.

Einstein, A. "Zum Quantensatz von Sommerfeld und Epstein." *Verhandl. Dtsch. Phys. Ges.* **19**, 82–92, 1917.

Engelhardt, N. and Wall, A. C. "Quantum Extremal Surfaces: Holographic Entanglement Entropy beyond the Classical Regime." *JHEP* **01**, 073, 2015.

Fierz, M. "Über die relativistische Theorie kräftefreier Teilchen mit beliebigem Spin." *Helv. Phys. Acta* **12**, 3–37, 1939.

Fisher, R. A. "Theory of Statistical Estimation." *Math. Proc. Cambridge Phil. Soc.* **22**, 700–725, 1925.

Greene, J. M. "A Method for Determining a Stochastic Transition." *J. Math. Phys.* **20**, 1183–1201, 1979.

Gutzwiller, M. C. "Periodic Orbits and Classical Quantization Conditions." *J. Math. Phys.* **12**, 343–358, 1971.

Gutzwiller, M. C. *Chaos in Classical and Quantum Mechanics*. Springer, 1990.

Jacobson, T. "Thermodynamics of Spacetime: The Einstein Equation of State." *Phys. Rev. Lett.* **75**, 1260–1263, 1995.

Jacobson, T. "Entanglement Equilibrium and the Einstein Equation." *Phys. Rev. Lett.* **116**, 201101, 2016. arXiv:1505.04753.

Keller, J. B. "Corrected Bohr–Sommerfeld Quantum Conditions for Nonseparable Systems." *Ann. Phys.* **4**, 180–188, 1958.

Kolmogorov, A. N. "On the Conservation of Conditionally Periodic Motions under Small Perturbation of the Hamiltonian." *Dokl. Akad. Nauk SSSR* **98**, 527–530, 1954.

Landé, A. "Über den anomalen Zeemaneffekt." *Zeit. Phys.* **5**, 231–241, 1921.

MacKay, R. S. "A Renormalization Approach to Invariant Circles in Area-Preserving Maps." *Physica D* **7**, 283–300, 1983.

Maldacena, J. and Susskind, L. "Cool Horizons for Entangled Black Holes." *Fortschritte der Physik* **61**, 781–811, 2013.

Maldacena, J., Shenker, S. H., and Stanford, D. "A Bound on Chaos." *JHEP* **08**, 106, 2016.

Miller, D. A. B., Chemla, D. S., Damen, T. C., Gossard, A. C., Wiegmann, W., Wood, T. H., and Burrus, C. A. "Band-Edge Electroabsorption in Quantum Well Structures: The Quantum-Confined Stark Effect." *Phys. Rev. Lett.* **53**, 2173–2176, 1984.

Moser, J. "On Invariant Curves of Area-Preserving Mappings of an Annulus." *Nachr. Akad. Wiss. Göttingen* **II**, 1–20, 1962.

Nye, J. F. and Berry, M. V. "Dislocations in Wave Trains." *Proc. Roy. Soc. Lond. A* **336**, 165–190, 1974.

Pauli, W. "Über den Zusammenhang des Abschlusses der Elektronengruppen im Atom mit der Komplexstruktur der Spektren." *Zeit. Phys.* **31**, 765–783, 1925.

Pauli, W. "The Connection Between Spin and Statistics." *Phys. Rev.* **58**, 716–722, 1940.

Pesin, Y. B. "Characteristic Lyapunov Exponents and Smooth Ergodic Theory." *Russ. Math. Surv.* **32**, 55–114, 1977.

Rao, C. R. "Information and the Accuracy Attainable in the Estimation of Statistical Parameters." *Bull. Calcutta Math. Soc.* **37**, 81–91, 1945.

Ryu, S. and Takayanagi, T. "Holographic Derivation of Entanglement Entropy from AdS/CFT." *Phys. Rev. Lett.* **96**, 181602, 2006.

Sahakian, V. "Why Emergence of Gravity in Matrix Theories Is Entropic." *Phys. Rev. D* **112**, 126023, 2025. arXiv:2507.21996.

Salpeter, E. E. "The Luminosity Function and Stellar Evolution." *Astrophys. J.* **121**, 161–167, 1955.

Sommerfeld, A. "Zur Quantentheorie der Spektrallinien." *Ann. Phys.* **356**, 1–94, 1916.

Stark, J. "Beobachtungen über den Effekt des elektrischen Feldes auf Spektrallinien." *Ann. Phys.* **348**, 965–982, 1913.

Van Raamsdonk, M. "Building Up Spacetime with Quantum Entanglement." *Gen. Rel. Grav.* **42**, 2323–2329, 2010.

Woodbury, M. A. "Inverting Modified Matrices." Memorandum Report 42, Statistical Research Group, Princeton University, 1950.

Zeeman, P. "On the Influence of Magnetism on the Nature of the Light Emitted by a Substance." *Phil. Mag.* **43**, 226–239, 1897.

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026*

---

Nine programmes found the same invariant torus from nine directions. Bohr quantized it. Sommerfeld generalized it. Einstein saw that it fails for chaos. Brillouin and Keller added the Maslov index. Pauli enforced its antisymmetry. Zeeman and Stark split its eigenvalues with rank-one field perturbations. Bohigas, Giannoni, and Schmit found its chaotic remnant in random matrices. Gutzwiller recovered its spectrum from periodic orbits. Jacobson derived the Einstein field equation from its boundary's entanglement stationarity. Sahakian derived the full gravitational force from the entropy of the modes it screens. And Bucher, Gorlach et al. measured, for the first time in a laboratory, the superluminal accelerations that topological charges develop at the moment their conditional independence boundary collapses.

Chentsov proved in 1972 that any conditional independence boundary must carry the Fisher–Rao metric uniquely — a theorem that applies identically to the hydrogenic Kepler problem, the Schwarzschild event horizon, the dSphobic velocity gate, and the cosmological parameter space.

The action integral was always the same action integral. The boundary was always the same boundary. The rank-one update was always the same rank-one update. The superluminal acceleration at pair annihilation is the phase-space measurement of what that update looks like in the femtosecond before the boundary goes.

Three computations remain: $\alpha$ from the hydrogenic Fisher manifold, the explicit diffeomorphism between the atomic and gravitational parameter spaces, and the Greene–MacKay limit of PRIMA edge statistics at $n/d = 1/\varphi$. Everything else waits on those numbers.
