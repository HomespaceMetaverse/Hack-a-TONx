# Homespace Network: Epine SDK by Homespace for TON-Enabled Applications with TonConnect Authentication
## Overview

We are creating a network of 3D cinematic spaces to be used as a new generation of websites as well as a service for private virtual reality meetings. We use a streaming system and develop a decentralized browser with web3 tools, an asset store (modules, levels, nft) and a constructor of Metaspaces for users.  

For the purpose of the hackathon as a part of our system we created an opensource SDK module - Epine SDK by Homespace. 

The Epine SDK by Homespace is an open-source set of powerful tools for developers to create TON blockchain-enabled applications with TonConnect authentication methods. With Epine SDK, developers can connect Ton wallets via TonConnect, verify wallets, and retrieve balances. The SDK's components include an Unreal Engine Plugin, a C++ Library, and a Server. As part of our project, Epine serves to log in with TON and add the TON wallet to the wallets used for transactions within Homespace. 

## What was built during the hackathon?
During the hackathon, we extended our existing SDK solution to support the TON blockchain. We added Ton Connect authentication method, which enables us and in the future other developers to authenticate users using Ton Connect wallets. We also added support for retrieving balances of TON wallets, which provides developers with an easy way to retrieve and display wallet balances in their applications. With these new features, our SDK solution is now even more powerful and versatile, allowing developers to build TON blockchain-enabled applications with ease. As a web3 decentralized project, we decided to make the Epine SDK opensource. 

## Unreal Engine Plugin
[Source code](https://github.com/EpineCloud/EpinePlugin-Unreal)

The Unreal Engine Plugin is a wrapper around the C++ library and allows developers to connect Ton wallets to their Unreal Engine applications. It simplifies the integration process and enables developers to focus on their business logic. In this case, the showcase for using the SDK is our project. 

## C++ Library
[Source code](https://github.com/EpineCloud/epine-sdk-cpp)

The C++ Library connects to the server via Socket.io and HTTP. It provides developers with an easy-to-use interface for interacting with the TON blockchain and Ton wallets using TonConnect authentication.

## Server
[Source code](https://github.com/EpineCloud/epine-server-public)

The Server is a backend that implements the logic for TON blockchain and wallet interactions with TonConnect authentication. It enables developers to interact with TON blockchains in a hassle-free manner and focuses on their business logic instead of complex blockchain connections.

The Epine SDK by Homespacee is constantly evolving, and we are always working on adding new functionalities to it. With this SDK, we aim to make TON blockchain-enabled application development simpler, faster, and more efficient.

## Homespace Build with SDK 
[Source code](https://github.com/EpineCloud/epine-server-public)
This is the offline version of our build (the version with the server will be available for the MVP launch). You can try an example of how the Epine SDK works as follows:
1. Run the build on Windows. 
2. After loading and opening the first space press tab (open menu).
3. In the upper right corner, click on the profile icon. The profile menu will open. At the bottom of the accounts panel, click on "[ + ] ADD SERVICE" button, then select TON and scan QR with TonKeeper in the window that pops up. 
4. After login, the profile menu will show the TonKeeper wallet and the balance of the wallet.
ATTENTION! THIS IS A UNTESTED VERSION TO PRESENT AN EXAMPLE OF SDK WORKING IN OUR PROJECT. WE ASK THE JURY TO EVALUATE THE CODE FIRST. 

