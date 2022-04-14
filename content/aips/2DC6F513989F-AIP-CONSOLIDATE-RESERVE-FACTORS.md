---
title: Consolidate Aave V1 and V2 Reserve Factors
status: WIP
author: Matthew Graham (@matthew-graham), Austin Green (@austingreen)
shortDescription: Distribute V1 reserve factor funds to V2 and send all new funds directly to V2
discussions: https://governance.aave.com/t/arc-consolidate-aave-v1-v2-amm-reserve-factors-purchase-cvx-and-deploy-to-earn-yield/6797
created: 2022-04-14
---

## Simple Summary


## Abstract


## Motivation


## Test Cases

The full test of this proposal can be found here: https://github.com/llama-community/refactor-aave-rf/blob/main/src/test/ProposalPayload.t.sol

## Implementation

In order to consolidate the V1 and V2 reserve factors, the proposal will target the contract ProposalPayload and call the execute and distributeTokens functions.

**Target Contract**

ProposalPayload = ETHERSCAN_LINK

**Transfer Parameters**



## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).