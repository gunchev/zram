README
######

ZRAM is a Linux block device that can be used for compressed swap in memory.
It's useful in memory constrained devices. This provides a service to setup
ZRAM as a swap device based on criteria such as available memory.

This package consists of two simple shell scripts, one configuration file
and one systemd unit file. There is the [zram-generator](https://github.com/systemd/zram-generator),
but it is written in rust and not as simple and easy to hack by any sysadmin.
