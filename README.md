## Cows Gone Mad Smart Contract

#### Cows Gone Mad Functionality

- Deployment (Owner)
  - Token Name
  - Token Symbol
  - Initialize Base URI
  - Initialize Not Revealed URI
- Admin (Owner)
  - Add Admin Address
  - Remove Admin Address
- Founder (Admin)
  - Add Founder Address (Admin)
  - Remove Founder Address (Admin)
- Mint
  - Mint Single
  - Mint Batch
- Burn an NFT
- Reveal NFT's (Owner)
- Set NFT per address limit (Admin)
- Set Price (Admin)
- Set Founders Price (Admin)
- Set Whitelist Price (Admin)
- Set max mint amount per session (Admin)
- Set base URI (Owner)
- Set base extension (Owner)
- Set not revealed URI (Owner)
- Pause NFT sale (Admin)
- Whitelist users (Admin)
- Remove whitelisted users (Admin)
- Withdraw from contract wallet (Owner)
##### View
- View Price
- View Founders Price
- View Whitelist Price
- View Token URI with tokenID
- View revealed status
- Check if address is whitelisted
- Check if address is a founder
- View all owner's tokens

#### Additional Functionality provided by openzeppelin

- Ownable contract
  - Check the owner address
  - Transfer Ownership
  - Renounce Ownership
