## Introduction

Solidity is the primary language for writing smart contracts on blockchain platforms like Celo. One important consideration when writing these contracts is the cost of gas, the fee required to perform transactions and computations on the network. In this challenge, you will focus on optimizing the gas usage of a smart contract.

## Problem Statement

Given a pre-existing contract that handles a simple token economy (including functions for minting tokens, transferring tokens, and querying balances), your task is to refactor the contract to reduce its gas consumption with the following requirements:

1. The contract should still follow the ERC-20 standard.
2. The contract should pass all the same tests as before the refactoring.
3. The contract should include comments indicating where optimizations have been made and explaining the reasoning behind them.

## Hints

- Consider using smaller data types where possible.
- Make use of `view` and `pure` function modifiers when functions don't need to alter the contract's state.
- Utilize short-circuiting in boolean expressions to avoid unnecessary computation.
- Make effective use of data structures and contract storage.

## Evaluation Criteria

- **Correctness**: The contract should compile without errors and function the same as before the refactoring.
- **Readability**: The contract should be well-documented, with comments explaining the optimizations.
- **Efficiency**: The optimized contract should use significantly less gas than the original contract.
- **Testability**: You should also provide examples of how to test each function of the contract.

Please note that while gas optimization is important, it should not compromise the contract's security.

For a comprehensive understanding of Celo smart contracts, Solidity, and gas optimization, please refer to the Celo and Solidity tutorials.

## Submission

Please reply with a link to your PR on GitHub, including your optimized contract. Also, include any notes or comments you think are necessary to understand your design and choices. Lastly, provide a brief explanation about how each function of the contract should be tested.
