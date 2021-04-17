OHcoin Core 0.14.2
=====================

Setup
---------------------
OHcoin Core is the original OHcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of OHcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download OHcoin Core, visit [ohcoin.org](https://ohcoin.org).

Running
---------------------
The following are some helpful notes on how to run OHcoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/ohcoin-qt` (GUI) or
- `bin/ohcoind` (headless)

### Windows

Unpack the files into a directory, and then run ohcoin-qt.exe.

### OS X

Drag OHcoin-Core to your applications folder, and then run OHcoin-Core.

### Need Help?

* See the documentation at the [OHcoin Wiki](https://ohcoin.info/)
for help and more information.
* Ask for help on [#ohcoin](http://webchat.freenode.net?channels=ohcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=ohcoin).
* Ask for help on the [OHcoinTalk](https://ohcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build OHcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The OHcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/ohcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [OHcoinTalk](https://ohcointalk.io/) forums.
* Discuss general OHcoin development on #ohcoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=ohcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
