# Internet Computer Token Standard

This standard tries to introduce a common interface which could be used by community tokens that will
be lunched on Dfinity's Internet Computer.

The candid interfaces are included in the `candid` directory, the basic functionality of the
tokens which are mandatory to implement by all the implementations are put inside the `token.did`
file, other features are put in the `extensions` directory.

1. BURNABLE: The token can be burned and destroyed, reducing the supply.
2. DEX: To make the token automatically convertible to Cycles, so the captured fees can
help pay for the canister costs.
3. HISTORY: To make the transaction log visible and scalable by using archive canisters.
