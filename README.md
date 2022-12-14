[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/Kenny-Heitritter/QuLabEDU.git)

## Overview
QuLabEDU is a series of hands-on labs in quantum information science built for a range of education backgrounds. Each lab is a jupyter-notebook intended to be run via Amazon Web Service's cloud quantum computing platform, Braket. These notebooks consist of an introduction and a series of code-blocks and questions that are answered in real-time.

## Usage
- Create an AWS account with access to Braket.
- Initialize a notebook on Braket.
    - Login to AWS -> Amazon Braket -> Notebooks -> Create notebook instance
    - When creating notebook instance, use Git Repository options to clone this repository 'https://github.com/Kenny-Heitritter/QuLabEDU.git'
- Go to the labs folder in your initialized Notebook and select your desired lab.

## Current Labs
 <Q|1> - The Stern-Gerlach Experiment
  - An introduction to the concept of qubit operations and measurements. After getting aquainted with the basics, you will use qubits to recreate the Stern-Gerlach experiment which originally showed the spin-1/2 nature of the electron. Variations on the Stern-Gerlach experiment show how quantum operations and measurement behave quite differently from their classical counterparts.


## Roadmap
- Complete graduate-level version of <Q|1>
- Create general scaffolding for lab creation
- Develop future labs based around the following:
    - Rabi oscillations
    - Entanglement, Bell states (2 qubits)
    - Quantum teleportation, usage in error correction
    - Trotterized version of MRI
    - Renyi entropy from twin copies
    - Measure phase shifts in one dimension
    - Preparation of configurable Rydberg arrays
    - Phase diagram of Rydberg atom ladders
    - Measurement of decoherence times (T1, T2) and comparison to hardware listings

## Contributing
To contribute, please contact Kenny Heitritter at kenneth-heitritter@uiowa.edu

## License
Apache License 2.0
