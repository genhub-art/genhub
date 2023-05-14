# Genhub.art

Genhub.art is a powerful open platform for the creation of generative art NFT collections. By using HTML5, anyone can deploy generators for collections that feature any rich media of their choice: 2D images, 3D models, algorithmic art, animations, sound, interactive experiences, or even complete video games and virtual worlds. 

Once you deploy you collection generator, genhub.art handles all the complexities of creating the collection smart contract, creating the minting page, handling minting logic, generating rich metadata for your generative NFTs, and many more.

We also provide examples and templates which you can use to get started instantly.

**Website** - https://genhub.art

**Docs** - https://ivan-tsoninski.gitbook.io/genhub.art

**API** - https://api.gehub.art

To clone with all submodule repositories:

```
git clone --recursive git@github.com:genhub-art/genhub.git
```

or clone the relevant repositories individually the standard way.

The **Docs** have all of the below information.

## Video

<a href="http://www.youtube.com/watch?feature=player_embedded&v=etK0MsXGRbg" target="_blank">
 <img src="http://img.youtube.com/vi/etK0MsXGRbg/mqdefault.jpg" alt="Watch the video" width="500" border="10" />
</a>

## Infrastructure

**Website** - built with Next.js, hosted on Cloud.run with continuous deployment via Docker and Github.

**Indexer** - indexes data about smart contracts state from the chain and stores it in the database. Built with Node.js and hosted on a cloud VPS.

**Database** - Supabase PostgreSQL database

**API** - PostgREST instance hosted on Cloud.run and connected to the database. Provides and efficient and expressive OpenAPI compatible way to query the database and filter data.

**Smart Contracts** - written in Solidity, built and deployed with Hardhat. Include Collection.sol (an ERC721 based smart contract) and Factory.sol (creates and keeps track of collections).

## How to launch your collection

For a more detailed explanation you can see the docs: https://ivan-tsoninski.gitbook.io/genhub.art/launch-your-collection

- Clone our one of our example/templates
- Modify it to your liking
- Modify the window.metadata() function
- Upload the whole folder to our website
- Play around with the preview by clicking **[Randomize]** to make sure everything is working correctly
- Enter details about your collection (title, description, price, max supply)
- Click **[Create Collection]**
- Confirm the transaction
- In a few minutes, the collection will be available in the **Collections** page or under **Profile -> Creations**
- Anyone can use you collection's page to explore your generator by clicking **Variations** and if they like what they see they can click **Mint** to mint their own random NFT.

## API

To learn more about how to use the API you can visit the docs: https://ivan-tsoninski.gitbook.io/genhub.art/api

Available at: https://api.genhub.art
- GET https://api.genhub.art/factories
- GET https://api.genhub.art/collections
- GET https://api.genhub.art/nfts
- GET https://api.genhub.art/rpc/get_nft_metadata?chain=...&collection=...&token_id=...

## Roadmap

Currently, genhub has the following features:
- Creating and deploying collections
- Rich Metadata with attributes/properties
- Custom minting page for each collection
- Collection previews

We are planning to implement the following features soon:
- Parameters for NFTs (allow customization at time of minting)
- Secondary Marketplace
- Multichain Support (EVM compatible) 

## Examples Art Gifs (available on website)

**Interactive Cat**

![cat](https://github.com/genhub-art/genhub/assets/44375889/9ab103de-33ef-473e-b975-796ef690c64d)

**Animated Solar System**

![orbit](https://github.com/genhub-art/genhub/assets/44375889/63ac3c94-6a2e-4385-8e89-70c2c913eca4)

**Truchet Tile Maze Algorithmic Art**

![truchet](https://github.com/genhub-art/genhub/assets/44375889/58f253dc-5ccc-48ac-b254-9aa0938ce335)


