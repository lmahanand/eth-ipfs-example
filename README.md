# eth-ipfs-example

## Steps to run the smart contract ##

Tools and Technologies: Solidity, Truffle, React JS, Mocha, Node.js, Infura, IPFS.

Steps are given considering smart contract is deployed in In Memory Ethereum network Ganache.

### truffle migrate --compile-all --reset --network ganache ###

### npm run start ###

Once the page is loaded, choose any file and click on Send IT button that will send the file to IPFS.

Once the file is uploaded successully, IPFS hash will be created against the uploaded file which can later be used to retrieve the original file.
