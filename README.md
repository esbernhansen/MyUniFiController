unifi-pfsense
=============

A pfSense package that provides the UniFi Controller software.

Installation
------------

To install the controller software and the rc script:

1. Log in to the pfSense command line shell as root.
2. Run this one-line command, which downloads the install script from Github and executes it with sh (points to current 4.6.6 branch):

  ```
    fetch -o - https://git.io/v2pRl | sh -s
  ```

The install script will install dependencies, download the UniFi controller software, make some adjustments, and start the UniFi controller.
