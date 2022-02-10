# **Bridge Indexer (Non-public)**

Bridge Indexer is an events listener for Borealis NATS Bus, which listening for NEAR's on-chain events (block releasing) with filtering Rainbow Bridge related transactions.

Provides publishing (as producer) of messages, which contains Rainbow Bridge related transactions, to the Borealis NATS Bus.

## **Build and run Bridge Indexer using make.sh shell helper and Cargo:**
```
bash ./make.sh [ help/h/? | fmt | check | build | build release | submodules | submodules update ]
```

```
bash ./make.sh fmt

bash ./make.sh check

bash ./make.sh submodules update

bash ./make.sh submodules

bash ./make.sh build release

bash ./make.sh build
```
