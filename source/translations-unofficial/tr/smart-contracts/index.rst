.. Concordium smart contracts documentation master file, created by
   sphinx-quickstart on Thu Oct 22 15:01:04 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=======================================
Concordium Smart Contract Documentation
=======================================

Welcome to the documentation of Concordium smart contracts!

The documentation is split into four categories

   - **General**: Explaining concepts and details for understanding Concordium
     Smart Contracts.
   - **Tutorials**: Step by step walk-through with details explained as needed.
   - **How-to guides**: Short guides to achieve specific goals.
   - **References**: Precise descriptions of the machinery.

.. todo::

   A list of information, still missing from the documentation

   **Guides**

   - Queries
   - Contract best practices (ensure amount is 0, naming conventions)

   **Tutorial**

   - Finish first contract

.. toctree::
   :maxdepth: 1
   :caption: General

   general/introduction
   general/contract-module
   general/contract-instances
   general/contract-schema
   general/resource-accounting
   general/develop-contracts

.. toctree::
   :maxdepth: 1
   :caption: Tutorials

   tutorials/piggy-bank/index

.. toctree::
   :maxdepth: 1
   :caption: Contract development guides

   guides/setup-tools
   guides/setup-contract
   guides/compile-module
   guides/unit-test-contract
   guides/local-simulate
   guides/build-schema
   guides/no-std

.. toctree::
   :maxdepth: 1
   :caption: On-chain guides

   guides/deploy-moduletr
   guides/initialize-contract
   guides/interact-instance
   guides/inspect-instance

.. toctree::
   :maxdepth: 1
   :caption: References

   references/schema-json
   references/simulate-context
   references/host-fns
   references/references-on-chain
   references/local-settings
   Rust contract examples (repo) <https://github.com/Concordium/concordium-rust-smart-contracts>
   concordium-std <https://docs.rs/concordium-std/latest/concordium_std/>

.. todo::

   Update user documentation link
