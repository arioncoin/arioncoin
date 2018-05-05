Arion Core
=============

04/30/18

v1.1.2 - UI Overhaul

Significant UI updates across almost all aspects of the wallet.
New logo and type integrated
Artwork behind logo swaps to a random variation each time the wallet is launched


Mandatory update v1.1.0 available

PLEASE update prior to block 29,000. 

Local wallets AND masternode vps's must be updated.

The Arion wallet has been updated to version 1.1.0 and includes a change to the proof-of-work/masternode ratio starting at block 29,000.

https://our-arion.com

Arion digital currency is a highly secure and flexible method of payment that furthers the economic strength of the community itself. With no connection to the manipulation and corruption of the global banking and financial cartels, Arion provides a way for believers to store value, exchange value, transact, and spread the word to the masses. 

Arion has three core goals:

• To provide secure blockchain technology leveraged by believers

• To create a built-in market for tract and gift sales, which gives believes a platform for spreading their message while increasing value to the currency

• To serve as a convenient method of payment among believers, which increases the community grant fund for outreach and missionary programs


Current wallets
---------------
Linux -

https://github.com/ArionCore/Arion/releases/download/v1.1.2.1/arioncore-1.1.2-linux32.tar.gz

https://github.com/ArionCore/Arion/releases/download/v1.1.2.1/arioncore-1.1.2-linux64.tar.gz

Windows -

https://github.com/ArionCore/Arion/releases/download/v1.1.2.1/arioncore-1.1.2-win32.zip

https://github.com/ArionCore/Arion/releases/download/v1.1.2.1/arioncore-1.1.2-win64.zip

Mac -

https://github.com/ArionCore/Arion/releases/download/v1.1.2.1/arioncore-1.1.2-osx.dmg

https://github.com/ArionCore/Arion/releases/download/v1.1.2.1/arioncore-1.1.2-osx64.tar.gz


Masternodes
-----------
Arion implements masternodes that provide serveral important functions to the network. For the network services they provide, a random Masternode on the network is selected for each block and awarded ~80% of the block subsidy.

Masternodes MUST be run on a separate server with a hot/cold wallet setup. Most users will opt to use a VPS service with an Ubuntu 16.04 server such as Amazon EC2, Google Cloud Compute, or Vultr. Masternodes can not be operated from a local wallet as it is unsecure and a liability to have an unlocked and unecrypted local wallet...therfore, this functionality is blocked at a source code level.

Masternodes also require sentinel ( https://github.com/ArionCore/sentinel ).

We have two comprehensive masternode guides available now that can be used for the setup and configuration of Arion masternodes using a Linux VPS to host the node (currently a requirement).

The first guide goes through a hot/cold wallet setup using Vultr as a VPS service (they've been a decent choice with Linux VPS's available for $2.50/month). This guide also has a Troubleshooting section that is continually being added to:

https://docs.google.com/document/d/1kz6OuR1ybR_ZpvKEvJQybUdn_jVZVfviks7h-77_1Gs/edit?usp=sharing

The second guide is from Discord community member @birty#9460 (thanks birty!) and is focused on a setup with Time4VPS (another popular VPS option):

https://docs.google.com/document/d/1CWUjlrmvpbceB7_Mu-mEhqg67nKYT7hvvF9gNTu4qMA/edit?usp=sharing


Fundamentals
------------

Symbol: RAP

Type: PoW + Masternodes - Neoscrypt (ASIC Resistant, GPU friendly, DgW v3 retargeting)

Features: Masternodes with high rewards, InstantSend, PrivateSend, Fast block times

Coin supply: Approx 21 Million

Premine: Approx 3%*

Total Block Reward: 14 Arion (11.023 MN + 2.977 PoW),  reducing by 7% annually

Masternode Reward: ~80% of block (+ Lucky PoW) after block 29,000, 50% prior to block 29,000

PoW Reward: ~20% of block (+ Lucky PoW) after block 29,000, 50% prior to block 29,000

Block Time Average: 120 seconds

Masternode Collateral: 1000 Arion

Governance: Budgets and Superblocks initiating after approx 1 year (block 262,800)

* Arion premine to be used for Airdrops, Bounties, and development of Arion Gift Cards system


Links
-------

Discord - https://discord.gg/NMgQEn8

Twitter - https://twitter.com/RAP_Project  https://twitter.com/our_arion

Instagram - https://www.instagram.com/our_arion/

About - http://our-arion.com/what-makes-us-different/

FAQ - http://our-arion.com/faq/

Spread the word - http://our-arion.com/spread-the-word/


License
-------

Arion Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.


Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/ArionCore/Arion/tags) are created to indicate new official,
stable release versions of Arion Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).
