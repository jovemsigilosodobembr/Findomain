[![Follow on Twitter](https://img.shields.io/twitter/follow/edu4rdshl.svg?logo=twitter)](https://twitter.com/edu4rdshl)
[![Follow on Twitter](https://img.shields.io/twitter/follow/FindomainApp.svg?logo=twitter)](https://twitter.com/FindomainApp)

[![Travis CI Status](https://travis-ci.org/edu4rdshl/findomain.svg?branch=master)](https://travis-ci.org/edu4rdshl/findomain)
[![Appveyor CI Status](https://ci.appveyor.com/api/projects/status/github/edu4rdshl/findomain?branch=master&svg=true)](https://ci.appveyor.com/project/edu4rdshl/findomain)
[![Build status](https://github.com/Edu4rdSHL/findomain/workflows/Github%20Actions/badge.svg)](https://github.com/Edu4rdSHL/findomain/actions)




# Findomain

![Findomain](images/findomain.png)

The complete solution for domain recognition. Supports screenshoting, port scan, HTTP check, data import from other tools, subdomain monitoring, alerts via Discord, Slack and Telegram, multiple API Keys for sources and much more.

## Chat with us

[![Chat on Discord](https://img.shields.io/discord/697050821057183777.svg?logo=discord)](https://discord.gg/y5JaRbX)

The next table offers you the comparison about what is in Plus version that is not in free version (current repo).

# What Findomain can do?

It table gives you a idea why you should use findomain and what it can do for you. The domain used for the test was aol.com in the following [BlackArch](https://blackarch.org) virtual machine:

```
Host: KVM/QEMU (Standard PC (i440FX + PIIX, 1996) pc-i440fx-3.1)
Kernel: 5.2.6-arch1-1-ARCH
CPU: Intel (Skylake, IBRS) (4) @ 2.904GHz
Memory: 139MiB / 3943MiB
```
The tool used to calculate the time, is the `time` command in Linux.

|Enumeration Tool|Search Time|Total Subdomains Found|CPU Usage|RAM Usage|
|---|---|---|---|---|
|Findomain|real 0m5.515s|84110|Very Low|Very Low|

**Summary:** 84110 subdomains in 5.5 seconds.



# Findomain in depth

See [Subdomains Enumeration: what is, how to do it, monitoring automation using webhooks and centralizing your findings](https://medium.com/@edu4rdshl/subdomains-enumeration-what-is-how-to-do-it-monitoring-automation-using-webhooks-and-5e0a0c6d9127) for a detailed guide including real world examples of how you get the most out of the tool.

# How it works?
It tool doesn't use the common methods for sub(domains) discover, the tool uses Certificate Transparency logs and specific well tested APIs to find subdomains. It method make it tool the most faster and reliable. The tool make use of multiple public available APIs to perform the search. If you want to know more about Certificate Transparency logs, read https://www.certificate-transparency.org/

APIs that we are using at the moment:

- [Certspotter](https://api.certspotter.com/)
- [Crt.sh Database (favorite) or Crt.sh HTTP API](https://crt.sh)
- [Virustotal](https://www.virustotal.com/ui/domains/)
- [Sublist3r](https://api.sublist3r.com/)
- [Facebook](https://developers.facebook.com/docs/certificate-transparency) `**`
- [Spyse (CertDB)](https://certdb.com/apidocs#/Subdomains) `*`
- [Bufferover](http://dns.bufferover.run/)
- [Threatcrowd](https://threatcrowd.org/)
- [Virustotal with apikey](https://www.virustotal.com/) `**`
- [AnubisDB](https://jonlu.ca/anubis/)
- [Urlscan.io](https://urlscan.io/about-api/)
- [SecurityTrails](https://docs.securitytrails.com/docs) `**`
- [Threatminer](https://www.threatminer.org/api.php)
- [C99](https://api.c99.nl/) `**`
- [Archive.org](https://archive.org/)
- [CTSearch](https://ui.ctsearch.entrust.com/ui/ctsearchui)

**Notes**

APIs marked with `**`, **require** an access token to work. Search in the [Findomain documentation](docs/INSTALLATION.md#access-tokens-configuration) how to configure and use it.

APIs marked with `*` can *optionally* be used with an access token, create one if you start experiencing problems with that APIs. Search in the [Findomain documentation](docs/INSTALLATION.md#access-tokens-configuration) how to configure and use it.

**More APIs?**

If you know other APIs that should be added, comment [here](https://github.com/Edu4rdSHL/findomain/issues/7).

# Installation

We offer binarys ready to use for the following platforms (all are for 64 bits only):

* [Linux](docs/INSTALLATION.md#installation-in-linux-using-compiled-artifacts)
* [Windows](docs/INSTALLATION.md#installation-windows)
* [MacOS](docs/INSTALLATION.md#installation-macos)
* [Aarch64 (Raspberry Pi)](docs/INSTALLATION.md#installation-aarch64-raspberry-pi)
* [NixOS](docs/INSTALLATION.md#installation-nixos)
* [Docker](docs/INSTALLATION.md#installation-docker)

If you need to run Findomain in another platform, continue reading the documentation.


# Issues and requests

If you have a problem or a feature request, open an [issue](https://github.com/Edu4rdSHL/findomain/issues).

# Stargazers over time

[![Stargazers over time](https://starchart.cc/Edu4rdSHL/findomain.svg)](https://starchart.cc/Edu4rdSHL/findomain)

## Contributors

### Code Contributors

This project exists thanks to all the people who contribute. [See the contributors list](https://github.com/Edu4rdSHL/findomain/graphs/contributors).

pkg install rust make perl
pkg install rust

apt-get  install rust make perl
apt-get install rust
