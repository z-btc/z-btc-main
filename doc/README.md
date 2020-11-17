Z-BTC
=====================

Setup
---------------------
Z-BTC is an implementation of a node for the Z-BTC network and is one of the pieces of software that provide 
the backbone of the network. It downloads and stores the entire history of Z-BTC transactions (which is currently 
several GBs); depending on the speed of your computer and network connection, the synchronization process can take 
anywhere from a few hours to a day or more.

To download Z-BTC, visit [Z-BTC.com](https://Z-BTC.com/).

Running
---------------------
Z-BTC is only supported on the Linux and docker platforms at this time.

To run Z-BTC on Linux:

* ensure that your system meets the minimum recommended [system requirements](#)
* unpack the files into a directory
* run `bin/bitcoind`

A docker image is available from #. Images are tagged with 
the release version number. The `latest` tag is updated as new versions are released. The source for this image 
(Dockerfiles etc) is maintained in a GitHub repository: https://github.com/z-btc/z-btc. 
 
### Need Help?

* Log an issue on [GitHub] (https://github.com/z-btc/z-btc/issues)
* Ask for help on the [Z-BTC Subreddit](https://www.reddit.com/r/z-btc/) or
[Z-BTC Subreddit](https://www.reddit.com/r/z-btc/).
* Consult [Z-BTC Wiki](https://wiki.Z-BTC.com/) for information about Bitcoin protocol.

Building
---------------------
The following are developer notes on how to build Bitcoin. They are not complete guides, but include notes on the 
necessary libraries, compile flags, etc.

- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Z-BTC repo's [root README](/README.md) contains relevant information on the development process and automated 
testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Benchmarking](benchmarking.md)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distribution is done under the [Open BSV License](/LICENSE). This product includes software developed by the OpenSSL 
Project for use in the [OpenSSL Toolkit](https://www.openssl.org/), cryptographic software written by Eric Young 
([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
