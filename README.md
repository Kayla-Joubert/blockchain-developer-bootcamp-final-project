(Final Project: Consensys Blockchain Developer Bootcamp)

# Really Really Free Market (Idea One)

## Overview

The Really Really Free Market (RRFM) is distributed network of peers which allows for the trustless gifting of material goods.

## Mechanism

-   Peer A lists an item in the marketplace
-   Peer B requests ownership of the item
    -   The item is taken out of the marketplace until Peer A responds to the request.
-   Peer A accepts or rejects the request
    -   If the request is accepted:
        -   A verification process is triggered on the network
        -   Once the request is verified the state of ownership of the item is transfered to Peer B
        -   A (hypothetical) self driving vehicle or drone is then triggered by a smart contract to deliver the item to the new owner.
        -   Confirmation of delivery by Peer B ends the transferal process (and potentially rewards Peer A with a token?).
    -   If the request is rejected:
        -   The item is placed back into the marketplace

## Tokens

Tokens ensure that the marketplace is not misused.

-   On joining the marketplace the user recieves x amount of tokens
-   When a peer recieves an item from the marketplace x amount of tokens are deducted from their account
-   When a peer lists and succesfully gifts an item to another peer x amount of tokens are deposited in their account
-   If a user has 0 tokens they cannot request an item from the marketplace.

### Notes on Concept

-   The concept is based on the real world "Really Really Free Market" which allows for the gifting of goods and services.
    Further Reading:
    [Really Really Free Market - Wikipedia] (https://en.wikipedia.org/wiki/Really_Really_Free_Market)

## Running the app

---

## Fallback Ideas

-   Seed Exchange
