WWWCoin Core 
=====================================


https://wwwcoin.co

What is wwwcoin?
----------------

wwwcoin was forked  from Litecoin,it is an router digital currency that enables instant payments to anyone, anywhere in the world. wwwcoin uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried
out collectively by the network. wwwcoin Core is the name of open source software which enables the use of this currency.


For more information, as well as an immediately useable, binary version of
the wwwcoin Core software, see [https://wwwcoin.co](https://wwwcoin.co).


How to build wwwcoin Core in ubuntu 16.04 TLS.
----------------
>Build Dependencies
```
## shared libraries and dependencies
sudo apt-get install -y build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils
sudo apt-get -y install libboost-all-dev libminiupnpc-dev libprotobuf-dev protobuf-compiler

## BerkleyDB for wallet support
sudo apt-get install -y software-properties-common
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install -y libdb4.8-dev libdb4.8++-dev

## ZMQ
sudo apt-get install -y libzmq3-dev

## QT5
sudo apt-get -y install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler
sudo apt-get -y install libqrencode-dev

```
>Get Source Code
```
git clone https://github.com/wwcoincore/wwwcoin.git
./autogen.sh
./configure
make
```

Contact
-------

E-mail: wwwcoin.core@gmail.com

License
-------

wwwcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.