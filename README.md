# Decentratwitter

Decentratwitter is the name of my Social dApp for this stackup bounty. The aim of this project is to provide users with a simple frontend UI with all the features of Writing Smart Contract, React & Testing, Blockchain Interaction, Development Framework, Metadata storage, Navigational components

**Smart Contract Features and Functionality:**

Our smart contract serves as the backbone of a decentralized social networking dApp. It incorporates several innovative features to create a secure and user-centric social media experience:

1. **User Profiles:** Users can create and manage their profiles on the blockchain. Personal information is stored securely, and users have control over their data. Within this dApp, users can craft and manage their profiles on the blockchain infrastructure. Personal data remains stored in a secure manner, with users retaining full authority over their information.

2. **Posts and Interactions:** Users can create posts, like, and comment on posts. These interactions are recorded on the blockchain, ensuring transparency and immutability.

3. **Decentralized Follow System:** Unlike traditional social media platforms, our dApp employs a decentralized follow system. Users can follow other profiles, and this information is stored on the blockchain, removing the need for a central authority.

4. **Censorship Resistance:** Due to the decentralized nature of the application, censorship is minimized. Posts and accounts cannot be taken down or blocked by a single entity.

5. **Monetization and Tokens:** We integrated a token system into the smart contract, allowing content creators to monetize their posts. Users can tip content creators with tokens they earn from engagement or purchase.

**Web Framework and Libraries:**

Our dApp leverages a variety of technologies for a seamless user experience:

1. **Frontend:** We chose React.js as our frontend framework for its modular components and dynamic updates. This allows users to easily navigate through profiles and posts.

2. **Web3.js:** To interact with the Ethereum blockchain and the smart contract, we used Web3.js. This library enabled us to connect the frontend with the decentralized backend.

3. **IPFS:** For storing images and other media, we integrated the InterPlanetary File System (IPFS). This ensures efficient and decentralized storage of user-generated content.

4. **UI Framework:** We employed Material-UI to design a clean and intuitive user interface, enhancing the overall user experience.

**Social dApp Overview:**

Our decentralized social dApp represents a paradigm shift in social networking. By utilizing blockchain and decentralized technologies, it empowers users to have full control over their data and interactions. Unlike traditional platforms, this dApp puts users in charge, removes intermediaries, and fosters a community-driven environment. With censorship-resistant features, content monetization, and a transparent architecture, it stands as a testament to the potential of blockchain in revolutionizing social media.

For a more comprehensive understanding, Explore our dApp's functionalities and experience the future of social networking on the [Firebase](https://decentratwitter.web.app/).








## Technology Stack & Tools

- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Ethers](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ipfs](https://ipfs.io/) (Metadata storage)
- [Firebase](https://firebase.google.com/) (Web hosting)
- [React routers](https://v5.reactrouter.com/) (Navigational components)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/), should work with any node version below 16.5.0
- Install [Hardhat](https://hardhat.org/)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
```
$ cd decentratwitter
$ npm install
```
### 3. Boot up local development blockchain
```
$ cd decentratwitter
$ npx hardhat node
```

### 4. Connect development blockchain accounts to Metamask
- Copy private key of the addresses and import to Metamask
- Connect your metamask to hardhat blockchain, network 127.0.0.1:8545.
- If you have not added hardhat to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Hardhat". For the "New RPC URL" field enter "http://127.0.0.1:8545". For the chain ID enter "31337". Then click save.  


### 5. Run deploy script to migrate smart contracts
`$ npx hardhat run scripts/deploy.js --network localhost`

### 6. Run Tests
`$ npx hardhat test`

### 7. Launch Frontend
`$ npm run start`

License
----
MIT

