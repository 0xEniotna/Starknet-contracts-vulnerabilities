# Starknet-contracts-vulnerabilities
A collection of Starknet smart-contracts vulnerabilitie

# (Not So) Smart Contracts

This repository contains examples of common Starknet smart contract vulnerabilities, including code from real smart contracts. Use Not So Smart Contracts to learn about Starknet vulnerabilities, as a reference when performing security reviews, and as a benchmark for security and analysis tools.

## Features

Each _Not So Smart Contract_ includes a standard set of information:

* Description of the unique vulnerability type
* Attack scenarios to exploit the vulnerability
* Recommendations to eliminate or mitigate the vulnerability
* Real-world contracts that exhibit the flaw
* References to third-party resources with more information

## Vulnerabilities

| Not So Smart Contract | Description |
| --- | --- |
| [Bad randomness](bad_randomness) | Contract attempts to get on-chain randomness, which can be manipulated by users |
| [Integer Overflow](integer_overflow) | Arithmetic in Solidity (or EVM) is not safe by default |
| [Reentrancy](reentrancy) | Calling external contracts gives them control over execution |
| [Unprotected Function](unprotected_function) | Failure to use function modifier allows attacker to manipulate contract |
| [Wrong Constructor Attribute](wrong_constructor_attribute) | Anyone can become owner of contract due to wrong constructor attribute|

## Credits


