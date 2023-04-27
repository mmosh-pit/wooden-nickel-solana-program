# Wooden Nickle Program

This program runs the logic to Mint and Trade the Wooden Nickle SFT.

The Wooden Nickel is a semi-fungible token that serves as a token “Gate,” meaning it is required for certain functions and it carries the lineage of the minter.

Specifically, the Wooden Nickel can only be minted by the holder of a Fake ID. A Wooden Nickel is also required to mint a Fake ID in the game.
A Fake ID can still be minted off the personal brood link.

### Core logic is located in the `solana_anchor/src/lib.rs` file

  It contains functions to create and configure the SFT Pool, and to mint the SFT, adding the corresponding lineage and metadata to that SFT in a PDA

#### There are utility functions in `solana_anchor/src/utils.rs` file
