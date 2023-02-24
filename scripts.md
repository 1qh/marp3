- Building a decentralized crowdfunding app that connects project creators with backers using the Ethereum blockchain and NextJS

# Intro

- An overview of decentralized crowdfunding and the benefits of building a decentralized crowdfunding app

  - Welcome to our presentation on building a decentralized crowdfunding app using Ethereum blockchain and NextJS
  - Decentralized crowdfunding is a new approach to fundraising that allows project creators to connect directly with backers, without the need for intermediaries such as banks or crowdfunding platforms
  - The benefits of decentralized crowdfunding include increased transparency, lower fees, and greater control for project creators
  - In this presentation, we'll be discussing the key features of our app, how we built it, and how it works

# Problem Statement

- Identifying the challenges with traditional crowdfunding platforms and how our decentralized crowdfunding app solves them

  - Traditional crowdfunding platforms such as Kickstarter or Indiegogo have several challenges, including high fees, lack of transparency, and centralized control
  - High fees can take away a significant portion of the funds raised, reducing the amount of money that reaches the project creator
  - Lack of transparency can lead to questions about where the funds are going and how they are being used
  - Centralized control can lead to censorship or bias, where certain projects are favored over others
  - Our decentralized crowdfunding app addresses these challenges by using the Ethereum blockchain, which ensures transparency, lower fees, and decentralized control

# Technical Architecture

- An overview of the technical architecture of our decentralized crowdfunding app

  - Our app is built using NextJS, a popular React-based framework for building server-side rendered web applications
  - The front-end of the app communicates with the back-end, which is built using Solidity, a smart contract programming language used to build decentralized applications on the Ethereum blockchain
  - We use Ether.js, a popular JavaScript library for interacting with the Ethereum blockchain, to send and receive transactions
  - Our app is deployed on the Goerli test network, a test network for the Ethereum blockchain that allows us to test and deploy our app without incurring real-world costs

# Features of the App

- A look at the key features of our decentralized crowdfunding app

  - Our app has several key features that make it a powerful tool for project creators and backers alike
  - Project creators can submit their projects to the app and set a funding goal, as well as a deadline for reaching that goal
  - Backers can browse through the available projects and fund them using Ethereum or other supported cryptocurrencies
  - The app ensures transparency by displaying real-time updates on the progress of each project, including the amount raised and the number of backers
  - Backers can also interact with the smart contract directly by calling the "donate" function to contribute funds to a project

## Crowdfunding Page

- This is the main page of our app, where users can browse through all the crowdfunding campaigns available
- They can also filter campaigns based on different categories such as technology, arts, education, and more.

## Campaign Details

- When a user clicks on a campaign from the Crowdfunding page, they will be taken to this page which displays detailed information about the campaign such as the funding progress, the number of contributors, and the deadline for contributions
- The user can also make a contribution by entering the amount they want to contribute and clicking on the Donate button.

## Create Campaign

- This page allows users to create a new crowdfunding campaign
- They can enter details such as the title, description, funding goal, and deadline
- Once they click on the Create button, the MetaMask popup will appear asking them to confirm the transaction.

- Submitting a Project

  - To submit a project, project creators need to connect their Ethereum wallet to the app
  - Once connected, they can fill out a form with the details of their project, including a title, description, funding goal, and deadline
  - After submitting the project, it will be added to the list of available projects on the app
  - Backers can then browse through the list of projects and decide which ones they want to fund

## Profile Page

- The Profile page displays all the campaigns created by the user
- It works similarly to the Crowdfunding page, but it only shows campaigns created by the user who is currently logged in.

## Connect Wallet

- Before users can create campaigns or make contributions, they need to connect their Ethereum wallet to the app
- This can be done by clicking on the Connect Wallet button which will prompt the user to select their preferred wallet and then authenticate the connection.

## Transaction Confirmation

- Whenever a user creates a new campaign or makes a contribution, a MetaMask popup will appear asking them to confirm the transaction
- This is a security measure to prevent unauthorized transactions from taking place.

# Testing the Smart Contract

- Testing the smart contract is a crucial step in the development process
- By testing the contract, we can ensure that it functions as intended and avoid potential bugs and vulnerabilities
- Hardhat is a popular development environment for Ethereum that provides a built-in testing framework
- Hardhat enables us to write and run automated tests for our smart contract, allowing us to catch any issues before deployment
- Additionally, Hardhat provides several features, including contract mocking, test snapshots, and coverage reports, making the testing process more efficient and effective.

# Testing the DApp

- After deploying the smart contract, it's important to test the DApp to ensure it interacts correctly with the contract
- We can test the DApp manually or using automated tests
- For our decentralized crowdfunding app, we used automated tests with Jest and React Testing Library to test the user interface and interactions with the smart contract
- Automated testing helps catch bugs and ensures the DApp functions correctly, providing a better user experience

# Hardhat Testing

- Our smart contract code is tested using Hardhat, a popular development environment for building and testing smart contracts
- Hardhat provides a robust set of tools and utilities for testing smart contracts and simulating real-world scenarios.

# Deployment of the Smart Contract

- Once the smart contract has been tested and verified, it's time to deploy it to the Ethereum network
- Deploying the smart contract involves sending it to the network and creating a new instance of the contract
- We can deploy our smart contract to different Ethereum networks, including the mainnet, testnets, and private networks
- For our decentralized crowdfunding app, we deployed our smart contract to the Goerli test network using ThirdWeb
- ThirdWeb is a user-friendly and secure platform for deploying and managing Ethereum smart contracts

# ThirdWeb Deployment

- Our crowdfunding app is deployed on ThirdWeb, a cloud-based Ethereum infrastructure service
- This allows us to easily deploy, test, and manage our smart contracts and web app.

# Evaluation

- Our decentralized crowdfunding app allows users to create and fund campaigns securely and transparently using blockchain technology
- The app has a user-friendly interface and provides clear instructions and feedback to users
- The smart contract code has been thoroughly tested and verified, ensuring it functions correctly and securely
- The app has been deployed to the Goerli test network, allowing users to test and use the app without

# Future Work

- We plan to continue improving our decentralized crowdfunding app by adding new features such as social sharing, improved user authentication, and enhanced data visualization
- We also plan to explore new blockchain technologies such as Polkadot and Solana to see how they can further enhance our app's performance and scalability.
