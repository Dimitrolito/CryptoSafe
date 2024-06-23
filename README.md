# CryptoSafe
Secure storage and management of your cryptocurrencies

Explanation of the Code:

1. Contract Structure: "CryptoSafe" is a basic contract for managing cryptocurrency transactions.

2. State Variables:

   - balances: Stores balances of user addresses.
   -allowed: Stores allowed amounts of tokens that can be transferred on behalf of other addresses.

3. Events:

   - Transfer: Fired when tokens are successfully transferred between addresses.
   - Approval: Fired when permission to transfer tokens on behalf of another address is set or modified.

4. Functions:

 - balanceOf: Returns the balance of the specified address.
 - transfer: Transfers tokens from the sender's address to another specified address.
 - transferFrom: Transfers tokens from a specified sender to another specified address, considering prior approval.
 - approve: Sets the permission for a specified address to transfer tokens on behalf of the caller.
 - allowance: Returns the current allowed amount of tokens for specified addresses.
