---
description: Functional requirements for the Scatter Peerplays plugin.
---

# Functional Requirements

## 1.0 Introduction

### 1.1 Objective

### 1.2 Scope

The scope is defined in the [project scope document](project-scope.md).

### 1.3 Assumptions and Constraints



This document will provide a tabular listing of the Peerplays Scatter Wallet Integration features. The target features for the Scatter Wallet Peerplays plugin will be based on this document. The features that Peerplays Scatter integration will provide is going to be a sub-set of the P[eerplays Wallet Features](https://app.gitbook.com/@peerplays/s/community-project-docs/peerplays-wallet/peerplays-wallet-feature-list).

## **2.0 High Level Requirements**

| Requirement | User Story |
| :--- | :--- |
| Connect to Peerplays blockchain | As a user I should be able to connect to the Peerplays main net. |
| Generate keypair | As a user I should be able to generate a Peerplays keypair. |
| Create Peerplays account | The user must be directed to a faucet to create the peerplays account |
| Import Key | A Given Peerplays private key should be imported by Scatter wallet |
| Support for PPY asset | As a user I should have PPY asset support within the Scatter wallet. |
| Retrieve PPY Balance | As a user I should be able to see my PPY balance within the Scatter wallet. |
| Send PPY | As a user I should be able to send PPY via the Scatter wallet. |
| Receive PPY | As a user I should be able to receive PPY via the Scatter wallet. |

## 3.0 Functional Requirements

This section will provide detailed description, mockups/wireframes/screenshots of requirements provided in section 2. The Quality assurance team will prepare the test plan based on this section.

### 3.1 Connect to Peerplays blockchain:

![The list of networks can be added and removed here.](../.gitbook/assets/image%20%288%29.png)

### 3.2 Generate Keypair

The generate keypair option will generate a Public-Private Key pair and display under a group. The keypair generation itself doesn't mean any linking with the Peerplays blockchain. Once the keypair is created, a faucet can be used to create a Peerplays blockchain account with a unique user name \(NAI\). The username will be subject to the Peerplays account creation [guidelines](https://github.com/peerplays-network/peerplays/wiki/Account-Names).

![Screen 1](../.gitbook/assets/image%20%283%29.png)

![Screen 2](../.gitbook/assets/image%20%2812%29.png)

### 3.3 Support for PPY Asset/Retrieve PPY Balance

![Note: Screenshot not yet available for PPY. This is the screenshot for BTC. ](../.gitbook/assets/image%20%282%29.png)

### 3.4 Send PPY

![Note: Screenshot not yet available for PPY. This is the screenshot for BTC. ](../.gitbook/assets/image%20%2811%29.png)

### 3.5 Receive PPY

![](../.gitbook/assets/image%20%286%29.png)

