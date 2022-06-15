# Test Verifier Contract Benchmarking

Execution benchmarking for a test verifier contract using Geth (v1.9.1) and [bsol](https://github.com/Giulio2002/bsol)

### Setup
```bash
git submodule init --recursive
cd bsol
sh install.sh

### Use svm to install solidity 0.7.6
cargo install svm-rs
svm install 0.7.6
svm use 0.7.6
```

### Running benchmark
```bash
cd contracts
$PATH_TO_BSOL_BIN/bsol --sol benchmark.sol --execution-time --runs 100 
```
