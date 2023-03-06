# AAVE Flashloan-Aave

## A loan without collateral and risks

This repo contains the contract for demonstrating the flashloans introduced by aave. In a flashloan, a user can take loan from any pool without any collateral, make profits through arbitrage or smart contract attack from the borrowed amount and return the borrowed amount with some premium. The interesting part is that all of these things happen in a single smartcontract call/transaction. This means that if any of the step fails, the complete call will be revereted as if there was no money borrowed. Only the gas fees for various steps are deducted.
