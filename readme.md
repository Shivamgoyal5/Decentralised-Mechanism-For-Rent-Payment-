### README.md

# RentPay Smart Contract
![alt text](<Screenshot 2024-08-25 122209.png>)
## Vision
The **RentPay** smart contract aims to revolutionize the rental payment system by providing a transparent, decentralized, and automated way to manage tenant payments and track their contractual obligations. This system is designed to handle payments efficiently, maintain a clear record of each tenant's payment history, and ensure fair treatment through an appeal mechanism for late payments. The contract also offers a way to categorize tenants into legal and illegal lists based on their payment behavior, with provisions for appeals and owner interventions.

## Project Features
- **Owner-Only Access**: Only the contract owner (deployer) can perform specific actions like adding tenants, recording payments, and reviewing appeals.
- **Tenant Management**: The contract allows the owner to add tenants with specific contract dates and update these dates as needed.
- **Payment Recording**: Payments made by tenants can be recorded, specifying the amount, payment date, whether it was on time, and if it was within a grace period.
- **Legal and Illegal Lists**: Tenants are automatically managed into legal and illegal lists based on their payment history, particularly late payments.
- **Appeal Mechanism**: Tenants who find themselves on the illegal list can submit appeals, which the owner can review and act upon.
- **Transparent Record-Keeping**: Tenants can view their details and entire payment history, promoting transparency.
- **Event Logging**: Key actions such as adding tenants, recording payments, submitting appeals, and updating lists trigger events for easy tracking.

## Future Scope
- **Automated Payment Processing**: Integrating with payment gateways to allow automatic payment logging and on-chain rent payments.
- **Multi-Signature Ownership**: Expanding the owner role to a multi-signature wallet for more decentralized governance.
- **Penalty System**: Implementing an automated penalty system for late payments that could deduct penalties directly from the payer's deposit.
- **Integration with Decentralized Identity (DID)**: Allowing tenants to use decentralized identities for seamless verification and history tracking across multiple rental contracts.
- **Enhanced Appeal Process**: Developing a more sophisticated appeal system where a committee of addresses (oracles) can vote on the outcome.
- **Scalability and Interoperability**: Adapting the contract for use on different blockchains and integrating it with existing property management systems.

## Project Structure
```
RentPay/
├── contracts/
│   └── RentPay.sol         # The smart contract file written in Solidity.
├── migrations/
│   └── 1_initial_migration.js   # Migration script for deployment.
├── test/
│   └── RentPay.test.js     # Test scripts for contract functions (if any).
├── README.md               # Project documentation.
└── package.json            # Node.js project file (if applicable).
```

### Contracts
- **RentPay.sol**: The core smart contract file that includes all the logic for managing tenants, payments, and appeals.

### Migrations
- **1_initial_migration.js**: Script to handle the deployment of the RentPay contract onto the blockchain.

### Test
- **RentPay.test.js**: JavaScript-based test scripts to ensure the smart contract functions as expected. (You can add test cases here).

## Developer Details
- **Developer**: [Shivam Goyal]


## Deployment 
Chain Nmae: Educhain Open Campus 
Contract Id: 0xc59a8c320a56839b265fa1c2f1988e5a046acfd4
![alt text](<Screenshot 2024-08-25 132801.png>)



