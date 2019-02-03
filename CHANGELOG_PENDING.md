## v0.30.0

*TBD*

Special thanks to external contributors on this release:

### BREAKING CHANGES:

* CLI/RPC/Config
- [httpclient] Update Subscribe interface to reflect new pubsub/eventBus API [ADR-33](https://github.com/tendermint/tendermint/blob/develop/docs/architecture/adr-033-pubsub.md)

* Apps

* Go API

* Blockchain Protocol

* P2P Protocol

### FEATURES:

### IMPROVEMENTS:
- [tools] add go-deadlock tool to help detect deadlocks

### BUG FIXES:
- [node] \#3186 EventBus and indexerService should be started before first block (for replay last block on handshake) execution
- [libs/pubsub] \#951, \#1880 use non-blocking send when dispatching messages [ADR-33](https://github.com/tendermint/tendermint/blob/develop/docs/architecture/adr-033-pubsub.md)
