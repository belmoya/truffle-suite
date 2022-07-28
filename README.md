# truffle-suite
Desarrollo de smart contract en blockchain local. 

Proyecto Prework para Desarrollo de Aplicaciones Blockchain. Desarrollé un smart contract, luego generé una blockchain local y desplegué el contracto en la misma. 
#TruffleSuite #Solidity #Ganage 



CMD: 
Starting migrations...
======================
> Network name:    'development'
> Network id:      1659045670314
> Block gas limit: 6721975 (0x6691b7)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x2a3b5379fb758a4d8cdaba73df6247e453e3a4a3c0c8eda98c6b5122a7cbb8fb
   > Blocks: 0            Seconds: 0
   > contract address:    0x5fC6f4dB499296140624ea5A771970Dc34DD2E45
   > block number:        1
   > block timestamp:     1659046750
   > account:             0x445e1182dC352131F0e4043A88Df9601bB8F49fF
   > balance:             99.99502292
   > gas used:            248854 (0x3cc16)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00497708 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00497708 ETH


2_hello_blockchain.js
=====================

   Deploying 'HelloBlockchain'
   ---------------------------
   > transaction hash:    0x61d41f4dea85bfeb78101091b6822cccd91b1b5f09788428846a8877c1ac705c
   > Blocks: 1            Seconds: 5
   > contract address:    0xa7139BF38EE9651105BF493577b379E0d4744F1f
   > block number:        3
   > block timestamp:     1659046764
   > account:             0x445e1182dC352131F0e4043A88Df9601bB8F49fF
   > balance:             99.99146964
   > gas used:            135151 (0x20fef)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00270302 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00270302 ETH

Summary
=======
> Total deployments:   2
> Final cost:          0.0076801 ETH


truffle(development)>
undefined
truffle(development)> const instance = await HelloBlockchain.deployed()
undefined
truffle(development)> instance.sayHi()
'!Hello, blockchain!'
truffle(development)>
