# Plymouth Splashscreen

Plymouth theme **pix** can be used for a custom splashscreen, copying contents of this folder to:

```
/usr/share/plymouth/themes/pix/
```

And editing `/boot/cmdline.txt` to:

```
console=tty1 root=PARTUUID=8a36818e-02 rootfstype=ext4 elevator=deadline fsck.repair=yes rootwait logo.nologo loglevel=1 quiet splash vt.global_cursor_default=0 plymmouth.ignore-serial-consoles net.ifnames=0
```