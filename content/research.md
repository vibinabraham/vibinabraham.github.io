---
title: "Research"
description: "Research of Vibin Abraham: many-body theory for spectroscopy, X-ray and core-level spectra, noise-resilient quantum algorithms, end-to-end quantum simulation workflows, relativistic Green's function methods, and tensor product states."
hidemeta: true
---

<h2 class="research-heading">Research interests</h2>

<div class="research-grid">

<div class="research-card">
  <div class="fig"><img src="/papers/paper6/paper6_toc.png" alt="Real-time coupled-cluster ansatz and quantum algorithm for core spectra"></div>
  <div>
    <h3>X-ray and core-level spectroscopy</h3>
    <div class="tags"><span class="tag pnnl">PNNL</span></div>
    <p>Core ionization is spatially localized, but the valence response it triggers is not. The sudden core hole drives correlated valence dynamics (shake-up, charge-transfer screening, relaxation) on attosecond-to-femtosecond timescales, and these imprint the satellite structure and quasiparticle weights of the core spectrum.</p>
    <p>I resolve these dynamics with real-time coupled-cluster Green's functions: a time-dependent double coupled-cluster (TD-dCC) hierarchy that couples the N- and (N−1)-electron sectors through truncated BCH expansions, reproducing exact satellite features at reduced cost, with a component analysis that isolates the hole-mediated excitation pathways behind each satellite. Using correlated shifted-start real-time Λ-CC with orbital- and fragment-resolved screening, I show that O 1s ionization in the water dimer recruits donor-local and intermolecular charge-transfer channels, and that stretching the hydrogen-bonded O–H nearly doubles their share of the satellite response within ~10 fs. In parallel, I construct fault-tolerant quantum signal processing algorithms for the core-hole Green's function, and am building GPU-accelerated RT-CC software (pytdcc) to reach larger systems.</p>
    <p class="key-papers">Key papers: <a href="https://pubs.aip.org/aip/jcp/article/164/10/104113/3383265/Elucidating-many-body-effects-in-molecular-core">J. Chem. Phys. 2026</a> · <a href="https://arxiv.org/abs/2608.22268">arXiv:2608.22268</a></p>
  </div>
</div>

<div class="research-card">
  <div class="fig"><img src="/papers/paper2/paper2.png" alt="Quantum self-consistent equation-of-motion method"></div>
  <div>
    <h3>Noise-resilient quantum algorithms</h3>
    <div class="tags"><span class="tag pnnl">PNNL</span><span class="tag vt">Virginia Tech</span></div>
    <p>Near-term quantum hardware is noisy, so algorithms must be compact and able to learn from the noise. I develop noise-aware methods that learn from noisy real-time dynamics and quantum Krylov subspaces, dual-space formulations for compact eigenvalue problems that keep a variational bound, and uncertainty quantification and chemically decisive benchmarks for judging when hardware gives reliable answers. This builds on the equation-of-motion algorithms for excited states I co-developed with Los Alamos National Laboratory.</p>
    <p class="key-papers">Key papers: <a href="https://arxiv.org/abs/2609.04387">arXiv:2609.04387</a> · <a href="https://arxiv.org/abs/2607.14392">arXiv:2607.14392</a> · <a href="https://arxiv.org/abs/2601.10813">arXiv:2601.10813</a> · <a href="https://pubs.rsc.org/en/content/articlehtml/2023/sc/d2sc05371c">Chem. Sci. 2023</a></p>
  </div>
</div>

<div class="research-card no-fig">
  <div>
    <h3>End-to-end quantum simulation workflows</h3>
    <div class="tags"><span class="tag pnnl">PNNL</span></div>
    <p>Useful quantum simulation needs the whole pipeline, from a real molecule or material to a Hamiltonian a quantum computer can handle. I build classical–quantum workflows that combine electronic structure, embedding, active-space reduction, and downfolding:</p>
    <ul>
      <li><strong>HDAC8 metalloenzyme:</strong> projector-based embedding through to quantum simulation, with IQM, NVIDIA, Argonne National Laboratory, and UCL.</li>
      <li><strong>Strongly correlated materials:</strong> two-dimensional Hubbard systems from downfolded Hamiltonians, with Mario Motta and Karol Kowalski.</li>
      <li><strong>Molecular spin qubits:</strong> dephasing and open-system dynamics, from molecular modeling to quantum dynamical simulation.</li>
      <li><strong>Constrained systems:</strong> adiabatic gauge potential optimization to prepare better initial states for quantum calculations.</li>
    </ul>
  </div>
</div>

<div class="research-card">
  <div class="fig"><img src="/papers/paper1/paper1.jpg" alt="Relativistic self-consistent GW for molecules"></div>
  <div>
    <h3>Relativistic Green's function methods for molecules and solids</h3>
    <div class="tags"><span class="tag umich">Michigan</span></div>
    <p>Heavy elements, including actinides, are central to catalysis, nuclear chemistry, and quantum materials, yet relativistic effects make them hard to model. I developed and benchmarked fully self-consistent, relativistic GW for ionization potentials and total energies of heavy-element molecules and periodic solids at finite temperature, implemented in the open-source <a href="https://green-phys.org/">Green</a> package.</p>
    <p class="key-papers">Key papers: <a href="https://pubs.acs.org/doi/abs/10.1021/acs.jctc.4c00075">JCTC 2024</a> · <a href="https://pubs.rsc.org/en/content/articlelanding/2024/fd/d4fd00043a">Faraday Discuss. 2024</a> · <a href="https://www.sciencedirect.com/science/article/abs/pii/S0010465524003035">Comput. Phys. Commun. 2025</a> · <a href="https://arxiv.org/abs/2605.31571">J. Phys. Chem. Lett. 2026</a></p>
  </div>
</div>

<div class="research-card">
  <div class="fig"><img src="/papers/paper3/paper3.png" alt="Tensor product selected configuration interaction"></div>
  <div>
    <h3>Tensor product states and excitonic processes</h3>
    <div class="tags"><span class="tag vt">Virginia Tech</span></div>
    <p>Strongly correlated systems defeat standard methods because the number of important configurations explodes. I designed tensor-product-state frameworks (TPSCI, cluster many-body expansion) that describe them compactly, and applied them to excitonic processes in molecular aggregates: singlet fission and energy transfer in organic photovoltaic materials, with predictions later confirmed by independent experiments.</p>
    <p class="key-papers">Key papers: <a href="https://pubs.acs.org/doi/abs/10.1021/acs.jctc.0c00141">JCTC 2020</a> · <a href="https://pubs.aip.org/aip/jcp/article-abstract/155/5/054101/201005/Cluster-many-body-expansion-A-many-body-expansion">J. Chem. Phys. 2021 (Editor's Pick)</a> · <a href="https://pubs.acs.org/jpclcd/article-abstract/8/22/5472/761156/Simple-Rule-To-Predict-Boundedness-of-Multiexciton">J. Phys. Chem. Lett. 2017</a> · <a href="https://pubs.acs.org/doi/10.1021/acs.jpclett.1c03217">J. Phys. Chem. Lett. 2021</a></p>
  </div>
</div>

</div>

See [Publications](../papers/) for highlighted work, or the [full list of publications](../publications/).
