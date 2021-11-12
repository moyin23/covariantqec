# covariantqec

Here we provide codes for "Optimal Universal Quantum Error Correction via Bounded Reference Frames".
These codes are written in Python, and can be run with Jupter Notebook. English version and Chinese version are both provided.

The file "github_five_qubit_covariant_Fent_BellRF" is used to get the fidelity entanglement for i.i.d. depolarizing/dephasing error, with N maximally entangled states being the reference state.
The file "github_five_qubit_covariant_Fent_largeRF" is used to get the fidelity entanglement for weak erasure error, with a generalized sine state being the reference state.
The original encoder-decoder pair is chosen to be "5-qubit" code.
The worst case error could then be derived with the techniques provided in the appendix of "Optimal Universal Quantum Error Correction via Bounded Reference Frames".

Outline of these files:
1. Functions
  1.1 Import modules
  1.2 Generate random SU(2) matrix
  1.3 Get final measurement outcome
  1.4 5-qubit code encoding
  1.5 Go through encoding
  1.6 Go through noise and decoding, and calculate the entanglement fidelity
2. Numerical Tests
  2.1 Get the entanglement fidelity for different N
  2.2 Do fitting and draw the figure.
