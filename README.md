# Winlator Turnip Drivers
A repository containing custom drivers for <a href="https://github.com/brunodev85/winlator">Winlator</a>
- Turnip drivers are compiled from <a href="https://docs.mesa3d.org/index.html">Mesa</a> source.

---

# Installation

### Using the .wcp file (Winlator GlibC 7.1.2 mods and up only)

- Place it anywhere on your device.
- In Winlator, open up the side menu.
- Open the "Contents" page.
- In the drop down box select Turnip.
- Tap "Install Content" and navigate to the .wcp file.
- Tap Continue.</br>

Now you can select the driver in the Container settings.

### For Winlator with Native GlibC:

Copy paste libvulkan_freedreno.so into z:/usr/lib

### For Winlator Proot (non-GlibC):

Copy paste libvulkan_freedreno.so into z:/usr/lib/aarch64-linux-gnu


[Watch the first 3 minutes of this video](https://youtu.be/rQTpv2rtiOY?t=35) (Does not include .wcp installation)

---

# Reporting issues

Report them at <a href="https://gitlab.freedesktop.org/mesa/mesa/-/issues">Mesa Issues</a>.
Not me. I cannot fix, nor will I report for you.

---

# Usage

- [Winlator](docs/winlator.md)
- [Winlator GlibC](docs/winlatorglibc.md)

For any questions contact KIMCHI on the <a href="https://discord.gg/YhpdhVBmXX">Strato discord.</a>

---

# Compiling

You need to apply these patches to your Mesa project:

https://gitlab.freedesktop.org/Pipetto-crypto/mesa/-/commit/9575886914d4a4ca09694c42e261f568ee8575d7

https://gitlab.freedesktop.org/Pipetto-crypto/mesa/-/commit/d264c66f9950cb2331c22c21172a07520fb38c68

https://gitlab.freedesktop.org/Pipetto-crypto/mesa/-/commit/96c4cb07b2a52124021c807f2c1ad4ab1f1cbf9c

Compile project with Proot distro Ubuntu Focal on Termux.

---

### Special thanks to
JeezDisReez<br/>
BrunoSX<br/>
Bylaws<br/>
Mark<br/>
Danylo<br/>
Mesa Turnip team<br/>
Strato testers<br/>
Winlator testers<br/>

### Software used
Mesa [<a href="mesa3d.org">mesa3d.org</a>]<br/>
Termux [<a href="https://f-droid.org/repo/com.termux_1000.apk">f-droid.org</a>]<br/>
Proot<br/>
Ubuntu Focal<br/>
