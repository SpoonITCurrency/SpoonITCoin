SpoonITCoin / based on Litecoin
================================

http://www.spoonit.co.nz

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Litecoin Developers
Copyright (c) 2015 ---- SpoonITnz Developers

What is SpoonITCoin?
----------------

SpoonITCoin aims to be a faster and more secure version of Litecoin.

Original decription from the Litecoin team:

Litecoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 - ~84 million total coins

The rest is the same as Bitcoin.
 - 50 coins per block
 - 2016 blocks to retarget difficulty

For more information regarding this SpoonITCoin build visit http://www.spoonit.co.nz

License
-------

SpoonITCoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their butts off for a great cup of coffee and when they have time they work on this.



Testing
-------

*** Will be starting soon.


### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./litecoin-qt_test

