# QEMU KVM Windows 10 VM - XML configurations

These config files include a standard VM installed in a real disk partition without that many optimizations apart from Virtio's drivers.


There is also a very similar configuration, but with tweaks targeting the AMD Ryzen processors of the "EPYC" generation. Its topology is taken from
[here](https://mathiashueber.com/performance-tweaks-gaming-on-virtual-machines/), with CPU pinning for 8 vCPUs and host pass-through.
