# Infrastructure Changelog

All notable changes to the infrastructure will be documented in this file. Since the `infrastructure` has a lot of
components, the logs will have the following format:

```
(<component-name>): <the description of the change>
```

## Unreleased

### Changed

### Added

### Fixed

## Release 2021-01-12

### Added

- (`fee-seller`): reserve fee accumulator address.

### Changed

- (`explorer`) was refactored and optimized.
- (`explorer`): optimized by caching.
- (`tok_cli`): was removed and all commands from it have been moved to `zk`.

### Fixed

- (`fee-seller`): the logic of amount to withdraw/transfer through ZkSync network.
- Link to status page was added to explorer.
- (`explorer`): account and token ids, verified and committed nonces.
- (`zk`): `lint` command.
