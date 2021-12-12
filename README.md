# Fight Surety Dapp

This repository contains an Ethereum DApp that simulates an flight insurance service. It is not a full version of this kind of app but it is enough to illustrate how it could be implemented over Ethereum.

The project uses the libraries and versions. A brief description of its use is provided:

`Truffle Version : 5.4.23`
`Solidity : 0.4.24`
`Node : 14.16.0`
`NPM : 6.14.11`
`openzeppelin-solidity:1.10.0`

# Installation

Run the next steps to run the application:

Run this command inside the root FlightSurety folder project:

```bash
npm install
```

Compile the smart contracts

```bash
truffle compile
```

Execute ganache-cli with next parameters :

```bash
ganache-cli -a 20 -l 9999999 -m "brisk ketchup hollow truly blast flavor jacket organ armor right galaxy shop"
```

If you want to run the test cases:

```bash
truffle test
```

To deploy the smart contracts to Ganache you must run in terminal:

```bash
truffle migrate --network development
```

Start the server that register the Oracles and simulates their responses:

```bash
npm run server
```

To run the dapp frontend you should run this command:

```bash
npm run dapp
```
