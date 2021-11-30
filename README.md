# Minting Website for CSB

[https://crypto-ski-bums.netlify.app/](https://crypto-ski-bums.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/e6942ea0-e9b7-40b3-bcf2-c55afc5941c1/deploy-status)](https://app.netlify.com/sites/crypto-ski-bums/deploys)

This is the minting website for the CSB project. Currently this project is under-construction and utilizes the Solana development network.

## Mint a Sample NFT

Follow these steps to mint a sample NFT from our example domain.

### 1. Create a Phantom Wallet

Add the [Phantom Wallet Chrome Extension](https://chrome.google.com/webstore/detail/phantom/bfnaelmomeimhlpmgjnjophhpkkoljpa?hl=en). Once added, connect and create a new wallet.

### 2. Set Phantom to view `devnet`

In the phantom wallet select ⚙️ **settings** -> **Change Network** -> `https://api.devnet.solana.com`. The minting example only works on the devnet.

### 3. Connect your wallet

Go to the [CSB Minting Page](https://crypto-ski-bums.netlify.app/), and click **Connect Wallet**. Select your phantom wallet.

### 4. Airdrop `devnet` funds to your wallet

If you do not have funds on the devnet you can airdrop funds using the [solona dev tools](https://docs.solana.com/cli/install-solana-cli-tools#use-solanas-install-tool). Once installed you can run the following command to airdrop 10 SOL to a wallet on the devnet:

```
solana airdrop 10 <RECIPIENT_ACCOUNT_ADDRESS> --url https://api.devnet.solana.com
```

### 5. Mint an NFT

Once your wallet is connected you will see how many NFTs there are total, how many have been minted, and how many are available to mint. If there are NFTs available you can mint them by pressing the **MINT** button.

---

## Dependencies

This is a create react app project forked from [Candy-Machine-Mint](https://github.com/exiled-apes/candy-machine-mint).
