 ## CREATE A DAPP
 
 ### INTRODUCTION
 
 This section provides details of contract language and how to create and deploy smart contracts. Eleven01 provides a platform that allows publishers to create, publish, and extend the core blockchain services beyond the core blockchain ledger. There is no need to construct and build these elements since they are a modular component of the system and can be used on an opt-in based model. Eleven01 abstracts the hardware elements and provides a simple API to create, deploy, and utilise these services, where one can connect to external data sources and web services. This allows those who are building their solution on Eleven01 to focus on application, and not complex infrastructure.

Eleven01 has developed an improved way to integrate Oracles, enhancing the compatibility of our blockchain protocol.

**Prerequisites to build a dApp**

![image](https://user-images.githubusercontent.com/39953416/60514105-61e81b80-9cf6-11e9-9e89-3242b8daaba6.png)

### DAPP CREATION BY TRUFFLE FRAMEWORK AND METAMASK

Developer can use Node.js or Python as languages to create a server for dApp if developer intends to create. Web3js and Web3py are currently available Ethereum APIs. We will be using Node.js to create a server so that developers can create Dapps with ease.

**Step1: Attach Eleven01 Custom RPC to Metamask**

1. Download the Metamask chrome extension and create an account.
2. Eleven01 provides a custom RPC to connect our blockchain. Please use the URL below and add it Custom RPC section in Metamask. Below are the Images for reference.

``` shell 
http://13.83.91.1:8083/api/node/rpc 
```

3. Open Metamask, click on dropdown of networks and click on custom rpc option. 

![image](https://user-images.githubusercontent.com/39953416/60514444-1f730e80-9cf7-11e9-8445-36a37ab63478.png)

![image](https://user-images.githubusercontent.com/39953416/60514531-48939f00-9cf7-11e9-9de3-f6f1f7fb43a1.png)

4. Install truffle globally by using the following command. 

``` shell 
npm install -g truffle@4.1.15 
```

**Step2: Folder Setup and Truffle Configuration**

5. Create a folder and execute a command truffle init (do not forget to install truffle globally in your computer).