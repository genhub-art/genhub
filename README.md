# Genhub.art

Genhub.art is a powerful open platform for the creation of generative art NFT collections. By using HTML5, anyone can deploy generators for collections that feature any rich media of their choice: 2D images, 3D models, algorithmic art, animations, sound, interactive experiences, or even complete video games and virtual worlds. 

Once you deploy you collection generator, genhub.art handles all the complexities of creating the collection smart contract, creating the minting page, handling minting logic, generating rich metadata for your generative NFTs, and many more.

We also provide examples and templates which you can use to get started instantly.

**Website** http://genhub.art/

**Docs** https://ivan-tsoninski.gitbook.io/genhub.art/


To clone with all submodule repositories:

```
git clone --recursive git@github.com:genhub-art/genhub.git
```

or clone the relevant repositories individually the standard way.

## Infrastructure

**Website** - built with Next.js, hosted on Cloud.run with continuous deployment via Docker and Github.

**Indexer** - indexes data about smart contracts state from the chain and stores it in the database. Built with Node.js and hosted on a cloud VPS.

**Database** - Supabase PostgreSQL database

**API** - PostgREST instance hosted on Cloud.run and connected to the database. Provides and efficient and expressive OpenAPI compatible way to query the database and filter data.

**Smart Contracts** - written in Solidity, built and deployed with Hardhat. Include Collection.sol (an ERC721 based smart contract) and Factory.sol (creates and keeps track of collections).

## Video

<a href="http://www.youtube.com/watch?feature=player_embedded&v=etK0MsXGRbg" target="_blank">
 <img src="http://img.youtube.com/vi/etK0MsXGRbg/mqdefault.jpg" alt="Watch the video" width="500" border="10" />
</a>



## Examples Art Gifs (available on website)


![cat](https://github.com/genhub-art/genhub/assets/44375889/9ab103de-33ef-473e-b975-796ef690c64d)
![orbit](https://github.com/genhub-art/genhub/assets/44375889/63ac3c94-6a2e-4385-8e89-70c2c913eca4)
![truchet](https://github.com/genhub-art/genhub/assets/44375889/58f253dc-5ccc-48ac-b254-9aa0938ce335)


