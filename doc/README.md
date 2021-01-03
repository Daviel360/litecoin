ChocolateChip Core
=============

Setup
---------------------
ChocolateChip Core is the original ChocolateChip client and it builds the backbone of the network. It downloads and, by default, stores the entire history of ChocolateChip transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download ChocolateChip Core, visit [chocolatechip.org](https://chocolatechip.org/).

Running
---------------------
The following are some helpful notes on how to run ChocolateChip Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/chocolatechip-qt` (GUI) or
- `bin/chocolatechipd` (headless)

### Windows

Unpack the files into a directory, and then run chocolatechip-qt.exe.

### macOS

Drag ChocolateChip Core to your applications folder, and then run ChocolateChip Core.

### Need Help?

* See the documentation at the [ChocolateChip Wiki](https://chocolatechip.info/)
for help and more information.
* Ask for help on [#chocolatechip](http://webchat.freenode.net?channels=chocolatechip) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=chocolatechip).
* Ask for help on the [ChocolateChipTalk](https://chocolatechiptalk.io/) forums, in the [Technical Support section](https://chocolatechiptalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build ChocolateChip Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The ChocolateChip repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [ChocolateChipTalk](https://chocolatechiptalk.io/) forums.
* Discuss general ChocolateChip development on #chocolatechip-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=chocolatechip-dev.

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
