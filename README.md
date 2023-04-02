<div align="center">
  <p align="center">
    <img src="./public/apple-touch-icon.png" width=150>
    <br/>
    <a href="https://florinouns-dapp.vercel.app/" target="blank"><img src="./src/assets/img/logo.png" width="350" alt="FloriNouns Logo" /></a>
  </p>
</div>

# FloriNouns Dapp

## About The Project

This project is affiliated with [FGCU](https://www.fgcu.edu/) and will allow users to mint NFTs from the FloriNouns NFT collection.

### Built and Deployed With

- [React](https://reactjs.org/)
- [Mantine](https://mantine.dev/)
- [Web3.js](https://github.com/ChainSafe/web3.js)
- [Factoria F0](https://factoria.app/)
- [Vercel](https://vercel.com/)

## How to run the app locally

### Prerequisites

- Install Node.js at https://nodejs.org

### Steps

1.  Clone the repo.

    ```sh
    git clone https://github.com/FloriNouns/florinouns-dapp.git
    ```

2.  Install NPM packages.

    ```sh
    npm install
    ```

3.  Duplicate `.env.example` and rename it to `.env`.
4.  Enter variables into `.env`

    - Chain ID should match where your contract is deployed. If using our testing contract, use Rinkeby (Chain 4).

          REACT_APP_CHAIN_ID='4'

    - Enter the address of your Factoria F0 contract. Use address seen below if using our testing contract.

          CONTRACT_ADDRESS='0xaCd530bDc049E269dcd743D6E849092c983E7799'

    - The application will try to use MetaMask as your provider, so RPC endpoints are optional.

5.  Run the application locally
    ```js
    npm start
    ```
