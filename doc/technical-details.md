Dicecoin [DICE] Technical Details
===================================

This document outlines the technical implementation details for Dicecoin. It should be of use to advanced users and developers.

Specifications
--------------

* 84 million coins in total
* 2 minute average block time
* 1000 coins per block
* Block reward halves every 12 months
* Retargets difficulty temporally using DigiShield
* x11 ASIC-resistant Proof-of-Work algorithm

Port numbers
------------

The following port numbers are used by Dicecoin.

* P2P uses port 7247 (17247 on Testnet)
* RPC uses port 7347 (17347 on Testnet)

Message start string
--------------------

The message start string used by Dicecoin is:

```
0xff, 0xc4, 0xba, 0xdf
```

The message start string for Testnet is:

```
0xff, 0xc4, 0xb9, 0xde
```
