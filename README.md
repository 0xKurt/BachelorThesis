# Vulnerability Detection in Solidity Smart Contracts - A Comparison of Tools and Services

### Bachelor Thesis in "Applied Computer Science", January 8, 2021

## Abstract

This bachelor thesis focuses on different security aspects of smart contracts on the Ethereum blockchain.
The Ethereum blockchain posesses a native software layer, the Ethereum Virtual Machine, that allows for the execution of code in the form of smart contracts. These smart contracts are often written in the programming language Solidity and the deployment onto the blockchain renders them immutable, yet publicly accessible. However, the primary use cases of smart contracts are financial applications.

Thus, it is crucially important to develop secure software. Several tools and services exist that allow for the analysis of Solidity code in order to prevent vulnerabilities and common vectors of attack in smart contracts.

This thesis compares these analyzers to determine their general usage and overall efficiency in finding these common vulnerabilities. 
For this purpose, the most common vulnerabilities are discussed, a smart contract based on these vulnerabilities is created and afterward inspected by the analyzers. The main focus is on the completeness of the vulnerabilities found, additional found problems, further information according to these results, and usability.

The comparison reveals that the use of tools and services is overall recommended. They are easy to use and mostly up to date. The analysis duration is adequate, and the results are usually well presented. However, it is noteworthy that none of the single applications was able to find all of the implemented weaknesses. Therefore, it is highly recommended to use the applications complementary to each other in order to cover a broad spectrum of security vulnerabilities and problems.


## Table of Content

### 1. Introduction

### 3. Basics
  * What is a Blockchain?
  * The Ethereum Blockchain
    * Smart Contracts 
    * Solidity
    
### 4. Vulnerabilities
  * External Calls
    * Unchecked Call Return Value
    * Delegatecall to Untrusted Callee
    * Failed Call using Send
  * Denial of Service
    * DoS with (Unexpected) revert
    * DoS with Block Gas Limit  
  * Reentrancy
  * Access Control
    * Unprotected Owner Setter
    * Unprotected Ether Withdrawl
    * Unprotected Selfdestruct
  * Integer Overflow and Underflow
    * Integer Overflow
    * Integer Underflow
  * Bad Randomness
    * With Private Seed
    * With Block Hash
    
### 4. Vulnerability Detection Tools and Services
  * Tools
    * Mythril
    * Slither
    * Securify2
    * Manticore
  * Services
    * Remix IDE
    * MythX

### 5. Vulnerable Smart Contract: BadBet
  * Gameplay
  * BadBet Smart Contract

### 6. Results of the BadBet Smart Contract Analysis
  * Mythril
    * Analysis Results
    * Conclusion
  * Slither
    * Analysis Results
    * Conclusion
  * Securify
    * Analysis Results
    * Conclusion
  * Manticore
  * Remix
    * Analysis Results
    * Conclusion
  * MythX
    * Analysis Results
    * Conclusion

### 7. Comparison of Results
  * Usage
  * Costs and Registration
  * Solidity Version
  * Duration of the Analysis
  * Content of Results
  * Quantity
  * Intentionally Implemented Vulnerabilities
  * Further Results

### 8. Conclusion

### List of Figures

### List of Tables

### Bibliography

### A. Appendix
  * A.1. BadBet.sol
  * A.2. BadBet0512.sol
  * A.3. Mythril Analysis Report
  * A.4. Slither Analysis Report
  * A.5. Securify Analysis Report
  * A.6. Remix Analysis Report
  * A.7. MythX Analysis Report
