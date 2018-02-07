MystCoin [MST] Technical Details
===================================

This document outlines the technical implementation details for MystCoin. It should be of use to advanced users and developers.

Specifications
--------------

* 42 million coins in total
* 2 minute average block time
* 100 coins per block
* Block reward halves 
* Retargets difficulty using DarkGravityWave
* x11 ASIC-resistant Proof-of-Work algorithm

Port numbers
------------

The following port numbers are used by MystCoin.

* P2P uses port 17118
* RPC uses port 17117 

Message start string
--------------------

The message start string used by MystCoin is:

```
0xfe, 0xc2, 0xb3, 0xee
```
