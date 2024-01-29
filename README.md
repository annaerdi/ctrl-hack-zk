## Team Name
MisTTaken

## Team Members
- Anna E.: Technical Lead
- Fridolin D.: Product Owner


## Project Overview

**Title:** Project Bridgehead

**Description:**  
We introduce a secure, blockchain-based certification system for establishing communication bridges between users in close physical proximity. Our prototype uses a dynamic QR code exchange, like a digital handshake, to initiate smart contracts that validate user identity and permit communication.
Our vision for the telco industry is security by architecture. Due to our pessimistic defense approach blockchain and smart contracts are essential.

## Problem Statement
In the current telecommunication environment, the use of outdated public phone numbers and an optimistic security stance has led to increased vulnerabilities, particularly to spoofing and phishing attacks. Our solution aims to rectify these problems by introducing a new security paradigm. By verifying the proximity and authenticity of users, leaving systems vulnerable to remote attacks. We propose a solution that ensures user presence and consent through blockchain-certified exchanges.

![image](https://github.com/annaerdi/ctrl-hack-zk/assets/26500470/feaec1b8-0f7f-47e5-bb08-1549290cd021)

This is a real screenshot from my phone. Translated it reads: "Potential scam". This indicates an optimistic security approach which is the industry norm.
The phone number is well known since several years, it is a well known phishing number.

## Solution Approach

### Concept
Our approach leverages the blockchain to certify the identity verification process, enhancing security by requiring users to be in close physical proximity to "bridge" their contacts or DIDs. The QR code serves as a user-friendly mechanism to initiate smart contracts and is designed to change frequently to prevent misuse and enhance security.

### Key Features
1. **Blockchain for Certification:** Utilizing blockchain to record and certify the two users digital communication bridging. (main idea)
2. **Dynamic QR Code Exchange:** Providing a secure, frequently changing QR code that requires physical presence, preventing remote attacks. (planned for next iterations)
3. **Smart Contract Initiation:** The QR code acts as a trigger for the smart contract, ensuring a secure and automated certification process. (partial implementation as a MVP)
4. **Proximity Verification:** Leveraging technology similar to Bluetooth to confirm the physical proximity of the parties involved in the bridging process. (planned for next iterations)

### Technologies Used
- Blockchain for secure certification ledger
- Smart Contracts for automated identity verification
- Mobile Phones
- classical telco infrastructure

## Design thinking process:

1. **Week 1 Problemspace:**  Profound understanding of the biggest Challenges of a telco enterprise and Blockchains technologycals impact. 
2. **Week 2 Solutoinspace:**  Outline the requirements for proximity-based blockchain certification. Implementation of a basic (QR-) code based smart contract to bridge two DIDs with minimal frontend. 


## Impact Assessment

Our blockchain certification prototype will:
- Enhance security by ensuring physical proximity during user bridging.
- Reduce the risk of remote spoofing and phishing attacks.
- Offer a decentralized and transparent process for establishing secure communications.

## Limitations of the Prototype

- **User Behavior Change:** Requires users to adapt to new behaviors, such as scanning QR codes for each communication bridge.
- **Dynamic QR Code Management:** Frequent changes in QR codes can introduce complexity and require a robust back-end system.
- **Proximity Detection Reliability:** Ensuring the reliability of proximity detection in various environments and device conditions.
- **Blockchain Scalability:** Handling a high frequency of bridging requests on the blockchain without compromising performance.
- **Integration with Current Systems:** Compatibility with existing telecom infrastructure and user devices.
- **User Privacy Concerns:** Managing the balance between proximity verification and user privacy.

## Future Work and Development

- **Improving QR Code User Interface:** Creating a seamless experience for initiating the smart contract through QR codes.
- **Enhancing Proximity Detection:** Increasing the accuracy and reliability of the technology used for verifying physical proximity.
- **Scalability Solutions:** Researching blockchain scaling solutions to handle mass adoption without compromising speed or security.
- **Privacy-Preserving Techniques:** Developing methods to verify proximity while protecting user privacy.


## Conclusion

Project Bridgehead marks a pivotal step towards revolutionizing telecommunications security. By adopting a pessimistic security approach, we can greatly reduce vulnerabilities and set a new standard in telecom security.

