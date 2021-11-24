flight Core
=============

Setup
---------------------
flight Core is the original flight client and it builds the backbone of the network. It downloads and, by default, stores the entire history of flight transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download flight Core, visit [flight.org](https://flight.org).

Running
---------------------
The following are some helpful notes on how to run flight on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/flight-qt` (GUI) or
- `bin/flightd` (headless)

### Windows

Unpack the files into a directory, and then run flight-qt.exe.

### OS X

Drag flight-Core to your applications folder, and then run flight-Core.

### Need Help?

* See the documentation at the [flight Wiki](https://flight.info/)
for help and more information.
* Ask for help on [#flight](http://webchat.freenode.net?channels=flight) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=flight).
* Ask for help on the [flightTalk](https://flighttalk.io/) forums.

Building
---------------------
The following are developer notes on how to build flight on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The flight repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/flight/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [flightTalk](https://flighttalk.io/) forums.
* Discuss general flight development on #flight-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=flight-dev).

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
