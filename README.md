# Analog-GMP

Send a message using a GMP gateway contract on Sepolia Testnet (Daily)

Still the same as yesterday using Remix ❗️

1. Create the BranchlessMath.sol file & copy the following script [BranchlessMath.sol](https://github.com/SRnode/Analog-GMP/blob/main/BranchlessMath.sol) and paste it into the file

2. Create the file Primitives.sol & copy the script [Primitives.sol](https://github.com/SRnode/Analog-GMP/blob/main/Primitives.sol) and paste it into the file

3. Create file IGateway.sol & copy the script [IGateway.sol](https://github.com/SRnode/Analog-GMP/blob/main/IGateway.sol) and paste it into the file

4. Select the IGateway.sol file & Go to the Solidity Compiler menu, click Compile IGateway.sol

5. Go to the Deploy & Run Transactions menu

6. In the Environment column, select Injected Provider - Metamask (Change the metamask network to Sepolia Testnet)

7. Contract select IGateway - contract/IGateway.sol

8. Copy Gateway Address: SEpolia Testnet 0x000000007f56768de3133034fa730a909003a165

9. Paste the sc gateway address in the At Address column, then click the At Address button

10. Check the details under the Deployed/Unpinned Contracts section, click the submitMessage function details, fill in the details below

➖destinationAddress: Enter the address of the contract created from Sepolia

➖destinationNetwork: 5

➖executionGasLimit: 30000

➖data: 0x01

11. Click transaction, a pop up appears in the wallet, just wait until the transaction is successful

12. Check the Remix terminal copy tx hash check at https://eth-sepolia.blockscout.com/ 

13. Submit tx hash to [https://testnet.analog.one](https://testnet.analog.one/#/?signup&referral=LSSWP7)

*The analog verification is a bit delayed, if there is an error just wait 30 minutes before verifying again
