---
path: "/solidity-gas"
title: "Gas"
order: "40A"
section: "Solidity"
description: "Learning the fundamentals of the language"
icon: "dumpster-fire"
---

### Perhaps the most important of everything
Gas.  How expensive is what I am doing?

#### What is gas?
Its the cost, in ethers, for the transaction.  The typical measurement for gas
is `gwei`.  `gwei` is 10^9 `wei`.  In other words, its giga weis.

* wei is the fundamental unit of ether.  Its like our pennies.
* gwei = 10^9 * wei
* ether = 10^18 wei

#### How does gas price work?
To understand you need to understand two things.

1. what a virtual machine is
2. The current cost of gas. [Opcode and its associated prices.](https://github.com/crytic/evm-opcodes)

#### What is a virtual machine.
(Use gimp theprimeagen)

#### What is the current cost of gas?
(Use brave search theprimeagen)

> Typical measurement for gas is in `gwei`

But how much is that?  gas-cost * 10^9 * eth-cost / 10^18<br />
That is for _one_ gas.<br />

#### Lets break down whats happening