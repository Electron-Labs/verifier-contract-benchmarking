# Test Verifier Contract Benchmarking

Execution benchmarking for a test verifier contract using Geth (v1.9.1) and [bsol](https://github.com/Giulio2002/bsol)

### Setup
```bash
git submodule init --recursive
cd bsol
sh install.sh
```

### Running benchmark
```bash
cd contracts
$PATH_TO_BSOL_BIN/bsol --sol benchmark.sol --execution-time --runs 100 
```
