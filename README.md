# Liberté Linux: Mission-critical stealth communication

[Liberté Linux](http://dee.su/liberte) is a [secure](http://dee.su/liberte-security), reliable, lightweight and [easy to use](http://dee.su/liberte-documentation) [Gentoo-based](http://www.gentoo.org/) LiveUSB/SD/CD Linux distribution with the primary purpose of enabling anyone to communicate safely and covertly in [hostile environments](http://dee.su/liberte-motivation). Whether you are a privacy advocate, a dissident, or a sleeper agent, you are equally likely to find Liberté Linux useful as a mission-critical communication aid.

See [build instructions](http://dee.su/liberte-build) if you want to master a custom Liberté Linux image. Liberté can also serve as a robust framework for mastering Gentoo-based LiveUSBs/CDs. The build process is fully automated with incremental build support, and is more mature and reliable than most of Gentoo's own outdated [LiveCD tools](http://wolf31o2.org/projects/). Gentoo is an extremely flexible distribution for safely generating custom live media from source — for instance, Liberté does not contain Portage, GCC, Perl or Python.


===This Fork===

This fork is a customized version of Liberte updated to the latest stable (3.11.7-r1) hardened kernel.  It adds the following privacy addons to Firefox: [NoScript](http://noscript.net/), [RequestPolicy](https://www.requestpolicy.com/), [RefControl](http://www.stardrifter.org/refcontrol/), [SecretAgent](http://www.dephormation.org.uk/?page=81), [Disconnect](https://disconnect.me/), [HTTPS-Everywhere](https://www.eff.org/https-everywhere), and [AblockPlus](http://adblockplus.org/) with [Pop-up Addon](http://jessehakanen.net/adblockpluspopupaddon/).  It re-enables [I2P](https://geti2p.net) support, which was removed in version 2013.11 and enables the web console so you can view susimail and other I2P goodies. GnuPG has been [patched](http://gagravarr.livejournal.com/137173.html) to generate 4096 bit keys by default and generate a maximum key size of 8192 bits.  Lastly, by popular demand, [BitCoin](https://bitcoin.org) support has been added via the thin client [Electrum](https://electrum.org).

As in the upstream, all network activity (other than Unsafe-Browser for public Wi-fi login) is routed through [TOR](https://torproject.org) or I2P. I2P tunnels are routed through TOR to keep your IP safely hidden.


License: [GPLv2](http://www.gnu.org/licenses/gpl-2.0.html).
