<!-- @format -->

# Milestone Delivery :mailbox:

**The [invoice form :pencil:](https://docs.google.com/forms/d/e/1FAIpQLSfmNYaoCgrxyhzgoKQ0ynQvnNRoTmgApz9NrMp-hd8mhIiO0A/viewform) has been filled out correctly for this milestone, and the delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/Grants-Program/blob/master/docs/milestone-deliverables-guidelines.md).**

- **Application Document:** https://github.com/w3f/Grants-Program/blob/master/applications/Afloat.md
- **Milestone Number:** 3

**Context** (optional)

This is the third milestone of Afloat's grant. It covers ordering fractional tax credits, confirming and settling the order.

A running instance of the code can be found [here](https://hashed-portal-dev.hashed.systems/login)

**Deliverables**

| Number | Deliverable            | Link                                                                                                                                                                                                                                                                                                                                                                                                                      | Notes                                                                                                               |
| -----: | ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
|    0a. | License                | https://github.com/hashed-io/hashed-substrate/blob/main/LICENSE                                                                                                                                                                                                                                                                                                                                                           | MIT                                                                                                                 |
|    0b. | Documentation          | https://github.com/hashed-io/hashed-marketplaces-ui <br> https://github.com/hashed-io/hashed-substrate <br>[Marketplace](https://github.com/hashed-io/hashed-substrate/tree/main/pallets/gated-marketplace)<br> [Fruniques](https://github.com/hashed-io/hashed-substrate/tree/main/pallets/fruniques)<br> https://github.com/hashed-io/hashed-private-server <br> https://github.com/hashed-io/hashed-private-client-api | The code has inline documentation and each repository has a detailed README with build, run, and test instructions. |
|    0c. | Testing                | [Github repository](https://github.com/hashed-io/hashed-substrate/blob/main/pallets/gated-marketplace/src/tests.rs)                                                                                                                                                                                                                                                                                                       | The test is built directly into the Rust project                                                                    |
|    0d. | Video                  | [English](https://drive.google.com/file/d/1YtlNNsmhpxzKgVTLbaMXC7unRzfVLNbE/view?usp=share_link) and [Spanish](https://drive.google.com/file/d/1D9LQ2KCDVWGbuTZ7_Oo-QYvOqNg9PUH3/view?usp=share_link) versions                                                                                                                                                                                                            | English and Spanish videos explaining the functionality on this Milestone, as well as some details on how to run it.                                                                                                                 |
|    0e. | Article                | [English](https://docs.google.com/document/d/1clgBMWQQXGqZd6p7P7CmZwEo0YaM5WRMZLISOn3FuNI/edit?usp=sharing) and [Spanish](https://docs.google.com/document/d/1AB-2sKU8GHO-yLZOQ-sn0MOlsCABPXG6gfRG61BtRXc/edit?usp=sharing) versions                                                                                                                                                                                      | English and Spanish articles explaining the math of the fractional NFTs and the business advatanges                                                                                                                 |
|     1. | Order Part of an NFT   | [Gated Markeplace business documentation.](https://github.com/hashed-io/hashed-substrate/blob/develop/docs/pallets-review/gated-marketplace.md#order-part-of-an-nft) The code can be found in the repositories on the last section.                                                                                                                                                                                                                                                                             |                                                                                                                     |
|     2. | Complete/Confirm Order | [Gated Markeplace business documentation.](https://github.com/hashed-io/hashed-substrate/blob/develop/docs/pallets-review/gated-marketplace.md#completeconfirm-order) The code can be found in the repositories on the last section.                                                                                                                                                                                                                                                                                  |                                                                                                                     |                                                                                                                     |
|     3. | Order Settlement       | [Gated Markeplace business documentation.](https://github.com/hashed-io/hashed-substrate/blob/develop/docs/pallets-review/gated-marketplace.md#order-settlement) The code can be found in the repositories on the last section.                                                                                                                                                                                                                                                                                  |                                                                                                                     |                                                                                                                     |

**Repositories**
(all MIT licensed)
| Component | Repo | Language |
| -----: | ----------- | ------- |
| Afloat Client API | https://github.com/hashed-io/afloat-client-api | Javascript |
| Marketplace UI | https://github.com/hashed-io/hashed-network-portal-ui | Quasar/Vue |
| Marketplace pallet | https://github.com/hashed-io/hashed-substrate/tree/develop/pallets/gated-marketplace | Rust |
| Fruniques pallet | https://github.com/hashed-io/hashed-substrate/tree/develop/pallets/fruniques | Rust |
| Confidential Documents Server | https://github.com/hashed-io/hashed-private-server | Javascript |
| Confidential Documents API | https://github.com/hashed-io/hashed-confidential-docs-client-api | Javascript |
| Faucet Server | https://github.com/hashed-io/faucet-server | Javascript |