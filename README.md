# 100Lakes

## Overview

100Lakes is a project designed to demonstrate the integration and deployment of smart contracts using various Ethereum frameworks. This repository contains submodules such as `dappsys`, `openzeppelin-contracts`, and `truffle`, which provide essential libraries and tools for developing and managing Ethereum smart contracts.

## Structure

- `dappsys`: A library of smart contracts for building decentralized applications (DApps).
- `openzeppelin-contracts`: A library of modular and reusable smart contracts, including ERC20, ERC721, and more.
- `truffle`: A development environment, testing framework, and asset pipeline for Ethereum.

## Getting Started

### Prerequisites

- Node.js and npm
- Git
- Truffle

### Installation

1. Clone the repository:
    ```sh
    git clone --recurse-submodules git@github.com:GSWSN/00000000.git
    cd 00000000
    ```

2. Initialize and update submodules:
    ```sh
    git submodule init
    git submodule update
    ```

3. Install npm dependencies:
    ```sh
    npm install
    ```

### Usage

#### Compiling Contracts

Use Truffle to compile the smart contracts:
```sh
truffle compile

Deploying Contracts

You can deploy the contracts to a local development network:

truffle migrate

Or specify a network defined in truffle-config.js:

truffle migrate --network <network_name>

Running Tests

To run the tests for the smart contracts:

truffle test

Deployment to GitHub Pages

This project uses GitHub Actions to deploy static content to GitHub Pages. The workflow file is located at .github/workflows/static.yml. The deployment is triggered on pushes to the main branch.

Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project’s coding standards and includes appropriate tests.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements

	•	Dappsys
	•	OpenZeppelin
	•	Truffle Suite

### Explanation

1. **Overview**: Provides a brief introduction to the project.
2. **Structure**: Describes the submodules included in the repository.
3. **Getting Started**: Lists the prerequisites and step-by-step instructions to set up the project.
4. **Usage**: Details how to compile, deploy, and test the smart contracts.
5. **Deployment to GitHub Pages**: Briefly explains the deployment process using GitHub Actions.
6. **Contributing**: Invites contributions and explains how to contribute.
7. **License**: States the licensing information.
8. **Acknowledgements**: Credits the libraries and tools used in the project.