# genhub

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

<video src="https://youtu.be/etK0MsXGRbg" width=100/>

## Examples Art Gifs (available on website)

https://2082346992-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Flt6e0pRnI5Xdcy7HrsNR%2Fuploads%2F9ayxrIUNsBx2iTCzmK2c%2Ftruchet.GIF?alt=media&token=cbe05195-ee96-4f44-ad66-a9bbbc5ae158
