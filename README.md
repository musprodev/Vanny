

## Explanation of Tests

- ```setUp()```: Initializes the contract and sets up test addresses.
- ```testMint()```: Tests the minting functionality, ensuring that the minted tokens are correctly assigned and that the total supply is updated.
- ```testTransfer()```: Tests transferring tokens between addresses and checks the balances.
- ```testFailTransferInsufficientBalance()```: Tests that transferring more tokens than available fails.
- ```testFailMintToZeroAddress()```: Tests that minting tokens to the zero address fails.
- ```testFailTransferToZeroAddress()```: Tests that transferring tokens to the zero address fails.
