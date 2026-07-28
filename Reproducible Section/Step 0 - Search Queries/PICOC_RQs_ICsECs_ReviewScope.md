
# PICOC, Research Questions, IC/ECs & Review Scope

## Review Scope

- **Title:** Applications of Quantum and Hybrid Quantum Convolutional Neural Networks: A Systematic Review
- **Coverage & Time Period:** 2021-2026 w/ Scopus, arXiv, IEEE

### 

## PICOC Table

| Component    | Definition                                                                                                                                   |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Population   | Studies involving the application of Quantum Convolutional Neural Networks and Hybrid Quantum Convolutional Neural Networks (QCNNs & HQCNNs) |
| Intervention | Investigating the uses of QCNNs & HQCNNs to solve real application tasks across varying domains.                                             |
| Comparison   | Comparison across application domains and compared against classical baselines where reported.                                               |
| Outcome      | Evaluating the performance metrics, deployment maturity and domain-specific barriers for QCNNs & HQCNNs.                                     |
| Context      | Quantum machine learning on NISQ-era devices and simulators.                                                                                 |

## Research Questions [RQs]

| Research Questions | Details                                                                                                                                  |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| RQ1                | What application domains and tasks have the QCNN/HQCNN models been applied to?                                                           |
| RQ2                | Which datasets and problem types are addressed within each domain?                                                                       |
| RQ3                | How do QCNN/HQCNN models perform on these tasks, as reported by their respective quantitative metrics in comparison to their classical baselines, if applicable? |
| RQ4                | What is the deployment maturity per domain in relation to execution environment (actual quantum hardware vs simulated [e.g., Qiskit, Pennylane]), |
| RQ5                | What domain-specific barriers and open opportunities exist, and where could QCNN/HQCNN models expand beyond image classification?        |

## Inclusion & Exclusion Criterias [ICs/ECs]

### Inclusion Criterias [ICs]

| No# | Inclusion Criteria                                                                                                     |
| --- | ---------------------------------------------------------------------------------------------------------------------- |
| IC1 | Publications between January 1st 2021- June 20th 2026.                                                                 |
| IC2 | Publications must be in English.                                                                                       |
| IC3 | Limited to Conference Papers, Articles, Journal Articles & Relevant Preprints.                                         |
| IC4 | Articles implementing or applying QCNNs, HQCNNs for practical use cases.                                               |
| IC5 | Works demonstrating practical application of QCNN or HQCNN technology with documented results and performance metrics. |

### Exclusion Criterias [ECs]

| No# | Exclusion Criteria                                                                                                                                 |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| EC1 | Excluding all papers that aren’t English.                                                                                                          |
| EC2 | Publications before January 1st 2021 and after June 20th 2026.                                                                                     |
| EC3 | Articles without full text, extended abstracts, duplicates, or reviews, editorials & books.                                                        |
| EC4 | Studies that do not directly incorporate QCNN/HQCNN models.                                                                                        |
| EC5 | Studies that are primarily theoretical or conceptual papers that do not involve the application of a model to a problem task.                      |
| EC6 | Studies where the proposed QCNN/HQCNN model mentions aren’t the paper’s own contribution, mentioned from related works or are peripheral mentions. |
| EC7 | Studies that use only standard reference datasets and do not demonstrate applicability to a domain-specific problem (e.g. MNIST, CIFAR, etc)       |
| EC8 | Studies that are not accessible via the available institutional access provided by the host university.                                            |
| EC9 | Studies lacking experimental validation or quantitative evaluation of the proposed QCNN/HQCNN model.                                               |

## Acronyms & Glossary

| Acrnonym         | Expanded Form                                           |
| ---------------- | ------------------------------------------------------- |
| QCNN             | Quantum Convolutional Neural Network                    |
| HQCNN            | Hybrid Quantum Convolutional Neural Network             |
| RX, RY, RZ-Gates | Rotation X, Y, or Z Gate (axis)                         |
| MCX Gate         | Multi-Controlled X Gate                                 |
| CRY Gate         | Controlled-Rotation Y Gate                              |
| CNOT/CX Gates    | Controlled-Not Gate                                     |
| Ansatz/PQC       | Parameterized Quantum Circuit                           |
| NISQ             | Noisy Intermediate-Scale Quantum                        |

| Word             | Definition                                              |
| ---------------- | ------------------------------------------------------- |
| QCNN             | |
| HQCNN            | |
| RX, RY, RZ-Gates | Rotation-X,Y,Z Gates are quantum gates that rotate a qubits state around the X,Y, or Z-axis by a given angle with the purpose of encoding classical data into quantum states.                                  |
| MCX Gate         | A Multi-Controlled-X Gate is a multi-qubit gate that resembles a CNOT gate with the addition of more control qubits, where the Pauli-X operation is triggered once all the control qubits are in a \|1⟩ state.  |
| CRY Gate         | A Controlled-RY Gate is a two-qubit RY Gate with a conditional activation based on if the control qubit is in a \|1⟩ state, it is one of the other methods used to establish entanglement between qubits.       |
| CNOT/CX Gates    | A Controlled-Not Gate is a two-qubit quantum gate that inverts a qubits' state if, and only if, the control \|1⟩ state. It is used to achieve entanglement and is the equivalent of a reversible XOR gate.      |
| Pauli-X Gate     | A Pauli-X Gate  lips the state of a qubit from \|0⟩ to \|1⟩ and from \|1⟩ to \|0⟩, representing the quantum variant of a NOT gate.                                                                               |
| Hadamard Gate    | A Hadamard Gate is a single-qubit quantum gate that maps a state into an equal, uniform superposition, where the qubit exists in a \|0⟩ and \|1⟩ state in parallel, this is done to allow quantum circuits to explore multiple paths in parallel. |
| Ansatz/PQC       | |
| NISQ             | |
