Unofficial WiringPi Mirror
==========================

This is an unofficial mirror of WiringPi to support ports (Python/Ruby/etc).  With the
[end of official development](http://wiringpi.com/wiringpi-deprecated/), this repository
has become a mirror of the last "official" source release as well as a source for small
updates to support newer hardware (primarily for use by the ports).

  * The final "official" source release can be found at the
    [`final_source_2.50`](https://github.com/WiringPi/WiringPi/tree/final_official_2.50) tag.
  * The default `master` branch contains code that has been written since that final source
    release to provide support for newer hardware.

Please do not email Gordon if you have issues, he will not be able to help.

Pull-requests may be accepted to add or fix support for newer hardware, but new features or
other changes will not be accepted.

For support, comments, questions, etc please join the WiringPi Discord channel: https://discord.gg/SM4WUVG

# Note
This is a arm64 fork of the unofficial mirror of WiringPi to support ports (Python/Ruby/etc).

Please do not email Gordon if you have issues, he will not be able to help.

Pull-requests are not currently accepted, since this is a mirror.

For support, comments, questions, etc please join the WiringPi Discord channel: https://discord.gg/SM4WUVG

## How to use

Just compile like the original wiringPi and install it.

In addition create a fake cpuinfo as /etc/wiringPi/cpuinfo with entries for Hardware and Revision, eg:
```
  Hardware	: BCM2710
  Revision 	: a020d3
```
