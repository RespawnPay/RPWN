RPWN Core 0.12.5.2
=====================

This is the official reference wallet for RPWN digital currency and comprises the backbone of the RPWN peer-to-peer network. You can [download RPWN Core](https://www.respawn.rocks) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run RPWN on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/RPWN-qt` (GUI) or
- `bin/RPWNd` (headless)

### Windows

Unpack the files into a directory, and then run RPWN-qt.exe.

### OS X

Drag RPWN-Qt to your applications folder, and then run RPWN-Qt.

### Need Help?

* Ask for help on Discord [DISCORD](https://discord.gg/EqtUe2b)
* Ask for help on the [BITCOINTalk](https://bitcointalk.org/index.php?topic=3916320.0) forums.

Building
---------------------
The following are developer notes on how to build RPWN Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The RPWN Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [DISCORD](https://discord.gg/EqtUe2b) server.


### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
