# MultiMinter for sRibbits:

## To do:

- add logic to fetch the current holders of the nft from the Songbird Explorer (https://songbird-explorer.flare.network/api-docs)
- add button to trigger above action (trigger `?module=token&action=getToken&contractaddress={contractAddressHash}`)
- populate the ui with the JSON array returned from the API call
- sign with your wallet address to approve the transactions (can this be automated?)

## Wishlist:

- Frontend Testing library
- Converter - Convert from and to 18 decimal number
- Upload CSV option in multi-sender
- Divide transactions in batch of 500 transfers for multisender
- Set max lock time for locker
- Create current-info page which will show - current wallet-address and chainId
- Add to Metamask buttons for faucet tokens
- Add ERC20, ERC721 and ERC1155 Generator and Minter
