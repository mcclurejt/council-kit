[@council/sdk](../README.md) / [Exports](../modules.md) / DataSource

# Interface: DataSource

The base DataSource interface which simply requires a context instance.

## Hierarchy

- **`DataSource`**

  ↳ [`TokenDataSource`](TokenDataSource.md)

  ↳ [`VotingContractDataSource`](VotingContractDataSource.md)

  ↳ [`VotingVaultDataSource`](VotingVaultDataSource.md)

## Implemented by

- [`CachedDataSource`](../classes/CachedDataSource.md)

## Table of contents

### Properties

- [context](DataSource.md#context)

## Properties

### context

• **context**: [`CouncilContext`](../classes/CouncilContext.md)

#### Defined in

[packages/council-sdk/src/datasources/base/DataSource.ts:8](https://github.com/element-fi/council-monorepo/blob/c567f01/packages/council-sdk/src/datasources/base/DataSource.ts#L8)
