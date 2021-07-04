# Ethereum 2.0 Validator Node Resources

## Overview

1. Install Ubuntu server
    * Configure SSH
    * Harden system
2. Install GETH (optional if using 3rd party node via API)
    * Installing GETH locally at least 100GB of available SSD space
    * Instead you can use Infura or Alchemy to pull in this information from their API
3. Install Bazel
    * This is necessary to build Prysm. If you are using a different validator client then this is not necessary. FF is using and is most familiar with Prysm.
4. Install Prysm (or other validator client)
    * Other clients include Teku, Nimbus, Lodestar, and Lighthouse
5. Configure the Beacon Chain
6. Onboard to the network
    * Get 32 Goerli (testnet) ETH
    * Generate validator keys
    * Visit pyrmont.launchpad.ethereum.org and follow steps to deposit ETH
7. Create Validator wallet
8. Configure the Validator
    * Create/configure services
9. Install monitoring/alert toolkits
    * These tools are to help you manage the server instance and associated ETH software
    * Prometheus
    * Node Exporter
    * Grafana

## Setup

* [ETH2 Pyrmont Testnet Launchpad](https://pyrmont.launchpad.ethereum.org/en/)
* [Guide to Staking on Ethereum 2.0 (Ubuntu/Pyrmont/Prysm)](https://someresat.medium.com/guide-to-staking-on-ethereum-2-0-ubuntu-pyrmont-prysm-a10b5129c7e3)
* [Prysm ETH2 Docs](https://docs.prylabs.network/docs/getting-started)
* [A comprehensive look at hardware for staking](https://www.reddit.com/r/ethstaker/comments/ggmbvd/a_comprehensive_look_at_hardware_for_staking/)
* [Setup an Eth2 Mainnet Validator System on Ubuntu](https://github.com/metanull-operator/eth2-ubuntu)

## APIs

* [Beaconcha.in - Open Source Ethereum 2.0 Beacon Chain Explorer](https://beaconcha.in/)
* [Infura - Ethereum APIs](https://infura.io/)
* [Alchemy](https://www.alchemy.com/enhanced-apis)

## ETHStaker Community

* [Reddit](https://www.reddit.com/r/ethstaker)
* [Homepage](https://ethstaker.cc/)
* [Discord](http://invite.gg/ethstaker)
* [Twitch](https://www.twitch.tv/ethstaker/)

## Learning

* [Ethereum Study Master](https://ethereumstudymaster.com/)

## Ubuntu Setup

* [Initial Server Setup with Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-20-04)
* [How to Set Up SSH Keys on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-ubuntu-20-04)

## Tools

* [Proof of attendance protocol (POAP)](https://app.poap.xyz/)
* [Staking Calculator](https://beaconcha.in/calculator)
* [Beacon Chain Knowledge Base](https://kb.beaconcha.in/)

## Articles

* [Validated, staking on eth2: #6 - Perfect is the enemy of the good](https://blog.ethereum.org/2020/12/10/validated-perfect-is-the-enemy-of-the-good/)
* [ETH2.0: Everything You Need to Know](https://medium.com/mycrypto/eth2-0-everything-you-need-to-know-eb32fbfe0bd)