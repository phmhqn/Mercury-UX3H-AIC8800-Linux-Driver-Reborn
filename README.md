# Mercury UX3H Network Card Driver for Linux (Reborn).

~~I have edited the driver to work well on my computer running Ubuntu 26.04 (Linux Kernel 7.0.0)~~  
Note: This driver has the support of Claude A.I in finding and fixing errors.

Now support from Linux kernel 5.x to the latest version.

To install, make sure the device is not plugged in. Download the pre-packaged package from the [Releases](https://github.com/phmhqn/Mercury-UX3H-AIC8800-Linux-Driver-Reborn/releases) page, then open your console, navigate to the download folder and execute the following command:
```
sudo apt install ./AIC8800-MercuryUX3H-{version}-rm-UniLinuxKrnl5-6-7.deb
```
> *This driver needs to be built according to your computer's configuration, it may take a long time to complete. We advise you to wait patiently.*

To uninstall the driver, execute this command:
```
sudo apt purge mercury-ux3h-drv
```

Have fun!

---

Credits:

- Mercury https://www.mercurycom.com.cn/ (https://service.mercurycom.com.cn/download-2391.html)

- YoungHguy https://github.com/YoungHguy/ux3h-driver-for-linux

- bk1d https://github.com/bk1d/aic8800fdrvpackage
