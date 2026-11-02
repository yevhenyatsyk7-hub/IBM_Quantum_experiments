# IBM_Quantum_experiments

Interesting calculations on an IBM quantum computer.

## Experiments

- **Bell state**: two entangled qubits on `ibm_kingston`.
- **CHSH test**: Bell inequality violation, S ≈ 2.65 (classical limit is 2).
- **GHZ scaling**: entanglement vs. circuit size (2 to 40 qubits) on `ibm_fez`, `ibm_kingston` and `ibm_marrakesh`.

## Notes

The code was written with the help of Claude (Anthropic) and run and verified by the author on real IBM Quantum processors (Open Plan).

The IBM API token is read from Colab Secrets (`userdata.get("IBM_TOKEN")`) and is never stored in the code.

## License

MIT
