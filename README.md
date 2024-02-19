
# Solana Wallet Application

This is a simple React application that interacts with the Solana blockchain. The application allows users to perform the following actions:

1. **Create a New Solana Account:**
   - Clicking the "Create a new Solana account" button generates a new Keypair and airdrops 2 SOL into it.

2. **Connect to Phantom Wallet:**
   - Clicking the "Connect to Phantom Wallet" button attempts to connect to the Phantom Wallet. If successful, it retrieves the public key of the connected wallet.

3. **Transfer SOL to New Wallet:**
   - Clicking the "Transfer SOL to New Wallet" button creates a transaction to transfer 1 SOL from the sender wallet to the connected wallet.

## Getting Started

To run this application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/jerydam/Solana-Assessment.git
   ```

2. Install dependencies:

   ```bash
   cd solana-wallet-app
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`.

## Requirements

- Node.js (https://nodejs.org/)
- NPM (Node Package Manager, comes with Node.js)

## Dependencies

- @solana/web3.js
- React
- ...

## Configuration

Ensure that your Solana network is set up, and the Phantom Wallet extension is installed in your browser.

## Usage

1. Click "Create a new Solana account" to generate a new Keypair and airdrop SOL.
2. Click "Connect to Phantom Wallet" to connect to the Phantom Wallet.
3. Click "Transfer SOL to New Wallet" to initiate a transfer from the sender wallet to the connected wallet.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Solana Documentation
- Phantom Wallet

Feel free to customize the README to suit your project's specifics and include any additional information that might be helpful for users and contributors.