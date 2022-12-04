Download & Install NodeJs

Create an account on alchemy
Create app on alchemy
Create Folder: hellworld (mkdir hellworld)  then cd hellworld
npm init
npm install --save-dev hardhat
npx hardhat
❯ Create an empty hardhat.config.js
mkdir contracts
mkdir scripts
pm install dotenv --save
- Create .env file
#API_URL = "https://eth-goerli.alchemyapi.io/v2/your-api-key"
#PRIVATE_KEY = "your-metamask-private-key"
npm install --save-dev @nomiclabs/hardhat-ethers "ethers@^5.0.0"
npx hardhat compile
npx hardhat run scripts/deploy.js --network goerli