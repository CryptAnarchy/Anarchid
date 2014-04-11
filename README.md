Anarchid - an anarcho manifested cryptocoin, 'faster' version of Litecoin which also uses scrypt
as a proof of work scheme and is intended for microtransactions.
 - 15 seconds block targets
 - 67 108 864 total coins
 - no subsidy within the first 3 days and after approximately 5 years;
    in between: 4 coins per generated block
 - difficulty retargets every 0.35 days
 - currently peers are looked up over IRC only
 - currently no block checkpoints are in the code (but could be easily
   added)
 - Rpcport: 56679
 - P2P port: 9030
Other than that, this coin is exactly like Litecoin and SMC. All of the coin parameters
are chosen arbitrarily or at most with 'fairness' towards everyone in mind.

So actually, this 'new' coin exists for the following reasons:
 - Anarchid proves that really anyone(!) can start a Litecoin/Bitcoin based currency
    (just look at the changes I applied to the original Litecoin source,
     for genesis block generation look at main.cpp)

Credits go to the original authors/communities that
created Bitcoin, Litecoin and SMC.
