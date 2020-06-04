# Geoblockchain Project

Edited by: Jou Ho

## Project Description

![](img/vulnertable_people.png)

### Purpose

The motivation behind this project is to support vulnerable populations around the world. Vulnerable populations include, but not limited to, economically disadvantaged, racial and ethnic minorities, the uninsured, low-income children, the elderly, the homeless, those with human immunodeficiency virus (HIV), and those with other chronic health conditions, including severe mental illness. It may also include rural residents, who often encounter barriers to accessing healthcare services. The vulnerability of these individuals is enhanced by race, ethnicity, age, sex, and factors such as income, insurance coverage (or lack thereof), and absence of a usual source of care. Their health and healthcare problems intersect with social factors, including housing, poverty, inadequate education, and geographical factors, such as access to locations and environmental factors. This project is dedicated to these populations and aims to provide a brand new method to address the vulnerability of such groups.

### Authors

The initial idea and design of this project is created by Bo Zhao, a geography professor at the University of Washington and the Pincipal Investigator at Humanistic GIS Laboratory. The initial development of the application is developed by Jou Ho, an undergraduate student at the University of Washington and a member of HGIS Lab. For more information about us and the HGIS Lab, visit our website at <https://hgis.uw.edu/>

### Goals

The goal of this project is to create a decentralized application (referred to as DApp) as opposed to typical applications where the backend code is running on centralized servers. This application allows users to donate cryptocurrency to any geographic regions that exist on the earth. This web-based platform will enable us to achieve the following primary goals:

-   Visualize vulnerable population through the levels of donation different geographical region receives. This visualization is open for anyone to see, allowing other people to utilize for reference or any related studies.
-   Provide a brand-new way to donate currency to vulnerable populations using blockchain  technology (explained in later sections), which allows us to create a donation application with the three critical following features, which introduces a more reliable and secured system architecture for donation purposes;
    1.  **Immutability**: no one can alter the stored data nor change the program code for this application for malicious purposes.
    2.  **Transparency**: every stored data, program code, and data processes are accessible for users to see, though immutable.
    3.  **Traceability**: users can keep track of any transactions (explained later) made through the application.
-   Ultimately, support the aforementioned vulnerable populations/geographies through the established donation platform.

### What is Blockchain and DApp

#### Blockchain

![](img/blockchain.png)

A blockchain is a growing list of records, known as blocks, that are connected using cryptography. Every block contains a cryptanalytic hash of the previous block, a timestamp, and transaction information.

By design, a blockchain is a proof against modification of the information. It is an open, distributed ledger that will record transactions between 2 parties with efficiency and during a verifiable and permanent manner. To be used as a distributed ledger, a blockchain is often managed by a peer-to-peer network put together adhering to a protocol for inter-node communication and confirming new blocks. Once recorded, the information in any given block cannot be altered retroactively without the alteration of all subsequent blocks, which needs a consensus of the network majority. Though blockchain records are not unalterable, blockchains are also thought of as secure by design and exemplify a distributed computing system with high Byzantine fault tolerance. A decentralized agreement has therefore been claimed with a blockchain.

Blockchain was invented by someone (or cluster of people) using the name Satoshi Nakamoto in 2008 to serve as the public transaction ledger of the cryptocurrency bitcoin. The identity of Satoshi Nakamoto is unknown. The invention of the blockchain for bitcoin created the primary digital currency to unravel the double-spending downside without requiring a proper authority or central server. The bitcoin design has inspired different applications, and cryptocurrencies widely use blockchains that are transparent by the general public. Blockchain is taken into account a sort of payment rail. Non-public blockchains are proposed for business use.

#### Decentralized Application (DApp)

![](img/DApp.png)

DApp is an abbreviated form of decentralized application.
A DApp has its backend code running on a decentralized peer-to-peer network. Contrast this with an app where the backend code is running on centralized servers.

A DApp can have frontend code and user interfaces written in any language (just like an app) that can make calls to its backend. Furthermore, its frontend can be hosted on decentralized storage such as Swarm or IPFS.

In this project, Ethereum network is used to create a DApp. Ethereum is one of the popular programmable blockchain in the world. Like other blockchains, Ethereum has a native cryptocurrency called Ether (ETH), but unlike other blockchains, Ethereum can do much more since Ethereum is programmable. This means that developers can use it to build new kinds of applications, notably DApp.

If an app = frontend + server, since Ethereum contracts are code that runs on the global Ethereum decentralized peer-to-peer network, then:

DApp = frontend + contracts

### Strengths and Weaknesses of Blockchain-based DApp

#### Strengths

The main advantages of using decentralized applications:

-   Payment processing does not require a third-party financial operator. In a decentralized network, transactions between users are performed directly and in cryptocurrency.
-   There is no need for registration or subscription due to the use of public and private keys for accessing data.
-   Open source and public registry make sure the platform is transparent and easy to use.

These criteria are all beneficial in the development of a donation application.

#### Weaknesses

The main disadvantages of using decentralized applications:

-   Fixing bugs or updating DApps is difficult, as every peer in the network has to update their node software.
-   Some applications require verification of user identity, and as there is no central authority to verify the user identity, it becomes an issue while developing such applications.
-   They are challenging to build because they use very complex protocols to achieve consensus, and they have to be built to scale from the start itself. So we cannot just implement an idea and then, later on, add more features and scale it.

These weaknesses are something that is yet to be solved for this project. We will need further ideas and development of our DApp in the future.

### Major Functions

The followings are the main functionalities of this DApp, although these are subject to change and new functions may be added in the course of development.

-   A web map that allows users to navigate through different geographical regions.
-   A search bar which users can type in the address, place, or country to find their location of interests.
-   Users can post or create new call for donation by filling a registration form.
-   Visualization of posted donations by markers on the map. The amount of donation could also be visualized by different levels of color.
-   Pop up windows that shows up upon clicking on the markers. This window contains information about the donation post such as: the name of organization/individuals/population groups, description of the donation post (why do they need donation? who will be supported by the donation?), and the total amount of donation they already received, etc.
-   Users can donate their crypto currency to a location by clicking on the "donate" button on pop up window for each donation post. They can decide how much cryptocurrency (Ether) to donate.
-   A person who created the donation post can retrieve donated money to their cryptocurrency wallet (metamask)

Above are the main functions of this DApp. However, there are, and will be, functions and details that will be needed in the future development of this application. This includes:

-   professional website design
-   professional data visualizations
-   functionalities that attracts large enough number of users
-   security measures against malicious use of this applications
-   improving overall user experience (UX) and user interface (UI)

### System Architechture

### Challenges and Concerns
