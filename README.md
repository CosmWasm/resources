# CosmWasm Resources

## Websites
- [CosmWasm](https://cosmwasm.com/)
- [CosmWasm Academy](https://academy.cosmwasm.com/)

## Github
- [CosmWasm](https://github.com/CosmWasm/cosmwasm)
- [CosmJS](https://github.com/cosmos/cosmjs)
- [CosmWasmJS](https://github.com/CosmWasm/CosmWasmJS)

## Docs
- [CosmWasm Book](https://book.cosmwasm.com/) (by Bartlomiej Kuras)
- [CosmWasmJS Docs](https://cosmwasm.github.io/CosmWasmJS/)
- 

## Examples
- [cw-plus contracts](https://github.com/CosmWasm/cw-plus)

## IBC Theory

Check out this great overview video from HackAtom Seoul: https://www.youtube.com/watch?v=x75UobIr4qo&t=5s

- [official docs on theory](https://ibcprotocol.org)
- [full IBC spec](https://github.com/cosmos/ibc)
  - [Dataflow](https://github.com/cosmos/ibc/blob/main/spec/core/ics-004-channel-and-packet-semantics/README.md#dataflow-visualisation)
  - [Connection Lifecycle](https://github.com/cosmos/ibc/blob/main/spec/core/ics-003-connection-semantics/README.md#sub-protocols)
  - [Channel Lifecycle](https://github.com/cosmos/ibc/blob/main/spec/core/ics-004-channel-and-packet-semantics/README.md#channel-lifecycle-management)
  - [Light Client Semantics](https://github.com/cosmos/ibc/blob/main/spec/core/ics-002-client-semantics/README.md)

## IBC Contracts

Ethan's HackAtom video. Intro starts here about basic interfaces: https://www.youtube.com/watch?v=x75UobIr4qo&t=7077s

  - [IBC interface definition](https://github.com/CosmWasm/cosmwasm/blob/main/IBC.md)
  - [simple example contract](https://github.com/ezekiiel/cw-ibc-example)

Here I get into a real example, implementing "Simple ICA" contracts that are similar to Interchain Accounts: https://www.youtube.com/watch?v=x75UobIr4qo&t=9070s

  - [Simple ICA example](https://github.com/confio/cw-ibc-demo): Example IBC enabled contracts along with full stack integration tests 

Here is the code and tests for another approach, a contract speaking standard ics20 protocol, so it connects to standard Go module on
a non-CosmWasm chain:

  - [ics20-cw20 example](https://github.com/CosmWasm/cw-plus/tree/main/contracts/cw20-ics20)
  - [integration tests for ics20-cw20](https://github.com/confio/ibc-tests-ics20)


## Relayer (IBC)
- [ts-relayer](https://github.com/confio/ts-relayer)
  - [setup docs](https://github.com/confio/ts-relayer/blob/main/spec/ibc-setup.md)
  - [full documentation](https://github.com/confio/ts-relayer/blob/main/spec/index.md)
- [Images for blockchains in CI](https://github.com/confio/relayer-ci-images)

## Misc
