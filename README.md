# Raktdhaara
Created a decentralized Blood Bank smart contract on Ethereum, enabling secure patient registration and transparent blood transactions.

 <!-- Optional: Add a badge/image showcasing the project or a logo -->

## Introduction

Raktdhaara is a decentralized application (DApp) developed on the Ethereum blockchain. It aims to create a secure and transparent blood bank system, facilitating efficient patient registration and tracking of blood transactions between donors and recipients.

## Features

- **Patient Registration**: Hospitals can register new patients on the blockchain, capturing their essential information such as name, age, blood group, contact details, home address, and Aadhar card number.
- **Blood Transactions**: The smart contract records blood transactions, including the timestamp, sender, and receiver addresses, enabling easy traceability of blood resources.
- **Efficient Data Retrieval**: Patient records are efficiently retrieved using a mapping that associates Aadhar card numbers with patient record indices, ensuring fast data access.
- **Access Control**: Access control mechanisms restrict critical functions to authorized hospitals (contract owner), ensuring data integrity and security.

## Technologies Used

- Solidity
- Ethereum Blockchain
- Remix IDE (for development and testing)
- Ganache (local development blockchain)

## Installation

1. Clone the repository: `https://github.com/Suryansh1208/Raktdhaara.git`
2. Change directory: `cd blood-bank`
3. Install dependencies: To install the Solidity compiler, you can use npm [Node Package Manager] (npm install -g solc)

## Usage

1. Deploy the smart contract to the Ethereum network using Remix IDE or any Ethereum-compatible wallet.
2. Hospitals (contract owner) can use their Ethereum address to register new patients and record blood transactions.
3. Patients can interact with the contract through a compatible wallet to access their information and transaction history.

## Contributing

Contributions to the Blood Bank Smart Contract project are welcome! If you would like to contribute, follow these steps:

1. Fork the project.
2. Create a new branch: `git checkout -b feature/new-feature`
3. Make your changes and commit them: `git commit -m "Add a new feature"`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or further discussions, feel free to contact me at [suryanshpandey1208@gmail.com] or connect with me on [LinkedIn](www.linkedin.com/in/suryansh-pandey).

