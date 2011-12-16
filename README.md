U-Boot for the Medion P89626
============================

This project will try merge the changes to U-Boot 1.1.2
from the [Medion Sources][medionsources] into a [recent version
of U-Boot][ubootgit].

Any help is appreciated.

To build the new board follow these steps (currently not working):

0. Clone this repository.
1. Download the [Medion sources][medionsources] and extract the x-tools.armv5v6.tar.gz to /opt.
2. `$ CROSS_COMPILE=/opt/x-tools/armv6_le/arm-none-linux-gnueabi/bin/arm-none-linux-gnueabi-`
3. `$ export CROSS_COMPILE`
4. `$ make ox820_config`
5. `$ make`

[medionsources]: http://www.medion.com/de/service/_lightbox/software_details.php?did=10636
[ubootgit]: http://git.denx.de/u-boot.git/
