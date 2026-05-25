# Xanadu (xanadu)

Xanadu is a Toronto-based photonic quantum computing company building cloud-accessible continuous-variable quantum processors based on squeezed states of light. Founded in 2016 by Christian Weedbrook and listed on TSX/Nasdaq (XNDU), Xanadu demonstrated a 50-million-fold Gaussian-boson-sampling speedup with Borealis in 2022 and published modular networked photonic quantum computing in *Nature* in 2025. Beyond hardware, Xanadu is one of the most prolific open-source contributors in quantum software — it maintains PennyLane (the de-facto cross-platform quantum ML framework), Strawberry Fields, MrMustard, The Walrus, Blackbird, Catalyst, Lightning, and FlamingPy, all under Apache-2.0. Xanadu's own Quantum Cloud was retired in January 2026; the company's developer surface is now centered entirely on its open-source stack and integrations with third-party QPUs.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/xanadu/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags

 - Quantum Computing, Photonic Quantum Computing, Quantum Machine Learning, Continuous Variable, Open Source, Python, PennyLane, Strawberry Fields, Toronto

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### PennyLane
PennyLane is the cross-platform Python framework for quantum computing, quantum machine learning, and quantum chemistry maintained by Xanadu. Automatic differentiation of hybrid quantum-classical computations across PyTorch, JAX, TensorFlow, and NumPy with a device-agnostic plugin model. Apache-2.0, v0.45.0 (May 2026), 3.2k+ stars.

**Human URL:** [https://pennylane.ai](https://pennylane.ai)

- [Portal](https://pennylane.ai)
- [Documentation](https://docs.pennylane.ai/en/stable/)
- [GitHub](https://github.com/PennyLaneAI/pennylane)
- [PyPI](https://pypi.org/project/PennyLane/)
- [Demos](https://pennylane.ai/qml/demonstrations/)
- [Forum](https://discuss.pennylane.ai/)
- [JSON Schema — Device](json-schema/pennylane-device-schema.json)
- [JSON-LD context](json-ld/xanadu-context.jsonld)

### Catalyst
JIT compiler for hybrid quantum-classical PennyLane programs. Built on MLIR, lowering circuits to native machine code with quantum control flow, dynamic shapes, and differentiable hybrid execution.

**Human URL:** [https://docs.pennylane.ai/projects/catalyst/en/stable/](https://docs.pennylane.ai/projects/catalyst/en/stable/)

- [Documentation](https://docs.pennylane.ai/projects/catalyst/en/stable/)
- [GitHub](https://github.com/PennyLaneAI/catalyst)
- [PyPI](https://pypi.org/project/PennyLane-Catalyst/)

### PennyLane Lightning
High-performance state-vector and tensor-network quantum simulators in C++. Backends: `lightning.qubit` (CPU), `lightning.gpu` (CUDA), `lightning.kokkos`, `lightning.tensor`.

**Human URL:** [https://docs.pennylane.ai/projects/lightning/en/stable/](https://docs.pennylane.ai/projects/lightning/en/stable/)

- [Documentation](https://docs.pennylane.ai/projects/lightning/en/stable/)
- [GitHub](https://github.com/PennyLaneAI/pennylane-lightning)
- [PyPI](https://pypi.org/project/PennyLane-Lightning/)

### Strawberry Fields
Full-stack Python library for designing, simulating, and optimizing continuous-variable photonic quantum circuits. Gaussian, Fock, TensorFlow, and Bosonic backends.

**Human URL:** [https://strawberryfields.readthedocs.io/en/stable/](https://strawberryfields.readthedocs.io/en/stable/)

- [Documentation](https://strawberryfields.readthedocs.io/en/stable/)
- [GitHub](https://github.com/XanaduAI/strawberryfields)
- [PyPI](https://pypi.org/project/StrawberryFields/)

### MrMustard
Differentiable quantum-optics simulator bridging phase space and Fock space with NumPy and JAX backends; fast exact Fock-amplitude computation for Gaussian components plus Riemannian optimization.

**Human URL:** [https://mrmustard.readthedocs.io/](https://mrmustard.readthedocs.io/)

- [Documentation](https://mrmustard.readthedocs.io/)
- [GitHub](https://github.com/XanaduAI/MrMustard)
- [PyPI](https://pypi.org/project/mrmustard/)

### The Walrus
Python/C++ library for fast calculation of hafnians, loop hafnians, and multidimensional Hermite polynomials — the linear-algebra primitives behind Gaussian boson sampling.

**Human URL:** [https://the-walrus.readthedocs.io/](https://the-walrus.readthedocs.io/)

- [Documentation](https://the-walrus.readthedocs.io/)
- [GitHub](https://github.com/XanaduAI/thewalrus)
- [PyPI](https://pypi.org/project/thewalrus/)

### Blackbird
Quantum assembly language and intermediate representation for continuous-variable photonic quantum computation. Targets Xanadu hardware (X-series, Borealis, Aurora) and Strawberry Fields.

**Human URL:** [https://quantum-blackbird.readthedocs.io/](https://quantum-blackbird.readthedocs.io/)

- [Documentation](https://quantum-blackbird.readthedocs.io/)
- [GitHub](https://github.com/XanaduAI/blackbird)
- [PyPI](https://pypi.org/project/quantum-blackbird/)

### PennyLane-Qiskit Plugin
Integrates IBM Qiskit and IBM Q hardware as PennyLane devices for differentiable quantum programming.

**Human URL:** [https://docs.pennylane.ai/projects/qiskit/](https://docs.pennylane.ai/projects/qiskit/)

- [Documentation](https://docs.pennylane.ai/projects/qiskit/)
- [GitHub](https://github.com/PennyLaneAI/pennylane-qiskit)
- [PyPI](https://pypi.org/project/PennyLane-qiskit/)

### FlamingPy
Cross-platform Python library for efficient simulation of error correction in fault-tolerant photonic quantum computers with pluggable decoder backends.

**Human URL:** [https://flamingpy.readthedocs.io/](https://flamingpy.readthedocs.io/)

- [Documentation](https://flamingpy.readthedocs.io/)
- [GitHub](https://github.com/XanaduAI/flamingpy)

### Xanadu Cloud Client
Python API and CLI historically used to access Xanadu's photonic quantum cloud (Borealis, X-series). Xanadu's Quantum Cloud was retired in January 2026 and the project is archived; useful as a reference for Blackbird job submission patterns.

**Human URL:** [https://github.com/XanaduAI/xanadu-cloud-client](https://github.com/XanaduAI/xanadu-cloud-client)

- [GitHub](https://github.com/XanaduAI/xanadu-cloud-client)
- [PyPI](https://pypi.org/project/xanadu-cloud-client/)

## Features

- **Photonic Quantum Hardware** — Continuous-variable photonic processors using squeezed light: Borealis (Gaussian boson sampling) and Aurora (modular, scaling toward fault tolerance).
- **PennyLane Open-Source Framework** — Hardware-agnostic differentiable quantum programming across PyTorch, JAX, TensorFlow, and NumPy.
- **Plugin Ecosystem** — IBM Qiskit, AWS Braket, Google Cirq, IonQ, Rigetti, Microsoft QDK, Quantinuum/Honeywell, Qulacs, Strawberry Fields.
- **Lightning High-Performance Simulators** — C++ state-vector and tensor-network simulators across CPU, CUDA GPU, Kokkos, and tensor backends.
- **Catalyst JIT Compiler** — MLIR-based compiler with quantum control flow and end-to-end differentiation.
- **Photonic Software Stack** — Strawberry Fields, MrMustard, The Walrus, Blackbird, and FlamingPy.
- **Quantum Codebook and QML Hub** — Xanadu Quantum Codebook plus pennylane.ai/qml hundreds of research demos.

## Use Cases

- **Quantum Machine Learning Research** — Train hybrid quantum-classical models with autodiff against simulators and real QPUs from one API.
- **Quantum Chemistry** — VQE, ground/excited state, dynamics simulations via `pennylane.qchem`.
- **Photonic Algorithm Research** — Gaussian boson sampling, graph optimization, vibronic spectra in Strawberry Fields and MrMustard.
- **Fault-Tolerant Architecture Studies** — Photonic error-correction architectures and decoder benchmarking with FlamingPy.
- **HPC-Scale Quantum Simulation** — Multi-GPU and multi-node state-vector and tensor simulation with Lightning + Catalyst.
- **Quantum Education** — Xanadu Quantum Codebook, QHack, pennylane.ai demo library.

## Integrations

IBM Qiskit / IBM Quantum, AWS Braket, Google Cirq, IonQ, Rigetti, Quantinuum/Honeywell, Microsoft QDK, Qulacs, PyTorch, JAX, TensorFlow, NumPy, NVIDIA cuQuantum.

## Common

- [Portal](https://xanadu.ai)
- [PennyLane Portal](https://pennylane.ai)
- [Blog](https://xanadu.ai/blog)
- [PennyLane Blog](https://pennylane.ai/blog)
- [XanaduAI GitHub](https://github.com/XanaduAI)
- [PennyLaneAI GitHub](https://github.com/PennyLaneAI)
- [LinkedIn](https://www.linkedin.com/company/xanadu-quantum-technologies)
- [Twitter](https://twitter.com/XanaduAI)
- [YouTube](https://www.youtube.com/c/XanaduAI)
- [Discussion Forum](https://discuss.pennylane.ai/)
- [Quantum ML Hub](https://pennylane.ai/qml/)
- [Xanadu Quantum Codebook](https://pennylane.ai/codebook)
- [Demos](https://pennylane.ai/qml/demonstrations/)
- [PennyLane Plugins](https://pennylane.ai/plugins)
- [Release Notes](https://docs.pennylane.ai/en/stable/development/release_notes.html)
- [License — Apache 2.0](https://github.com/PennyLaneAI/pennylane/blob/master/LICENSE)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
