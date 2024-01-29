# Building-with-Polygon-Bridge
Based on the project rubric you provided, here's an outline of the tasks you need to complete:

1. **Generate a 5-item collection using DALLE 2 or Midjourney**:
   - Use DALLE 2 or Midjourney to generate a collection of 5 items.

2. **Store items on IPFS using pinata.cloud**:
   - Upload the generated items to IPFS using pinata.cloud or any other IPFS pinning service.

3. **Deploy an ERC721 or ERC1155 to the Goerli Ethereum Testnet**:
   - Develop a smart contract (ERC721 or ERC1155) to represent your NFT collection.
   - Deploy the smart contract to the Goerli Ethereum Testnet using Hardhat or Truffle.

4. **Implement the promptDescription function**:
   - Add a function to your smart contract that returns the prompt used to generate the images.

5. **Map Your NFT Collection using Polygon network token mapper**:
   - Use the Polygon network token mapper to associate your NFT collection with the Polygon network. This step helps in visualizing the NFTs on the Polygon network.

6. **Write a Hardhat script to batch mint all NFTs**:
   - Develop a Hardhat script that allows for the batch minting of all NFTs in your collection. Since you're dealing with ERC721 tokens, consider using ERC721Enumerable for efficient batch minting.

7. **Write a Hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge**:
   - Develop a Hardhat script that facilitates the batch transfer of all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge. This script should handle the approval, deposit, and transfer of NFTs.

8. **Approve the NFTs to be transferred**:
   - Before transferring the NFTs to Polygon Mumbai, ensure that they are approved for transfer according to the requirements of your smart contract.

9. **Deposit the NFTs to the Bridge**:
   - Initiate the deposit process for transferring the NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge.

10. **Test balanceOf on Mumbai**:
    - After transferring the NFTs to Polygon Mumbai, write tests (using Hardhat tests or other testing frameworks) to ensure that the balanceOf function accurately reflects the ownership of NFTs on the Mumbai network.

