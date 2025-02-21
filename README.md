# Integer Underflow Vulnerability in Solidity

This repository demonstrates a common integer underflow vulnerability in Solidity smart contracts. The `transfer` function in `bug.sol` is susceptible to underflow if the amount to transfer exceeds the sender's balance. This can lead to unexpected behavior and potential exploitation.

The `bugSolution.sol` file provides a corrected version of the `transfer` function that safely handles underflow conditions using the `SafeMath` library.