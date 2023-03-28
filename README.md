TeleradiologyAI CT Scans NFT Contract
This is a smart contract for creating CT Scans non-fungible tokens (NFTs) on the Ethereum blockchain, using Remix.

The contract is named CTScans and extends the ERC721 contract from the OpenZeppelin library, which means it is a non-fungible token contract and allows us to create and manage unique tokens that represent CT Scans.

Installation and Usage
To use this contract, you can copy the code into Remix and deploy it to the Ethereum blockchain.

Once the contract is deployed, you can call the createScan function to create a new scan. This function takes in the scanID, scanType, and scanData as parameters and returns the tokenId of the newly created scan.

You can then call the getScan function to retrieve the details of a particular scan, given its tokenId.

Contract Details
The Scan struct defines the properties of a CT Scan, including the scanID, scanType, scanData, timestamp, and owner. The _scans mapping stores the scans, and the _scanCount variable keeps track of the number of scans created.

The createScan function is used to create a new scan. It takes in the scanID, scanType, and scanData as parameters, and returns the tokenId of the newly created scan.

The getScan function is used to retrieve the details of a particular scan, given its tokenId.

License
This project is licensed under the MIT License - see the LICENSE file for details.
