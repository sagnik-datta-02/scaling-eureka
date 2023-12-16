# Solana NFT Trial
# Sagnik NFT
Sagnik NFT is an NFT having rarity and gem type, color, and description.
This can be used anywhere, Below are the Steps to use it.

### Build & Deploy
- `cd program`
- `cargo build-sbf`
- `solana config set --url devnet`
- contract deployment requires Solana, so get some. `solana airdrop 1`
- verify you have enough Solana to cover fees `solana balance`
- `solana program deploy target/deploy/nft.so`

### Operations
- Mint: Create new Sagnik NFT based on color and rarity and description inputs.
- Transfer: Send Sagnik NFT between accounts.
- Burn: Remove Sagnik NFT from circulation
