
# PICOC, Research Questions, IC/ECs & Review Scope

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
| RQ3                | How do the QCNN/HQCNN models perform on these tasks, relative to classical baselines where reported?                                     |
| RQ4                | What is the deployment maturity per domain (actual quantum hardware vs simulated [e.g. Qiskit, Pennylane], synthetic vs real-world data) |
| RQ5                | What domain-specific barriers and open opportunities exist, and where could QCNN/HQCNN models expand beyond image classification         |

## Inclusion & Exclusion Criterias [ICs/ECs]

### Inclusion Criterias [ICs]

| ECs |                                                                                                                      |
| --- | -------------------------------------------------------------------------------------------------------------------- |
| IC1 | Publications between January 1st 2021- June 20th 2026.                                                               |
| IC2 | Publications must be in English.                                                                                     |
| IC3 | Limited to Conference Papers, Articles, Journal Articles & Relevant Preprints.                                       |
| IC4 | Articles implementing or applying QCNNs, HQCNNs for practical use cases.                                             |
| IC5 | Works demonstrating practical application of QCNN or HQCNN technology with documented results and accuracy readings. |

### Exclusion Criterias [ECs]

| ECs |                                                                                                                                                    |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| EC1 | Excluding all papers that aren’t English.                                                                                                          |
| EC2 | Publications before January 1st 2021 and after June 20th 2026.                                                                                     |
| EC3 | Articles without full text, extended abstracts, duplicates, or reviews, editorials & books.                                                        |
| EC4 | Studies that do not directly incorporate QCNN/HQCNN models.                                                                                        |
| EC5 | Studies that are primarily theoretical or conceptual papers that do not involve the application of a model to a problem task.                      |
| EC6 | Studies where the proposed QCNN/HQCNN model mentions aren’t the paper’s own contribution, mentioned from related works or are peripheral mentions. |
| EC7 | Studies consisting of generic hybrid quantum classifiers (Classical CNN/ResNet backbone + generic VQC or Quantum Kernel).                          |
| EC8 | Studies lacking experimental validation or quantitative evaluation of the proposed QCNN/HQCNN model.                                               |
| EC9 | Studies that use only synthetic datasets and do not demonstrate applicability to a domain-specific problem.                                        |
