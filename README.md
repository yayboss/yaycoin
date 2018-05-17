Yaycoin Wallet
=====================================

http://yaycoin.net

What is Yaycoin?
----------------

Yaycoin is a decentralized, an experimental digital currency that enables you to easily send money online to anyone, anywhere in the world.
POW Algo Scrypt, Block Time 1 Minute, Difficulty Retarget 30 Minutes, 500 YAY coins per block, Max Supply 5 Billion Coins.

TESTED ON UBUNTU 16.04

sudo apt-get update &&
sudo apt-get install build-essential libtool autotools-dev autoconf pkg-config libssl-dev git &&
sudo apt-get install libboost-all-dev &&
sudo apt-get install software-properties-common &&
sudo add-apt-repository ppa:bitcoin/bitcoin &&
sudo apt-get update &&
sudo apt-get install libdb4.8-dev libdb4.8++-dev &&
sudo apt-get install libminiupnpc-dev

QT 4
sudo apt-get update &&
sudo apt-get install libqt4-dev libprotobuf-dev protobuf-compiler



CLONING AND BUILDING
sudo git clone https://github.com/yayboss/yaycoin.git &&
cd yaycoin &&
sudo chmod -R 777 * &&
sudo ./autogen.sh &&
sudo ./configure &&
sudo make

For more information, as well as an immediately useable, binary version of
the Yaycoin Wallet software, see http://yaycoin.net

License
-------

Yaycoin Wallet is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see http://opensource.org/licenses/MIT.


