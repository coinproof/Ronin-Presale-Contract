# Ronin-Presale-Contract

Steps to deploy:

Step 1. Compile and provide **Payment Address** (Wallet that will collect BNBs from presale) and **Token address** to deploy RoninSwap-contract-RoninPresale.sol

Step 2. Verify contract

Step 3. Send 4B tokens to this contract from Ronin Token Contract (ALSO REMEMBER TO EXCLUDE PRESALE CONTRACT ADDRESS FROM ALL FEES USING "excludeFromAllFees" function on Ronin token contract

step 4. Whitelist addresses using "whitelistAddresses" function. Input the wallets in an array i.e. [walletaddress,walletaddress,walletaddress,.................,walletaddress] (No space required and each walletaddress is followed by a "," except the last one.

Step 5. Execute "startSwap" from deployer's wallet and set it "true" (without the quotes obvio) to allow people to swap using either the presale UI or the BSC explorer

Step 6. Execute "stopSwap" once presale ends and HC is reached.

Step 7. Execute "canClaim" and set it to "true" after adding Liquidity at PCS and NOVASWAP to let investors claim their tokens.

Step 8. Execute "withdrawOtherTokens" to claim any RONIN tokens that are left unsold after presale conclusion.
