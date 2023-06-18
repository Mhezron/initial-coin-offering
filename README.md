# Initial Coin Offering (ICO)

 Initial Coin Offering (ICO) smart contract and web application.
 The ICO is built on the Ethereum blockchain and allows individuals to contribute funds in exchange for newly created tokens.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

An Initial Coin Offering (ICO) is a fundraising mechanism commonly used by blockchain-based projects to secure capital. This repository provides an implementation of an ICO smart contract and a simple web application to facilitate the ICO process.

## Features

- ERC-20 Token: The ICO contract generates ERC-20 compliant tokens that can be transferred and held by contributors.
- Token Sale: Contributors can send Ether (ETH) to the ICO contract and receive tokens in exchange based on the ICO rate.
- Whitelisting: The ICO contract supports whitelisting to restrict participation to specific addresses.
- Time-Based Phases: The ICO contract can be configured with different phases, each with its own rate and duration.
- Refund Mechanism: If the soft cap is not reached, contributors can initiate a refund and retrieve their contributed funds.

## Prerequisites

To set up and run the ICO smart contract and web application, ensure you have the following prerequisites:

- Node.js: [https://nodejs.org](https://nodejs.org) (version 14 or above)
- Truffle: Installation instructions can be found at [https://www.trufflesuite.com/truffle](https://www.trufflesuite.com/truffle)
- Ganache (or other Ethereum development network): Installation instructions can be found at [https://www.trufflesuite.com/ganache](https://www.trufflesuite.com/ganache)

## Installation

Follow these steps to set up and run the ICO smart contract and web application:

1. Clone the repository or download the source code as a ZIP file.
2. Open a terminal and navigate to the project directory.
3. Install the project dependencies by running the following command:
   ```
   npm install
   ```
4. Compile the smart contracts and migrate them to the development network by running:
   ```
   truffle migrate --network development
   ```

## Usage

1. Start the development network (e.g., Ganache) and ensure it is running on the default port.
2. Run the web application locally by executing the following command:
   ```
   npm run dev
   ```
3. Access the web application in your browser at `http://localhost:3000`.
4. Connect a wallet (e.g., MetaMask) to the development network.
5. Follow the on-screen instructions to contribute Ether (ETH) to the ICO and receive tokens.

## Contributing

Contributions to the ICO project are welcome!

## License

The ICO project is open source and released under the [MIT License](LICENSE). 

## Acknowledgments

The ICO project relies on various open source libraries, frameworks, and resources. We would like to acknowledge the contributions of the developer community and the availability of free and accessible tools that make projects like this possible.
