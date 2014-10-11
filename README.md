# Overview 

This repository is dedicated to hacking the hardware of the Oculus Rift, and in paritcular enabling an open-source implementation of position tracking on the DK2 on Linux.

# Fork

There haven't been any updates to the main repo so forking to keep abreast of recent developments and actual code.

# Docs

* Links and info/history are tracked on the project wiki
  * https://github.com/lhl/OculusRiftHacking/wiki
* See the changelog for new developments
  * https://github.com/lhl/OculusRiftHacking/commits/master

# Projects

## RiftHacking-0.1
C++ DK2 HMD interface (IMU/LED info) for Linux. See the [corresponding writeup](http://doc-ok.org/?p=1095) for documentation.
* Linux
* by [@okreylos](https://twitter.com/okreylos) 
* GPLv2 licensed

## ouvrt
Linux tracking daemon (ouvrtd) and tools for interacting w/ the DK2 in Linux (like a ROM dumper)
* Linux
* by [pH5](https://github.com/pH5)
* GPLv2 licensed

## hid_win32_interceptor
HID message interceptor for Windows. This tool was used to [kick off reverse engineering](http://www.reddit.com/r/oculus/comments/2i7ujy/call_for_help_for_producing_a_linux_sdk/) the [DK2 protocols](https://github.com/lhl/OculusRiftHacking/wiki/DK2-Firmware-and-Protocol).
* Windows
* by [jherico](https://github.com/jherico)
