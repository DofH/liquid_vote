Liquid Vote
===========

Electronic vote collecting software. Each voter has an account and they may vote directly on a bill or they may delegate a representative. For more information [try this video](https://www.youtube.com/watch?v=fg0_Vhldz-8).

Identity Verification
---------------------

To ensure one account per voter and no more:

1. The voter creates an accont online
2. The voter enters their election commission registered address
3. That name and address are checked against the voter registration roles
4. If a match is found a secret code is sent to the voter via post
5. The voter enters the code and verifies their identity

Data
----

The information will more than likely come from [the Sunlight Foundation's Congress API](http://sunlightlabs.github.io/congress/). I'm interested in allowing vote delegation based on the originating committee.

Secrecy
-------

A secret ballot is crucial to protecting the integrity of the vote. This means delegates don't know who they are voting for.

This also means someone won't know how their delegate cast their vote. So they ultimately don't know how they voted.

