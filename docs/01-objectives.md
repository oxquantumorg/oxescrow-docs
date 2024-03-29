### Goals, Objectives, and User Interactions:

#### Goals:
- **Creation of a Secure and Efficient Payment Processor:** Develop a payment processor that facilitates escrow transactions between users within the LittleBiggy platform.
- **Integration of LittleBiggy API:** Utilize Chainlink or the Solana SDK to create oracles that retrieve specific data from the LittleBiggy API.
- **Smart Contract Development:** Design and implement a smart contract on the Solana blockchain that handles payments based on the retrieved data from the oracles.
- **Enhanced User Experience:** Provide a seamless user interface for users to interact with the payment processor, manage transactions, and view payment details.
- **Subgraph:** Create a subgraph to index all events from the smart contract, making it easier to query data and historic transactions.

#### Objectives:
- **Oracle Creation:** Develop an oracle – to fetch and provide LittleBiggy API data and to automatically trigger release of assets from every transactions/invoice at the provided release date on the smart contract.
- **Smart Contract Implementation:** Write a Solidity smart contract that receives instructions from the oracle and executes tasks like releasing assets to the transaction/invoice addresses and processing payments accordingly.
- **Integration and Testing:** Integrate the oracle with the smart contract and conduct thorough testing to ensure accurate data retrieval and payment execution.

#### User Interactions:
- **Buyers:** Users initiating transactions/invoice on LittleBiggy.
- **Sellers:** Individuals selling goods/services on LittleBiggy.
- **Payment Processor Interface:** User-friendly interface allowing buyers to make payments and sellers to receive them, displaying transaction details and invoice generation.

[GO HOME](/readme.md)