# E-Voting-System-Ethereum-Blockchain


This project has E-Voting System application in Ethereum. This project has feature like you can count a vote between two or many candidates using your account from ganache with metamask. Here we made a system like everyone can vote using only one account. If you tried to vote again using same account then it will restrict. Here we provide the prerequisites like truffle. Truffle can provide you to handle frontend part and also provide tools to make smart contract. And In this project we achieve the functionality of E-Voting system by using truffle and other applications which are mentioned below.

Anyone can used this project and work on that project. You just need to install following prerequisites and run it.

In this project I build a client side application that will connect to the smart contract. This application have the candidate id, name
and votes. We can cast a code for specific candidate by using account that we are connected to the blockchain.
By using metamask, I cast the vote from one account only, If I tried the multiple votes from one account it will show me error.

### DIRECTORY STRUCTURE

		build/contracts/	contains Election and Migration json files


### Dependencies requirements :-

1. Node Package Manager(NPM):- We required this dependency. You can download Node.js or by using following command you can install npm.

		npm install -g npm	
   You can see if you have node already installed by going to your terminal and typing:
		
		$ node -v
2. Truffle Framework :- Our next dependency is the truffle framework. This framework is allows us to build decentralised application 
												on the ethereum blockchain. It provide a tool that allow us to write smart contract with solidity programming 
												language.
												You can install Truffle with NPM in your command line like this:

		npm install -g truffle
4. Ganashe :- The next dependency is Ganache, a local in-memory blockchain. You can install Ganache by downloading it from the Truffle 
							Framework website. It will give us 10 external accounts with addresses on our local Ethereum blockchain.
							
		https://www.trufflesuite.com/ganache
6. Metamask :- Metamask is the google chrome extension. We need to connect metamask for use blockchain. By using this we will able to connect our local 
								Ethereum blockchain with our personal account.To install Metamask, search for the Metamask Chrome plugin in the Google Chrome web store.
								

### Execution Process :- 

* We assign our smart contract to a variable called "Election". We add it to the manifest of deployed contracts to ensure that it gets deployed when we run the migrations. Now let's run our migrations from the command line like this:

		$ truffle migrate
* By using above command we successfully migrated our smart contract to the local Ethereum blockchain. Now we can open the console to interact with the smart contract by using following command:

		$ truffle console
* After making all the smart contract, lets view the client side application in the browser. before that make sure you have migrated our smart contract by using fllowing command :

		$ truffle migrate --reset
		
* Now we can start our development server by using following command :

		$ npm run dev
After running above command new browser window onen automatically with client-side application.
If the browser shows the Loading... then its indicates that we do not connect blockchain yet. We need to connect blockchain using ganache and import one account
from ganache.
Now we can vote on our client side application and the casted vote is displayed in front of the candidates name.

# Features
* In this repository you will find all the prerequisites like Truffle dependency which allows us to build decentralised application on the Ethereum Blockchain. It provides a suite of tools that allow us to write smart contracts with the solidity programming language. It also enables us to deploy them to the blockchain. It also provides us a platform to develop our client side application.
* You just need to focus on your business logic that is smart contracts.

