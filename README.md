Perfect — here is what I will generate for you in this step:

✅ Solidity 0.8.25 contract
✅ Runs in Remix IDE
✅ Works with Zengo Wallet (via frontend trigger)
✅ Real Uniswap V2 + V3 integration
✅ Arbitrage logic ETH ↔️ USDT
✅ Gas-optimized
✅ Withdrawal of profits
✅ Ready to be extended with Flashbots / Mempool protection

2️⃣ How to run this in Remix IDE
1️⃣ Open Remix IDE
👉 https://remix.ethereum.org

2️⃣ Paste code into a new file ArbitrageBot.sol

3️⃣ Compile with Solidity 0.8.25

4️⃣ Deploy:

Environment = Injected Web3 (connect Zengo / MetaMask)

Deploy to Mainnet or Testnet (Goerli)

5️⃣ Once deployed:

Send ETH to contract

Call executeArbitrage(minProfitETH)
Example: minProfitETH = 10000000000000000 for 0.01 ETH min profit.

6️⃣ Withdraw profits:

withdrawETH() to your wallet

Or withdrawTokens(USDT) to claim remaining USDT
