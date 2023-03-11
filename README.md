# Debian ZFS Test & Rescue Live Image

A (personal) scripts to build Debian Live image with [ZFS][1] support for
[testing ZFS][2] and / or rescuing ZFS systems.

## Building the live image

```
sudo apt install live-build
git clone https://github.com/janvrany/debian-zfs-live.git
cd debian-zfs-live
sudo lb config
sudo lb build
```

[1]: https://zfsonlinux.org/
[2]: https://janvrany.github.io/2018/01/fun-with-zfs-part-2-creating-debian-zfs-rescue-usb-image.html

