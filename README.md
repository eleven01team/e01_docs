# GETTING STARTED
## OVERVIEW

Eleven01 is one of the fastest, highly-scalable blockchain protocol which aims to make blockchain technologies ready for real world use. We aim at establishing India as a benchmark for public as well as private workloads. Secure by default and privacy-focused, the Eleven01 protocol employs cutting-edge blockchain research to achieve high throughput through dynamic consensus and is designed to scale up to several thousand transactions per second.

Eleven01 provides a platform for developers to create, publish, and extend the core blockchain services beyond the core blockchain ledger. One of the biggest USPs of the Eleven01 protocol is the use of Oracles that will allow large-scale traditional centralized applications to incorporate blockchain into their existing infrastructure.

## ABOUT ELEVEN01

Eleven01 is India’s first-ever native protocol built to be capable of one of the fastest and most highly scalable blockchain protocols. It aims to take blockchain technologies to the next billion people, preparing for real world use cases. We strive to create a benchmark for public as well as private workloads. Secure by default and privately focused, the Eleven01 protocol employs cutting edge blockchain research to achieve high throughput through dynamic consensus.

Eleven01 provides a platform that allows developers a means to create, publish and extend the core blockchain services beyond the core blockchain ledger. One of the biggest USPs of Eleven01 protocol is the use of Oracles. This will allow large scale, traditional, centralised applications to employ blockchain into their existing infrastructure. It is designed from the ground up to be a use-case agnostic, topology-agnostic blockchain ledger.
Eleven01 protocol core software can be used to implement a public blockchain offering a cryptocurrency for anyone to join and transact with. It is also configured as a private, permissioned blockchain that can be used to build consortiums. In addition we are creating a “Marketplace”, where companies can buy, rent, or subscribe to smart contracts and services that will seamlessly integrate with Eleven01 chains.

The core features of Eleven01 include:

1. Dynamic consensus
2. Two tier identity verification 
3. Marketplace 
4. Customisable Oracle Implementation 
5. Identity management, Node management 
6. Usage of Key vault 

Eleven01 a competitive advantage over other blockchains. Implementing different consensus model for getting dynamic nature which includes IBFT, Raft, Clique PoA along with PoW.

## EXPLORE IN ELEVEN01

Eleven01 is a robust blockchain protocol, designed from the ground up to be a use-case agnostic, topology-agnostic blockchain ledger. It’s core software can be used to implement a public chain, offering a cryptocurrency that anyone can join and transact with. It can also be configured as a private, permissioned blockchain that can be used to build consortiums.

The goal is to provide a foundation that can be built upon and tailored to each application. The objective of this whitepaper is to discuss the features and USP (Unique Selling Proposition) of the Eleven01 protocol without going into the details of any of its specific implementation.

In addition to the protocol, we will also be unveiling the Eleven01 “Marketplace”, a place where companies can buy, rent, or subscribe to smart contracts and services that will seamlessly integrate with Eleven01 chains. The Eleven01 Marketplace is powered and run on our own protocol and thus enjoys all the features that Eleven01 has to offer

## CREATE AN ACCOUNT

**Developer Account Creation:**

The User has the flexibility of creating the account in two ways. They are:

1. By entering the details
  -a. After entering the details, click on “Confirm Email” button.
  -b. Verify your registered email by clicking on the verification link.
  -c. Enter details on application page and click on the “Sign-up” button.
  -d. Developer will be redirected to the landing page to access the content present in developers portal and create applications.
  
 *For **Login**,use the similar process but there won’t be any email verification.
 
2. By Social Authentications
  -a. We provide Github and Google as two open authentication options.
  -b. Based on preference choose any one. Click “Allow” on consent screen shown by chosen applications.
  -c. Developer will be redirected to the landing page to access the content present in developers portal and create applications.
  
*For **Login**,use the similar process for open authentication.
 
**User Account Creation:**

Developer has flexibility of creating the account in two ways. Those are:

1. By entering the details
  -a. After entering the details, click on “Confirm Email” button.
  -b. Verify your registered email by clicking on the verification link.
  -c. Enter details on application page and click on the “Sign-up” button.
  -d. User will be redirected to the landing page to access the content present in users portal and create applications.
  
*For **Login**, use the similar process but there won’t be any email verification

2. By social authentications
  -a. We provide Github and Google as two open authentication options
  -b. Based on preference choose any one. Click “Allow” on consent screen shown by chosen applications
  -c. User will be redirected to the landing page to access the content present in developers portal and create applications.
  
*For **Login**, use the similar process for open authentication.

## ARCHITECTURE AND COMPONENT OVERVIEW

This section contains the Architecture flowcharts with high level of details assigned to each component and states the relation between different components.

![alt text](https://developers.eleven01.io/assets/images/overview-structure.png)

## ELEVEN01 PUBLIC TEST NETWORK

Eleven01 TestNet is a public network which works on Raft consensus. Installation of testnet into our computer requires the following steps.

1. git clone  [git@github.com](https://developers.eleven01.io/)  :eleven01team/deployment-scripts.git
2. Change directory to deployment-scripts and run bootstrap.sh
3. This script will install all prerequisites which includes.
   - Tessera (0.6)
   - Go-lang(1.11.1)
   - Dependencies packages (libdb-dev, libleveldb-dev, libleveldb-dev, libleveldb-dev, libleveldb-dev, solc, sysvbanner, software-              properties-common, default-jdk, maven)
   - IPFS (optional)

``` shell 
cd deployment-scripts 
sudo ./bootstrap.sh 
```

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

**To Install IPFS**

While running bootstrap.sh script it will ask to install **IPFS**, if you want to install **IPFS** enter **"y"**

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

## ELEVEN01 CORE

### DYNAMIC CONSENSUS

The Eleven01 protocol provides a flexible, pluggable consensus model, when dealing with blockchain consensus protocols. This allows users to choose a particular consensus scheme that suits their need at genesis time. Currently, consensus protocols are going through rigorous academic research and one of our goals at Eleven01 is to support and improve these protocols.

### IDENTITY MANAGEMENT

Identity manager provides capabilities to the applications in the network to register , and authenticate a user and store user claims(passport, Aadhar) and policies. Identity manager has three levels of access.

1. Application (app): - Application has access to creating user and storing policies for a user.
2. Administrator (admin): - Admin has all the rights in a network.
3. User (user): - user can login and modify his own data.

### KEY VAULT STORAGE

Key Vault, also called a secret vault, holds the credentials of users (in encrypted form), so that they are secure against crackers trying to extract secrets.

Creating a Key Vault is a complex piece of engineering. It is much easier to pick up a working and proven open-source software. A security software should be open-source so that errors can be fixed as soon as they are found. With closed-source, implementers are dependent on the willingness of the vendor to provide the fix in a timely manner. It is also important to choose a software that has a large number of people working on it.

### NODE MANAGEMENT

Node Management comes under network category in which new nodes can be created, removed in terms of single or multiple nodes at a time. Selecting different consensus, number of nodes, permissioned or permissionless, network name, validator, admin or not, were assigned. Connection between different nodes and communication will be in Node management feature.

### GOVERNANCE

Governance Model is a set of policies defined to protect and secure the blockchain. Policies will impact user permissions, network access, and blockchain transactions.

### CUSTOMIZABLE ORACLE IMPLEMENTATION
An Oracle is essentially a trusted client on the blockchain. It has a unique account (a key pair) that runs off-chain, and provides data to the blockchain. It solves the requirement of external data feeds that can be integrated with the blockchain solution. The essential criteria for an Oracle is the trust that needs to be granted to its service.

Eleven01 has developed an improved way to integrate Oracles, enhancing the compatibility of the protocol.

### OFF-CHAIN STORAGE

Off-chain storage is used to reduce the size of a blockchain to make it more efficient. This is done by using only hashes of data objects in blockchain. The data objects themselves are stored in databases that are indexed by this hash. The database need not be stored at all nodes. A central or a distributed store can be used to store data objects. InterPlanetary File System (IPFS) is a Distributed Solution addresses the problem of storing hash indexed data objects.

## CREATE NODE AND JOINING A NETWORK

### BEFORE YOU BEGIN

Creating a Node in a public or private blockchain is a common thing for a blockchain developer but in order to create a node we have to connect with the blockchain by using the same chainID and it also depends on the configuration files of the blockchain. Manually adding nodes using the IP address is a tiresome process and may be difficult for a beginner.

What if you could become a participating node on a Private Network and use the previously created dApps by just following few instructions. Eleven01 provides that feature. All the keys that are related to your security and secrets are stored in a safe place that cannot be modified. From individual nodes to organisations, Eleven01 takes care of anything.

**Prerequisites to join a Network:**
    - Operating System: Ubuntu Linux 14.04 / 16.04 LTS (both 64-bit)
    - RAM: 2 GB
    - Geth Setup
    - Nodejs.
    - Git Support (already installed in recent linux versions).
    
## DOWNLOAD DEPENDENCIES

1. Git clone [git@github.com](https://developers.eleven01.io/) :eleven01team/deployment-scripts.git
2 .If you haven’t installed the network previously, change directory to deployment-scripts and run bootstrap.sh (or if you have installed ignore this step)
3. Go to deployment-scripts folder and run public_join.sh, it will create a new node and its configuration to join it to a network

``` shell
cd deployment-scripts    
./public_join.sh
Please enter network name you want to join[Default:TestNet]:
Please enter number of nodes to be created[Default:1]:
Please enter current node Ip[Default:127.0.0.1]:
```

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

geth attach networkname/qdata/node name/node/geth.ipc

``` shell
cd deployment-scripts              
geth attach TestNet/qdata/node2/node/geth.ipc     
```

![alt text](https://developers.eleven01.io/assets/images/truffle-migrate.jpg)

## PUBLIC BLOCKCHAIN API'S

Public blockchain Apis are classified into Node Api’s and Network Api's

### NODE API'S
1. /api/network/node/start
    - To start a node
    - Method - POST
    - Payload - { "networkName" : "", "nodeName": "" }
    - Response
        -i. Status code 200, {"result": Node started }
        -ii. Status code 400, {error: networkName not defined}|{error: nodeName not defined }
        -iii. Status code 404, {error: not found }

