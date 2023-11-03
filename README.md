# BlockChain-4-E-Voting
Voting System using Block Chain

# Tools Required:

Metamask
Python 
FastAPI
MySQL Database

# Installation steps:

Open a terminal

Clone the repository by using the command git clone https://github.com/susmithakolla/BlockChain-4-E-Voting
 
Download and install Ganache.

Create a workspace named developement, in the truffle projects section add truffle-config.js by clicking ADD PROJECT button.

Download Metamask extension for the browser.

Open MySQL and create database named voters.

Install truffle globally npm install -g truffle

Go to the root directory of repo and install node modules npm install

Install python dependencies pip install fastapi mysql-connector-python pydantic python-dotenv uvicorn uvicorn[standard] PyJWT

# Steps to Run Commands:

Open terminal at the project directory

Open Ganache and it's development workspace.

open terminal in project's root directory and run the command truffle console

compile the smart contracts with command compile Bundle app.js with browserify

 browserify ./src/js/app.js -o ./src/dist/app.bundle.js
 
Start the node server node index.js

Navigate to Database_API folder in another terminal cd Database_API

start the database server by following command uvicorn main:app --reload --host 127.0.0.1

Open new terminal and migrate the truffle contract to local blockchain truffle migrate
