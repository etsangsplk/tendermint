## v0.30.0

*TBD*

Special thanks to external contributors on this release:

### BREAKING CHANGES:

* CLI/RPC/Config

* Apps

* Go API

* Blockchain Protocol

* P2P Protocol

### FEATURES:
- [mempool] \#3079 bound mempool memory usage (`mempool.max_bytes` is set to 1GB by default; see config.toml)

### IMPROVEMENTS:
- [tools] add go-deadlock tool to help detect deadlocks

### BUG FIXES:
- [node] \#3186 EventBus and indexerService should be started before first block (for replay last block on handshake) execution
