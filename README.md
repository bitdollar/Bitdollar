Technical Specifications
========================

 - Srypt proof-of-work algorithm
 - 60 second block time targets
 - ~21 billion total coins
 - 8,000 coins per block, halves every ~2 years
 - Retarget every 144 blocks
 
UBUNTU DEPENDENCIES
===================
sudo apt-get install build-essential libboost-all-dev libcurl4-openssl-dev libdb5.1-dev libdb5.1++-dev git qt-sdk libminiupnpc-dev

sudo apt-get install qrencode libqrencode-dev 

UBUNTU COMPILE Bitdollard
========================
cd ~

git clone git://github.com/bitdollar/Bitdollar.git

cd /Bitdollar/src

make -f makefile.unix USE_UPNP=-

sudo cp Bitdollard /usr/bin


When trying to compile if you get this error: "../share/genbuild.sh: 34: ../share/genbuild.sh: cannot create obj/build.h: Directory nonexistent
make: *** [obj/build.h] Error "

Make sure to create the folder "obj" in the "src" folder:

cd /Bitdollar/src

mkdir obj

Then try compiling again.


UBUNTU COMPILE Bitdollar-qt
========================
cd Bitdollar

qmake "USE_UPNP=-" Bitdollar-qt.pro

make

Links
======

Website: http://www.Bitdollar.co

BitdollarTalk: http://Bitdollartalk.com/index.php

BitcoinTalk: https://bitcointalk.org/index.php?topic=408268.0

Facebook: https://www.facebook.com/Bitdollarcoin

Twitter: https://twitter.com/Bitdollarcoin

VK: https://vk.com/Bitdollar

Reddit: http://www.reddit.com/r/Bitdollar/

IRC Channel: http://webchat.freenode.net/?channels=#Bitdollarcoin



