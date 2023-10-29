# Extraction, indexing and analysis of Ethereum smart contracts data

This repository contains the LaTeX source code of my Master's Thesis in Computer Engineering.

## Thesis Objectives

The target of this Master’s Thesis was to extract semantics from the Ethereum blockchain and index it through Dgraph, a distributed graph database.
Two research questions were defined:

- RQ1: What kind of information is it possible to extract from EVM blockchains without relying on centralized services?
- RQ2: What computational resources are required to independently extract and index the entire history of the Ethereum blockchain in August 2023?

This work was carried out in collaboration with the Norwegian University of Science and Technology. The index has been built on their servers to allow researchers to analyze data in a faster way.

## Contribution

This Master’s Thesis gave multiple contributions to the topic of Ethereum data mining:

- An analysis of state-of-the-art tools, both private and open-source.
- The definition of a data schema optimized for graph databases. This schema includes both raw Ethereum data and the semantics that can be built from it.
- The release of [eth2dgraph1](https://github.com/davideaimar/eth2dgraph), an open-source tool developed in Rust that maps Ethereum data to Dgraph format. It enables users to efficiently prepare data to be ingested into Dgraph.
- An analysis of the Ethereum data, both in terms of infrastructure and time needed to perform extraction and indexing and in terms of what semantics can be extracted.

