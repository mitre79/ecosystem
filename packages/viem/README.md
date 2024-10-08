# @eth-optimism/viem

This package is a TypeScript extension for Viem that provides actions and utilities for working with OP stack chains. The goal of this package is to upstream as many actions and utilities as possible directly into Viem. You can view this as a playground for new features that haven't hit mainnet yet or more experimental features in the OP stack.

## Documentation

### Public L2 Actions
* [`estimateSendL2ToL2MessageGas`](https://github.com/ethereum-optimism/ecosystem/tree/main/packages/viem/docs/actions/estimateSendL2ToL2MessageGas.md)
* [`estimateExecuteL2ToL2MessageGas`](https://github.com/ethereum-optimism/ecosystem/tree/main/packages/viem/docs/actions/estimateExecuteL2ToL2MessageGas.md)

### Wallet L2 Actions
* [`sendL2ToL2Message`](https://github.com/ethereum-optimism/ecosystem/tree/main/packages/viem/docs/actions/sendL2ToL2Message.md)
* [`executeL2ToL2Message`](https://github.com/ethereum-optimism/ecosystem/tree/main/packages/viem/docs/actions/executeL2ToL2Message.md)

### Utilities
* [`extractMessageIdentifierFromLogs`](https://github.com/ethereum-optimism/ecosystem/tree/main/packages/viem/docs/utils/extractMessageIdentifierFromLogs.md)
* [`decodeSentMessage`](https://github.com/ethereum-optimism/ecosystem/tree/main/packages/viem/docs/utils/decodeSentMessage.md)

### Guides
* [`interop`](https://github.com/ethereum-optimism/ecosystem/tree/main/packages/viem/docs/guides/interop.md)

### Running Tests

Before you can run the unit tests you'll need [supersim](https://github.com/ethereum-optimism/supersim) installed. Once you have supersim installed you can run `pnpm nx run @eth-optimism/viem:test` from the root of the monorepo to get the tests running.