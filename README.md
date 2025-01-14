# NibiruChain/cw-nibiru

Smart contract sandbox for Nibiru Chain.

```bash
⚡ NibiruChain/cw-nibiru
├── 📂 artifacts         # compiled .wasm smart contracts for cw-nibiru
├── 📂 artifacts-cw-plus # compiled .wasm smart contracs from cw-plus
├── 📂 contracts         # Contracts for Nibiru Chain
    └── 📂 bindings-perp # Exposes queries and messages of the x/perp module of Nibiru.
    └── 📂 incentives    # Generalized incentives over time for locked tokens
    └── 📂 lockup        # For locking and unlocking tokens like LP tokens
    └── 📂 pricefeed     # CosmWasm version of the (now deprecated) x/pricefeed module.
    └── 📂 shifter       # Calls peg shift and depth shift in x/perp.
├── 📂 packages          # Contracts for Nibiru Chain
    └── 📦 bindings    # For sending custom messages via the x/wasm module of Nibiru.
    └── 📦 macro       # Implements procedural macros for the "nibiru-macro" pacakge. 
├── Cargo.toml
├── Cargo.lock
├── README.md
```

<!-- 🚧 Work in progress 🚧 -->
