# quantum-sluice
# quantum-sluice – Quantum‑Inspired Recursive Filter

This is not a linear filter. It implements:

- **Ternary states** (–1, 0, +1)
- **Time slicing** (different measurement basis per cycle)
- **Recursive collapse** (noise decays over cycles)
- **State memory** (amplitude stored across iterations)

The result is a filter that does not just reject based on static rules – it evolves.

## Compile

```bash
gcc quantum_sluice.c -o quantum_sluice
