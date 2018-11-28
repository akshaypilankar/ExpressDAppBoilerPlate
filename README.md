# ExpressDAppBoilerPlate
Boiler plate for Dapp with Web3 1.0  

### Setup


### Project Setup

```bash
git clone https://github.com/akshaypilankar/ExpressDAppBoilerPlate.git 
cd ExpressDAppBoilerPlate
npm install # Installs dependencies
npm run start
```
## Main network or any Ethereum testnet 
- copy this code to in index.js
```bash
var web3 = new Web3();
var provider = new Web3.providers.WebsocketProvider("wss://mainnet.infura.io/ws"); //case of mainnet
var provider = new Web3.providers.WebsocketProvider("wss://ropsten.infura.io/ws"); //case of testnet
var provider = new Web3.providers.HttpProvider("http://localhost:port number"); //in case of local or ganache
web3.setProvider(provider);
```
## web3 guide
https://web3js.readthedocs.io/en/1.0/web3-eth.html

## Thanks
pilankar.akshay3@gmail.com
