# 🌐 Nexus
Nexus is an open source protocol for AI-to-AI communication. The increasing complexity and interconnectivity of AI systems highlights the need for a standardized framework for AI-to-AI communication. Nexus AI provides such a framework, defining a set of rules and procedures that AI systems must follow when communicating with each other. This ensures that AI systems can exchange information in a secure, reliable, and efficient manner, regardless of their specific implementation details.

## Purpose of Nexus
The purpose of Nexus is to provide a standardized framework for AI-to-AI communication. The protocol defines a set of rules and procedures that AI systems must follow when communicating with each other. By adhering to these rules, AI systems can exchange information in a way that is secure, reliable, and efficient.

## Key Features of Nexus
- **Message format:** Nexus defines a standard message format that AI systems must use when communicating with each other. The format includes fields for the sender and receiver of the message, the type of message being sent, and the data being transmitted.

- **Security:** Nexus includes measures to ensure the security of AI-to-AI communication. This includes authentication of senders and receivers, encryption of messages, and protection against attacks such as tampering or eavesdropping.

- **Reliability:** Nexus includes mechanisms to ensure the reliability of AI-to-AI communication. This includes error detection and correction, message acknowledgements, and retransmission of lost or corrupted messages.

- **Scalability:** Nexus is designed to be scalable, allowing AI systems to communicate with each other regardless of their size or complexity. This includes support for multicast and broadcast communication, as well as mechanisms for load balancing and resource allocation.

## Benefits of Nexus
- **Interoperability:** By adhering to a standardized protocol like Nexus, AI systems can communicate with each other more easily, regardless of the specific implementation details of each system.

- **Efficiency:** Nexus is designed to be efficient, minimizing the amount of bandwidth and processing power required for AI-to-AI communication.

- **Security:** Nexus includes measures to ensure the security of AI-to-AI communication, protecting against attacks and unauthorized access to data.

- **Reliability:** Nexus includes mechanisms to ensure reliable communication, minimizing the risk of lost or corrupted data.

- **Costs Saving** Nexus includes mechanisms to ensure cuts savings trough only-llm-when-needed communications

## RFC

Sage Tech Labs Inc.
Request for Comments: 0001
Category: Experimental
Title: NEXUS: A Bot-to-Bot Communication Protocol Minimizing the Use of Large Language Models
Date: April 04 2023

1. Introduction

NEXUS is an experimental communication protocol designed for bot-to-bot communication while minimizing the dependency on large language models (LLMs) whenever possible. It incorporates message validation, caching mechanisms, and OpenAPI-based communication to reduce the need for intensive LLM usage.

2. Terminology

- LLM: Large Language Model
- Assistant: A bot based on an LLM
- Agent: A specialized module initiated by an Assistant to handle a specific request
- OpenAPI: A specification for building APIs

3. Protocol Overview

3.1. Message Validation and Authentication
- Assistants and Agents use a predefined validation schema and authentication system to ensure secure and compliant communication.

3.2. OpenAPI Implementation
- Assistants and Agents communicate using RESTful APIs based on the OpenAPI specification to ensure interoperability and easy integration.

3.3. Caching System
- Assistants cache OpenAPI definitions of the services and agents they interact with, and implement intelligent cache updating algorithms to maintain relevant information.

3.4. Direct Service Communication
- If an Agent already knows a request, it can handle it directly using the required service's API without communicating with another Assistant, improving efficiency.

3.5. Learning and Adaptation Mechanisms
- Assistants and Agents employ supervised or unsupervised machine learning techniques to adapt to new or unknown situations.

3.6. Modular and Scalable Architecture
- NEXUS has a modular and scalable architecture to accommodate different environments and workload requirements.

4. Protocol Specification

4.1. Message Structure
- Messages include metadata for validation and authentication purposes.

4.2. OpenAPI Communication
- Assistants and Agents exchange information using OpenAPI-based communication, allowing for a standardized and open approach to sharing data.

4.3. Caching and Cache Updates
- Assistants maintain a local or cached repository of OpenAPI definitions and update it based on intelligent cache updating algorithms.

4.4. Direct Service Interaction
- If an Agent can handle a request directly, it will use the Service B's API to obtain the necessary information without communicating with Assistant B.

5. Security Considerations

- Authentication and message validation mechanisms must be in place to ensure secure communication between Assistants and Agents.

6. IANA Considerations

- This document has no actions for IANA.

7. Acknowledgements

- The author would like to thank the user for their insights and suggestions in the development of the NEXUS protocol.

8. References

- Fielding, R., "Architectural Styles and the Design of Network-based Software Architectures", 2000.
- OpenAPI Initiative, "OpenAPI Specification", https://www.openapis.org/.
