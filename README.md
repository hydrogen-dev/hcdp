# Welcome to the Hydro Community Development Program!

#### Overview

The HCDP is a **core program** to Project Hydro. It is a collection of paid developer bounties **run by the Hydro Community** to advance the ecosystem or its products. Any community member can post and create a task for others to fulfill. These tasks could be for an SDK or library, dApps (Solidity), tutorials, enhancements and more. Tasks get assigned a bounty total and are paid upon fulfilling the requirements.

#### Participation & Process

Anyone can participate. Tasks get posted by the community and other community developers apply by filling out a form and commenting on the Github task. We review all applicants and their qualifications. An assignment is made with another Hydro Labs DA and project work begins. Milestones are set and checkins take place. Once a deliverable has been made, it is reviewed by the team or a 3rd party audit is preformed. There may be edits needed to code based on feedback. Once a code review is complete, code is buttoned up with a descriptive readme file and looks great, payment is made to the developer. [Read more here](https://github.com/HydroBlockchain/hcdp/blob/master/Hydro%20HCDP%20Task%20Approval%20Process).

To view a list of open tasks that can be applied for, visit our [active HCDP bounties page](https://github.com/HydroBlockchain/hcdp/issues).


# List of Completed Hydro Tasks:

The following is a list of tasks **successfully completed** as part of the HCDP by our growing developer community to advance the Hydro ecosystem. Developers can utilize these plugins, smart contracts and code in their development to jump start their project or leverage advanced functionality without re-inventing the wheel.


## Hydro Smart Contracts:

* **[Hydro Marketplace Coupons](https://github.com/Luiserebii/HydroSnowflake-Marketplace-Coupons):** This project is essentially a chain of Ethereum smart contracts built on top of the Hydro Snowflake protocol, aiming to provide a marketplace platform for sellers to launch their own stores and sell to users. Coupons are also featured, allowing users to use globally defined coupons guaranteed to expire within a certain time period, or assigning coupons per Snowflake EIN, manageable via multiple addresses. The marketplace itself is a Snowflake Resolver contract, which interacts with a Snowflake Via contract to handle the transaction (and thus coupon discount) logic.

  * **Task Reference:** [Issue #255](https://github.com/HydroBlockchain/hcdp/issues/255)
  *  **Developer Bounty:** 3,000,000 Hydro ([txn](https://etherscan.io/tx/0x519737ef1da37040e591853177307187ab215d3d151f11ff41241a5a562082da))
  * **Author:** [@Luiserebii](https://github.com/Luiserebii)
  * **Deliverable:** [Solidity Smart Contract](https://github.com/Luiserebii/HydroSnowflake-Marketplace-Coupons)
  

* **[Hydro Lottery](https://github.com/merlox/hydro-lottery):** An Ethereum smart contract uses Hydro Snowflake Ids (EINs) for creating unique lotteries with rewards setup in HYDRO tokens instead of ETH. It's made of an HydroEscrow contract that holds HYDRO for each unique lottery, a Randomizer contract that generates random numbers with Oracles for creating unique, secure randomized numbers for selecting winners and a HydroLottery contract that takes care of the main logic.

  * **Task Reference:** [Issue #256](https://github.com/HydroBlockchain/hcdp/issues/256)
  *  **Developer Bounty:** 4,000,000 Hydro ([txn](https://etherscan.io/tx/0x518aba6e649395707bc62290cc01bf94dcfd7a694d57b0501c943486b9f0254e))
  * **Author:** [@merlox](https://github.com/merlox)
  * **Deliverable:** [Solidity Smart Contract](https://github.com/merlox/hydro-lottery)
  
* **[Hydro Interest](https://github.com/ricktobacco/hydro-glacier):** An Ethereum smart contract on top of Hydro Snowflake that allows a certain percentage of interest on a defined principal amount, in HYDRO, to accrue and be charged (or paid) to a wallet tied to a SnowflakeID, and then for that balance to automatically be withdrawn (or paid). The smart contract will guarantee that the money is in the account by enforcing an escrow of the accruing payment within the wallet, thus eliminating payment default, or fraud from institutions. This utility smart contract will power charging interest in many future savings, lending, credit, and mortgage Hydro dApps. There will be Layer-3 dApps and Layer-4 APIs that hook into this utility smart contract function.

  * **Task Reference:** [Issue #264](https://github.com/HydroBlockchain/hcdp/issues/264)
  *  **Developer Bounty:** 4,000,000 Hydro ([txn](https://etherscan.io/tx/0x729dad0bc8b02b0eade7c1dfbb50dfbeae1e5a15efe34e4c18460511e4cd830c))
  * **Author:** [@ricktobacco](https://github.com/ricktobacco)
  * **Deliverable:** [Solidity Smart Contract](https://github.com/ricktobacco/hydro-glacier)

* **[Hydro Product Orders](https://github.com/merlox/ethereum-store):** An Ethereum smart contract on top of Hydro Snowflake that allows you to publish products, purchase them with HYDRO and dispute orders in case there's any problem. Remember to install all the dependencies with npm i before running the tests or using the contracts. All the contract code is stored inside the contracts folder.

  * **Task Reference:** [Issue #256](https://github.com/hydrogen-dev/hcdp/issues/256)
  * **Developer Bounty:** 4,000,000 Hydro ([txn](https://etherscan.io/tx/0x004492c489d34d08863eea4c38399b2c8ea5f56a9619283512d75b1f2a1ec20e))
  * **Author:** [@merlox](https://github.com/merlox)
  * **Deliverable:** [Smart Contract](https://github.com/merlox/ethereum-store)

* **[Hydro Gift Cards](https://github.com/kdmukai/hydro-gift-card):** An Ethereum smart contract on top of Hydro Snowflake that allows a certain percentage of interest on a defined principal amount, in HYDRO, to accrue and be charged (or paid) to a wallet tied to a SnowflakeID, and then for that balance to automatically be withdrawn (or paid). The smart contract will guarantee that the money is in the account by enforcing an escrow of the accruing payment within the wallet, thus eliminating payment default, or fraud from institutions. This utility smart contract will power charging interest in many future savings, lending, credit, and mortgage Hydro dApps. There will be Layer-3 dApps and Layer-4 APIs that hook into this utility smart contract function.

  * **Task Reference:** [Issue #253](https://github.com/HydroBlockchain/hcdp/issues/253)
  *  **Developer Bounty:** 4,000,000 Hydro ([txn](https://etherscan.io/tx/0x0369acb8927b311a64a4c0f59d57f8f48e2f8c7b7003eccc8c26ce659e50aafc))
  * **Author:** [@kdmukai](https://github.com/kdmukai)
  * **Deliverable:** [Solidity Smart Contract](https://github.com/kdmukai/hydro-gift-card)

* **[Hydro Invoicing](https://github.com/clemlak/SnowflakeInvoicing):** An Ethereum smart contract on top of Hydro Snowflake that allows a business to invoice another business or consumer for a specific amount, on a specified date, and in a certain amount of Hydro. This Ethereum smart contract is built on top of Hydro Snowflake.
  * **Task Reference:** [Issue #254](https://github.com/hydrogen-dev/hcdp/issues/254)
  * **Developer Bounty:** 3,000,000 Hydro ([txn](https://etherscan.io/tx/0xdcf425dcd9dbb34f62fc33ce99c5cd96b2ee0adc1e08f95167df0ef18486e74f))
  * **Author:** [@clemlak](https://github.com/clemlak)
  * **Deliverable:** [Solidity Smart Contract](https://github.com/clemlak/SnowflakeInvoicing)
  
  
 * **[Hydro Finance](https://github.com/merlox/hydro-finance):** An Ethereum smart contract on top of Hydro Snowflake that stores your credit cards, bank and investment accounts in one solidity contract named HydroFinance.sol using encryption to secure data on the blockchain. It receives the credit card data, encrypts it using your unique EIN identifier and stores that information into your user account. You can then generate the encryption result off-chain using web3.utils.soliditySha3() and your required parameters, to generate the hash that you can use to verify your account. This is the only method to securely protect data on the open blockchain since we can't store sensitive information without encryptions.
  * **Task Reference:** [Issue #257](https://github.com/hydrogen-dev/hcdp/issues/257)
  * **Developer Bounty:** 3,000,000 Hydro ([txn](https://etherscan.io/tx/0xfee2a17e2c67f9a32baa4bf4e86e690d4b0f8089a4114ce59d9d64723d26eec9))
  * **Author:** [@merlox](https://github.com/merlox)
  * **Deliverable:** [Solidity Smart Contract](https://github.com/merlox/hydro-finance)


## 3rd Party Hydro Plugins:


* **[Raindrop Client - Wordpress Plugin](https://wordpress.org/plugins/wp-hydro-raindrop/):** Hydro Multi Factor Authentication Plugin (MFA) for Wordpress adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #202](https://github.com/hydrogen-dev/hcdp/issues/202), [Issue #223](https://github.com/hydrogen-dev/hcdp/issues/223), and [Issue #230](https://github.com/hydrogen-dev/hcdp/issues/230)
  * **Developer Bounty:** 500,000 Hydro ([txn](https://etherscan.io/tx/0x642f95b71390eec2d78770efebd93f7b7bbfd3e13e5fd0ae233fb9e70f1633f8), [txn](https://etherscan.io/tx/0xe9014233fc58c530e735bb25fd4a7f7e080ba7817362935b21e38444905f1e75), [txn](https://etherscan.io/tx/0x10cd4cbac8157cbd11b9aa1cd1b6297dfa4c3d03212c3734a38288aa444985b0))
  * **Author:** [@adrenth](https://github.com/adrenth)
  * **Deliverable:** [Wordpress Plugin](https://wordpress.org/plugins/wp-hydro-raindrop/)
 
* **[Raindrop Client - Joomla Plugin](https://github.com/DaveM2011/joomla-hydro-raindrop):** Hydro Multi Factor Authentication Plugin (MFA) for Joomla adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #219](https://github.com/hydrogen-dev/hcdp/issues/219)
  * **Developer Bounty:** 700,000 Hydro ([txn](https://etherscan.io/tx/0x164eb52a1640c14c1a55e8b8088bc5bd9a16ec06959d10f991f6b5a70767f68a), [txn]([https://etherscan.io/tx/0x9833516cc9df90a5378ea44bc78858d4a1224e5191693d060b98a04af382f2c8](https://etherscan.io/tx/0x9833516cc9df90a5378ea44bc78858d4a1224e5191693d060b98a04af382f2c8)))
  * **Author:** [@DaveM2011](https://github.com/DaveM2011), [@realquink](https://github.com/realquink), [@mitdralla](https://github.com/mitdralla)
  * **Deliverable:** [Joomla Plugin](https://github.com/DaveM2011/joomla-hydro-raindrop)

* **[Raindrop Client - Laravel Plugin](https://github.com/HydroBlockchain/laravel-hydro-raindrop-demo):** Hydro Multi Factor Authentication Plugin (MFA) for Laravel adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #272](https://github.com/hydrogen-dev/hcdp/issues/272)
  * **Developer Bounty:** 2,000,000 Hydro ([txn](https://etherscan.io/tx/0xd9c069eff117707498cd0960bec6e103b4ccbb3434a6bf203bda6bc429f2b6c1))
  * **Author:** [@adrenth](https://github.com/adrenth), [@realquink](https://github.com/realquink), [@mitdralla](https://github.com/mitdralla)
  * **Deliverable:** [Laravel Plugin](https://github.com/HydroBlockchain/laravel-hydro-raindrop-demo)

* **[Raindrop Client - SalesForce Plugin](https://github.com/brett91ag/salesforce-hydro-raindrop):** Hydro Multi Factor Authentication Plugin (MFA) for OctoberCMS adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #220](https://github.com/HydroBlockchain/hcdp/issues/220)
  * **Developer Bounty:** 800,000 Hydro
  * **Author:** [@brett91ag](https://github.com/brett91ag)
  * **Deliverable:** [SalesForce Plugin](https://github.com/brett91ag/salesforce-hydro-raindrop)

* **[Raindrop Client - Drupal Plugin](https://github.com/proofoftom/drupal-hydro-raindrop):** Hydro Multi Factor Authentication Plugin (MFA) for OctoberCMS adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #217](https://github.com/HydroBlockchain/hcdp/issues/217)
  * **Developer Bounty:** 800,000 Hydro ([txn](https://etherscan.io/tx/0x7534fc14f6e742ceaeab3b28d723d8c72b8c61fb0d0e45b99940e4b6556ff741))
  * **Author:** [@proofoftom](https://github.com/proofoftom)
  * **Deliverable:** [Drupal Plugin](https://github.com/proofoftom/drupal-hydro-raindrop)

* **[Raindrop Client - OctoberCMS Plugin](https://github.com/HydroBlockchain/oc-hydroraindrop-plugin):** Hydro Multi Factor Authentication Plugin (MFA) for OctoberCMS adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #254](https://github.com/HydroBlockchain/hcdp/issues/258)
  * **Developer Bounty:** 800,000 Hydro ([txn](https://etherscan.io/tx/0x5c0f49d59d7fa5ae11503796039f481c2c40003e598d16e937b4ce3f90a44d28))
  * **Author:** [@crypt0h3nk](https://github.com/crypt0h3nk)
  * **Deliverable:** [OctoberCMS Plugin](https://github.com/HydroBlockchain/oc-hydroraindrop-plugin)

* **[Raindrop Client - Passport.js Module](https://github.com/Red-Maximus/passport-raindrop):** Hydro Multi Factor Authentication Plugin (MFA) for Passport.js adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #211](https://github.com/hydrogen-dev/hcdp/issues/211)
  * **Developer Bounty:** 500,000 Hydro ([txn](https://etherscan.io/tx/0x39dcb4b78e9cbf2967d53fbbf7e26db5dcefbbd6ef44215dd5cd25009c4b7dcf), [txn](https://etherscan.io/tx/0xad11932a322c152f7d4f78d0cd2eda019be24157b77d6fa469a195570683b033))
  * **Author:** [@Red-Maximus](https://github.com/Red-Maximus) 
  * **Deliverable:** [Passport.js Module](https://github.com/Red-Maximus/passport-raindrop)

 


## Hydro SDKs:

* **[Hydro Raindrop SDK for PHP](https://github.com/adrenth/raindrop-sdk):** This PHP library provides a suite of convenience functions intended to simplify the integration of Hydro's [Raindrop authentication](https://www.hydrogenplatform.com/hydro) into your project. More information, including detailed API documentation, is available in the [Raindrop documentation](https://www.hydrogenplatform.com/docs/hydro/v1/#Raindrop).

  * **Task Reference:** [Issue #208](https://github.com/HydroBlockchain/hcdp/issues/208)
  *  **Developer Bounty:** 200,000 Hydro ([txn](https://etherscan.io/tx/0xd49252811742613ccc2222595b2b3a813bc3d4e181409210004f2f09084528b5))
  * **Author:** [@adrenth](https://github.com/adrenth)
  * **Deliverable:** [SDK](https://github.com/adrenth/raindrop-sdk)


* **[Hydro Raindrop SDK for Java](https://github.com/serkanalgl/hydro-raindrop-java):** This Java library provides a suite of convenience functions intended to simplify the integration of Hydro's Raindrop authentication into your project. More information, including detailed API documentation, is available in the [Raindrop documentation](https://www.hydrogenplatform.com/docs/hydro/v1/#Raindrop).

  * **Task Reference:** [Issue #209](https://github.com/HydroBlockchain/hcdp/issues/209)
  *  **Developer Bounty:** 200,000 Hydro ([txn](https://etherscan.io/tx/0x2e69a09b8336da41a1745e84e077f68e5226a8b4749e5298cef182ecdb3517af))
  * **Author:** [@serkanalgl](https://github.com/serkanalgl)
  * **Deliverable:** [SDK](https://github.com/serkanalgl/hydro-raindrop-java)
  
* **[Hydro Raindrop SDK for ColdFusion](https://github.com/brett91ag/coldfusion-hydro-raindrop):** This ColdFusion library provides a suite of convenience functions intended to simplify the integration of Hydro's Raindrop authentication into your project. More information, including detailed API documentation, is available in the [Raindrop documentation](https://www.hydrogenplatform.com/docs/hydro/v1/#Raindrop).

  * **Task Reference:** [Issue #212](https://github.com/HydroBlockchain/hcdp/issues/212)
  *  **Developer Bounty:** 25,000 Hydro ([txn](https://etherscan.io/tx/0xffbe769a502b677b42c1d2483507ed9647843ca05a6dcfb1fd836f3320ee6916))
  * **Author:** [@brett91ag](https://github.com/brett91ag)
  * **Deliverable:** [SDK](https://github.com/brett91ag/coldfusion-hydro-raindrop)

## Hydro Code Audits:

* **[Decentralized Ambassador Smart Contract](https://github.com/HydroBlockchain/hcdp/issues/218):** The Decentralized Ambassador (DA) Program is an initiative to more heavily involve the Hydro community in the ongoing decentralization and global expansion of the Hydro blockchain ecosystem. This task is to evaluate the current master state of the Solidity code in the [DA Program smart contract](https://github.com/hydrogen-dev/smart-contracts/blob/master/decentralization-ambassadors/DA.sol), in order to identify any areas of potential improvement.

  * **Task Reference:** [Issue #218](https://github.com/HydroBlockchain/hcdp/issues/218)
  *  **Developer Bounty:** 450,000 Hydro ([txn](https://etherscan.io/tx/0x64703612480f77fd1d4a524226638e9f6ae2f81dc0152ad6f5658555a2317da1), [txn](https://etherscan.io/tx/0xa638103c1254667417d16bea8eb1442498028003e9f5e4564156a5e222bd09f9))
  * **Author:** [@clemlak](https://github.com/brett91ag), [@samglos](https://github.com/samgos)
  * **Deliverable:** [Smart Contract Audit](https://github.com/HydroBlockchain/smart-contracts/blob/master/decentralization-ambassadors/DA.sol)


## Misc Development:

* **[Hydro Raindrop Wordpress Testing](https://github.com/HydroBlockchain/hcdp/issues/236):** Testing and quality evaluation of the Hydro Raindrop Wordpress Plugin code, functionality and front end UI. 
  * **Task Reference:** [Issue #236](https://github.com/HydroBlockchain/hcdp/issues/236)
  * **Developer Bounty:** 200,000 Hydro ([txn](https://etherscan.io/tx/0xc292c3ab327fa303453b7dfc7ae246d0de1529344d80644e9ecf4aecb15b7017), [txn](https://etherscan.io/tx/0xb72e5b379f8c81914f7fcc56c38d15a3db79a61dfb44508b03874ba069177501), [txn](https://etherscan.io/tx/0xbceffe3a0ddb2f41b2134b2c47bf4d881dc492f5689bcc755e81eaeb97c3b86f))
  * **Author:** [@adrenth](https://github.com/adrenth), [@realquink](https://github.com/realquink), [@Riskex1](https://github.com/Riskex1)
  * **Deliverable:** [Testing](https://github.com/HydroBlockchain/hcdp/issues/236)


* **[Snowflake Identicon Generator -  Library](https://github.com/HydroBlockchain/hcdp/issues/218):** The Decentralized Ambassador (DA) Program is an initiative to more heavily involve the Hydro community in the ongoing decentralization and global expansion of the Hydro blockchain ecosystem. This task is to evaluate the current master state of the Solidity code in the [DA Program smart contract](https://github.com/hydrogen-dev/smart-contracts/blob/master/decentralization-ambassadors/DA.sol), in order to identify any areas of potential improvement.

  * **Task Reference:** [Issue #221](https://github.com/HydroBlockchain/hcdp/issues/221)
  *  **Developer Bounty:** 600,000 Hydro ([txn](https://etherscan.io/tx/0x64703612480f77fd1d4a524226638e9f6ae2f81dc0152ad6f5658555a2317da1), [txn](https://etherscan.io/tx/0xa638103c1254667417d16bea8eb1442498028003e9f5e4564156a5e222bd09f9))
  * **Author:** [@cyphercodes96](https://github.com/cyphercodes96), [@Amirh24](https://github.com/Amirh24)
  * **Deliverable:** [Smart Contract Audit](https://github.com/HydroBlockchain/smart-contracts/blob/master/decentralization-ambassadors/DA.sol)

* **[Snowflake Identicon Generator -  Design](https://github.com/HydroBlockchain/hcdp/issues/226):** The Decentralized Ambassador (DA) Program is an initiative to more heavily involve the Hydro community in the ongoing decentralization and global expansion of the Hydro blockchain ecosystem. This task is to evaluate the current master state of the Solidity code in the [DA Program smart contract](https://github.com/hydrogen-dev/smart-contracts/blob/master/decentralization-ambassadors/DA.sol), in order to identify any areas of potential improvement.

  * **Task Reference:** [Issue #226](https://github.com/HydroBlockchain/hcdp/issues/226)
  *  **Developer Bounty:** 600,000 Hydro ([txn](https://etherscan.io/tx/0xf341ebef90e1c36f66e878405ec55a7aebfb1466ab5566b6d081a32c8ae7a645))
  * **Author:** [@puppetbrain](https://github.com/puppetbrain)
  * **Deliverable:** [Snowflake Design Assets](https://github.com/HydroBlockchain/hcdp/issues/226)
