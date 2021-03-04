### Chain Desktop Wallet

Crypto.org Chain Desktop Wallet

### Warning
Crypto.org Chain Desktop Wallet and this library is currently in the beta development phase and subjects to changes. Before proceeding, please be aware of the following:

- This wallet is only testnet-ready, do not use in mainnet.
- Do not transfer any ERC20 tokens to addresses generated by this sample code as it can cause loss of funds.
- Crypto.org is not liable for any potential damage, loss of data/files arising from the use of the wallet.

### Installation

```
yarn install
```
Installs all the needed dependencies

### Development & Builds Processes

#### Web Target 🌐

```
yarn start
```
The command above runs the app as a normal web app in development, deployed at http://localhost:3000/

```
yarn build
```
Builds an optimized web distributable output for the repository.

The final output build should be ready to be deployed like any normal react web app. The /build folder is ready to be deployed 🚀


#### Electron Target 💻

```
yarn electron:dev
```
Runs the Electron app in the development mode.

The Electron app will reload if you make edits in the electron directory.
You will also see any lint errors in the console.


```
yarn electron:build
```
Builds the Electron app package for production to the dist folder.

The app is ready to be distributed!