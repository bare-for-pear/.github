# bare-for-pear

Infrastructure modules for the [Bare](https://github.com/holepunchto/bare) runtime. Community forks barified for Bare, plus original modules and a minimal git engine for P2P embedding.

**Modules:**
- **avsc** — Avro type system, serialization, schema evolution
- **avsc-rpc** — Avro RPC protocol, service definition, transports
- **git** — git CLI wrapper, subtree management, two-reality model
- **rpc-server** — server lifecycle, PID management, file-based command IPC
- **isomorphic-git** — full isomorphic-git with Hyperdrive fs adapter (dual backend: bare-fs / P2P)
- **p2p-git** — minimal git engine for embedding (plumbing only, transaction model via index)

Part of the [SPLectrum](https://splectrum.world) engineering infrastructure. All modules MIT licensed.
