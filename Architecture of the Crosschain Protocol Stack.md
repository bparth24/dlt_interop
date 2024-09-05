---

## 2. Architecture of the Crosschain Protocol Stack

The architecture of the crosschain interoperability stack provides a standardized framework to enable secure and seamless communication across diverse blockchain and/or DLT networks. It consists of a modular, plug-and-play architecture spanning three layers

1. **Crosschain Applications Layer**
2. **Crosschain Function Calls Layer**
3. **Crosschain Messaging Layer**

This layered architecture allows for the integration of components from different vendors, serving as a robust infrastructure for an array of crosschain applications.

```markdown
Architecture of the Crosschain Protocol Stack
=========================

+-----------------------------------------+
|                                         |
|        Crosschain Applications Layer    |
|                                         |
|     Business Logic & Use Case-Specific  |
|              Functionality              |
+-----------------------------------------+
                 ↑
                 |
                 ↓
+-----------------------------------------+
|                                         |
|      Crosschain Function Calls Layer    |
|                                         |
|      Execution of Operations Across     |
|              Multiple Networks          |
+-----------------------------------------+
                 ↑
                 |
                 ↓
+-----------------------------------------+
|                                         |
|        Crosschain Messaging Layer       |
|                                         |
|    Secure Exchange of Data & Events     |
|         Between Blockchain Networks     |
+-----------------------------------------+
```
This diagram provides a high-level overview of how the different layers interact and stack up to create a cohesive crosschain interoperability solution.


### **Crosschain Applications Layer: The Business Logic Hub**
- **Overview:** This layer contains the business logic and use case-specific functionality for enterprise applications.
- **Purpose:** Consider this the "brain" of the stack, where complex operations and decision-making processes are defined. It’s where enterprises implement the specific logic that drives their crosschain activities.
- **Role in the Stack:** It manages and controls how operations are carried out across networks, ensuring that all activities follow the intended business rules.

### **Crosschain Function Calls Layer: The Operational Core**
- **Overview:** This layer enables the execution of operations across networks, allowing crosschain applications to trigger and coordinate activities on multiple blockchains.
- **Purpose:** Imagine this layer as the "remote control" for blockchain networks. It allows applications to perform actions on one network that depend on the state or outcome on another, ensuring that all networks involved are synchronized.
- **Role in the Stack:** It orchestrates the execution of smart contract functions across networks, ensuring that transactions align with the business logic defined in the Applications layer.

### **Crosschain Messaging Layer: The Communication Backbone**
- **Overview:** This layer facilitates the secure exchange of data and events between networks, ensuring the integrity and validity of information passing between them.
- **Purpose:** Think of this layer as the "postal service" of the stack—it securely delivers messages between different networks, ensuring that events triggered on one blockchain can be verified and trusted on another. This is foundational for maintaining the decentralized, trustless nature of DLTs.
- **Role in the Stack:** It’s the backbone of communication, enabling verification and validation of cross-network events without needing a central authority.

---

# Integration and Benefits

When combined, these three layers create a protocol stack that is both robust and versatile, capable of meeting the complex demands of modern enterprises. By adhering to the Enterprise Ethereum Alliance's (EEA) Distributed Ledger Technology Interoperability Specification, this stack ensures that all components are interoperable, scalable, and secure.

## **Focus on EVM Compatibility**

- The current specification primarily targets Ethereum Virtual Machine (EVM)-compatible blockchains due to their widespread adoption. However, it’s designed to be adaptable, supporting other architectures like Zero-Knowledge Proof (ZKP) compatible networks and R3 Corda. This adaptability ensures that the stack remains future-proof, accommodating an evolving digital ecosystem.

---

## **Next Steps: Understanding the Crosschain Messaging Layer**

With the overall architecture and goals established, the next section delves into the foundational layer: the Crosschain Messaging Layer. This layer is crucial for enabling secure and verifiable communication between different blockchain networks. We’ll cover the specific protocols, message formats, and verification methods that make trusted interoperation across diverse DLTs possible.

---
