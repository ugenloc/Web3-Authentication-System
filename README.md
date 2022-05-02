# Web3 Authentication System
This is a simple web3 login system that prompts user to sign in using their metamask wallet.
This login system was created with Moralis SDK. Moralis is a leading web development platform that offers everything that the user needs to create, host, and grow great dApps in one place. Think of moralis as the firebase of crypto.

## Requitement
* Moralis severUrl
* Moralis appId

## Follow the instructions below to create a moralis severUrl and appSId

### 1. Create a free account
Go to [moralis](https://moralis.io) and sign up for a free account.

### 3. Create a Moralis Server
Click Create a new server in the top right corner and select mainnet server.

### 4. Select Dapp Network
Give your server a name, select a location and select your prefered blockchain networks or select all.

### 4. View severUrl and appId
Soon as your sever is created click on view to see your sever url and application id

### 4. Copy and paste the sever url and app id
Paste your sever url and app id as value to the severUrl and appId variable inside the main.js file.


/* Moralis init code */
const serverUrl = "https://xxxxx/server";
const appId = "YOUR_APP_ID";
Moralis.start({ serverUrl, appId });


