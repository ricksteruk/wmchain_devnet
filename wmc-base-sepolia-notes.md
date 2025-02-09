# WM CHAIN Base Seploia testnet exploration notes

Hi! Here are some basic details to get you started exploring the WM Chain testnet rolling up to Base Sepolia.  This information is mostly collected from ENO community testing that has been shared in Discord

## Create New Chrome Profile and install EVM Wallet

It's best to keep this test setup totally isolated from your main account and wallets - so create a new Profile for Chroms and download an EVM browser extension wallet.   [MetaMask](https://metamask.io/) works well but is a little ugly and fiddly with settings in places, [Coinbase Wallet](https://wallet.coinbase.com/)  is much easier on the eye but does not allow you to add custom tokens so is probably not a good choice.  [Rabby](https://rabby.io/) seems to be a good compromise of functionality and nice UI.  There are many other wallets you can try!

If you are not going to explore all the options just go with Metamask.

You should create a new wallet on one of these and if you want to explore the other wallets then import the seed phrase into one of those if you want to try it out.  I would advise using separate profiles in Chrome - or you can just delete or disable the wallet extensions you are not using once you've tested them out to avoid possible conflicts.

## Obtain ETH on Sepolia testnet<br> ( omit this step if you prefer to directly use a Faucet for Base Sepolia ETH )

First we will need to obtain some ETH on the Sepolia testnet.

You can visit this Google faucet - you will need to sign in to your Google account and you can claim 0.05 ETH per 24 hours.
https://cloud.google.com/application/web3/faucet/ethereum/sepolia

( If just using the Google facuet - claim - wait 24 houra - claim again then continue )

Or if you prefer not ot wait use this faucet - but you will need to have at least 0.01 ETH on your mainnet Ethereum account
https://faucet.quicknode.com/ethereum/sepolia

You should probably obtain at least 0.06 ETH on the Sepolia testnet so you might need to make a few claims


## Now use Superbridge to bridge the ETH from Sepolia to the Base sepolia testnet.

Visit this page and connect your MetaMask wallet - you cannot bridge all your ETH - you need a little for gas
https://testnets.superbridge.app/base-sepolia

You will need just over 0.05 ETH on the Base Sepolia network

( If you made 2 claims to the Google facuet - the maybe just bridge 0.09 ETH for example )

### ALTERNATIVE - Use a Faucet to directly obtain ETH on Base Seploia

Here are some possibilities - some may make you sign up with a social media, or make an account on their platform.

https://www.alchemy.com/faucets/base-sepolia<br>
https://bwarelabs.com/faucets/base-sepolia

other options here:
https://docs.base.org/docs/tools/network-faucets/



## Use WM Faucett to obtain WMTx testnet tokens on Base Sepolia

`NOTE: Some people have had errors using the WM Faucet - try creating a new blank Chrome profile or disabling any other extensions if you have problems - install the wallet browser extension and import your seed phrase.  Coinbase wallet extension might be more reliable than MetaMask`

Visit the WM faucet:
https://faucet-testnet-base.worldmobile.net/

You will need to sign in - login details can be found here: https://discord.com/channels/739450842108919828/1151424831473066004/1312789293407797280

`Make sure you select the Base Sepolia netwok in near the top right`

Connect your wallet, copy and paste your wallet address - then claim your 1 WMTX.   You can claim once per 24 hour period

If the WMTx does not show in your wallet click "Add Token" - and enter the contract address: 0xa400B9E45e91863ab675105C66B9d71466AF47b8



## Bridge your WMTx from Base Sepolia to the WM Chain

visit the WMTx bridge:
https://bridge-testnet-base.worldmobile.net/

You will need to sign in - login details can be found here: https://discord.com/channels/739450842108919828/1151424831473066004/1312789293407797280

Connect your wallet and then bridge some WMTX over to the WM Chain.

`Make sure you select the Base Sepolia netwok in near the top right`

You can try bridging your WMTx back and forth between chains.



## Visit the WM Chain explorer

visit the exlorer at:
https://explorer-testnet-base.worldmobile.net/

You will need to sign in - login details can be found here: https://discord.com/channels/739450842108919828/1151424831473066004/1312789293407797280

Have a good look around at the various screens!


## Next Steps

Visit Trident's site, connect your wallet and try to claim some Lampo and then stake it.  https://wmc-testing.com/faucet

This video shows you how simple it is to mint some Meme coins on the WM Chain - you just need to connect your wallet on the WM Chain instead of AVAX testnet as shown
https://youtu.be/4bN9QRTs_1k?si=gBj-1u8lEMnS0Z2G
<br>
( updated version of his video guide to mint ERC-20 on Eth https://youtu.be/SuPs-s6DPQU?si=mRYXIYmbmnxVsu-r )

Mint some meme coins and send them to other peopele in Discord!  They will tell you their wallet addresses if you ask them who wants your coins!!
( maybe also see IBIS's token guide below too )

This YouTube playlist has a really good guide to getting started with EVM and then starting to code and build meme coins and so on. [YouTube Web2 to Web3 playlist](https://youtube.com/playlist?list=PLJz1HruEnenAf80uOfDwBPqaliJkjKg69&si=5eID8ApAtITnITcj)

It follows along with parts of [Speed Run Ethereum](https://speedrunethereum.com)


## Other Community created guides

IBIS Bin Chicken WM chain setup guide:
Bin Chicken Guide:
https://github.com/bnchk/wmc_testnet/tree/main

IBIS Bin Chicken token mint guide:
https://github.com/bnchk/wmc_testnet/blob/main/TOKEN_MINT.md

IBIS Bin Chicken NFT mint guide:
https://github.com/bnchk/wmc_testnet/blob/main/NFT_MINT.md

Nico WM chain setup guide:
https://github.com/nodebasewm/nodebasewm.github.io/blob/main/wmc/testnet-guide.md

Catman load test guide:
https://github.com/catman-1234/multi-wallet-block-fill


