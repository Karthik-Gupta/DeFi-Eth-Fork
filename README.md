# DeFi-Eth-Fork

Will be forking Ethereum mainnet so that we can interact with existing contracts, today we will interact with the DAI stablecoin contract.

Running the application:

// Install the dependencies
npm i
// Running ganache with your own infura network, fork the mainnet and unlock coinbase account
npx ganache-cli -f <Your INFURA URL> -m “your 12 word mnemonic” --unlock 0x503828976D22510aad0201ac7EC88293211D23Da -i 9997 -p 8545
// Open truffle console in different session
npx truffle console
// run truffle commands
build / compile / test / migrate / run
