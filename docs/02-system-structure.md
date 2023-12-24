## System Architecture

#### High-Level Architectural Diagram
![System Architecture Diagram](link_to_your_diagram_image)

#### Backend, Frontend, and Database Requirements
- **Frontend (ReactJS):**
  - Responsible for the user interface.
  - Utilizes ReactJS to create an interactive and user-friendly interface for buyers, sellers, and the payment processor.
  
- **Backend (Smart Contracts on Solana using Rust):**
  - Implements the business logic and executes transactions.
  - Utilizes Rust to write smart contracts on the Solana blockchain, handling payments, invoice generation, and interactions with stable coins.
  
- **Database (Subgraph Assembly Language):**
  - Indexes and retrieves data efficiently from the blockchain.
  - Utilizes Subgraph to index blockchain data, providing a queryable interface for fetching relevant information.

#### Technology Stack
- **Languages and Frameworks:**
  - **Frontend:** ReactJS for building the user interface.
  - **Backend (Smart Contracts):** Rust for developing smart contracts on the Solana blockchain.
  - **Database:** Subgraph for indexing blockchain data.
  - **Oracle (NodeJS):** NodeJS for the LittleBiggy api to interact, initiate release and provide data to the smart contracts.

### Summary
The architecture consists of a ReactJS frontend for user interaction, Rust-based smart contracts on the Solana blockchain for executing payment transactions, Subgraph for efficient data indexing, and NodeJS for the oracle handling interactions with the LittleBiggy API. This combination of technologies aims to provide a robust and scalable system for the LittleBiggy payment processor, ensuring a seamless user experience and reliable transaction processing.
