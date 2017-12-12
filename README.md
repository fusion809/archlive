# archlive
This repository creates an ISO image for 64-bit Arch Linux with the following packages **removed**:

* [b43-fwcutter](https://www.archlinux.org/packages/core/x86_64/b43-fwcutter), my laptop is only compatible with proprietary Broadcom drivers, not open-source onces.
* [clonezilla](https://www.archlinux.org/packages/community/any/clonezilla), I don't use it.
* [openvpn](https://www.archlinux.org/packages/core/x86_64/openvpn), I don't use it. 

The [vim-minimal](https://www.archlinux.org/packages/extra/x86_64/vim-minimal) package replaced with the [vim](https://www.archlinux.org/packages/extra/x86_64/vim) package (I use Vim as my default editor). They seem to be the same package, given that vim-minimal redirects to vim. 

The following packages added:

* [broadcom-wl-dkms](https://www.archlinux.org/packages/community/x86_64/broadcom-wl-dkms), provides the proprietary Broadcom wireless driver (dkms).
* [linux-headers](https://www.archlinux.org/packages/core/x86_64/linux-headers), provides the headers required for the dkms packages.
* [spl-dkms](https://aur.archlinux.org/packages/spl-dkms), provides Solaris Porting Layer kernel modules (dkms). 
* [spl-utils](https://aur.archlinux.org/packages/spl-utils), provides Solaris Porting Layer kernel module support files.
* [zfs-dkms](https://aur.archlinux.org/packages/zfs-dkms), provides kernel modules for ZFS (dkms).
* [zfs-utils](https://aur.archlinux.org/packages/zfs-utils), provides support files for ZFS kernel modules.
