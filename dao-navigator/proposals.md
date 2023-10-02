# Proposals

There are several standard proposals types included in all siloDAOs that simplify treasury management operations. Custom proposals can be built upon request by SiloDAO, and since Silo is open source anyone can build additional solutions on top of Silo.

### Basic

**Signal Request:** create on-chain member vote to collect signal on various decisions within the DAO.

**ERC-20 Token Transfer:** a simple transfer of any ERC-20 from the main treasury to any address on the same network.

**Network Token Transfer:** a simple transfer of a network's native token (i.e. ETH) from the main treasury to any address on the same network.

### Advanced

**Use WalletConnect:** easily interact with any smart contract or application using the main treasury as the executing address. i.e. connect to Uniswap and swap some tokens within the main treasury.

**Update Governance Settings:** create a proposal to change any of the DAO's governance settings found in the 'Settings' tab.

**Add Shaman:** grant DAO permissions to an external contract. _<mark style="color:red;">WARNING! - This is for advanced users only and should be used with extreme caution.</mark>_

**Multicall Proposal Builder:** a transaction builder to create a multicall proposal. This is for advanced users that want to bundle multiple transactions into a single proposal. i.e. approve a contract to spend multiple tokens in the treasury, add liquidity, and stake the LP.
