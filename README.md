<h1 align="center">
  <img src="https://raw.githubusercontent.com/BVSHAI/HellFire/main/Assets/logo.png" alt="HellFire Logo">
</h1>

<h2 align="center">
  <img src="https://img.shields.io/badge/-HellFire-61DAFB?logo=firefox&logoColor=white&style=for-the-badge" alt="Product: HellFire">&nbsp;
  <img src="https://img.shields.io/badge/-MPLv2.0-61DAFB?style=for-the-badge" alt="License: MPLv2.0">&nbsp;
  <img src="https://img.shields.io/badge/-125.0a1-61DAFB?style=for-the-badge" alt="Version: 125.0a1">
</h2>

**HellFire**, named after the [HellFire Air-To-Surface missile](https://en.wikipedia.org/wiki/AGM-114_Hellfire), is a Firefox build optimized for absolute performance. It's a direct compilation of Firefox, emphasizing maximum performance without any source, configuration, or visual modifications.

## Releases

We provide builds for both Windows x64 and Linux x64 platforms.

- **Windows x64 Builds**: [Windows Releases](https://github.com/BVSHAI/HellFire/releases/)
- **Linux x64 Builds**: [Linux Releases](https://github.com/BVSHAI/HellFire/releases/)

## Compile Time Optimizations

HellFire offers a variety of optimized builds, each tailored for different levels of optimization and security.

| Configuration          | Optimization and Security Settings                     | Description                                            |
|------------------------|--------------------------------------------------------|--------------------------------------------------------|
| HellFire Lazer         | `-O3` Optimized with Default Security                  | Fast + Default Security, based on Mozilla's default compile |
| HellFire Missile       | `-Ofast` Optimized with Reduced Security               | Super Fast + Less Secure                               |
| HellFire Tracker       | `-Ofast` Optimized with Reduced Security + Debugging   | Super Fast + Less Secure + For Debugging Purposes      |

For more details, explore our Mozconfigs:
- [Win64 Mozconfigs](https://github.com/BVSHAI/HellFire/tree/main/MozConfigs/Win64)
- [Linux64 Mozconfigs](https://github.com/BVSHAI/HellFire/tree/main/MozConfigs/Linux64)

To build your own version, follow the [Firefox Build Guide](https://firefox-source-docs.mozilla.org/setup/). Ensure you copy the desired mozconfig to `mozilla-unified` and rename it to `mozconfig` before running `./mach build`.

> For custom builds like 'hardened' or mixed flag builds, please contact us directly.

## Updates

Stay updated with the latest versions and installer on our [Releases](https://github.com/BVSHAI/HellFire/releases/) page.

## Self Compile

Download the mozconfig for your preferred HellFire build from [HellFire MozConfigs](https://github.com/BVSHAI/HellFire/tree/main/MozConfigs), rename it to 'mozconfig', place it under mozilla-unified, and begin your build.

## Support

Enjoying HellFire's performance boost? Consider supporting us via UPI (India only). Please add a note for 'HellFire Support' when donating. Thank you for your support!

For UPI details, contact us via the email provided below.

## Ethics

For insights into our project's ethos, please read our [Ethics Statement](https://raw.githubusercontent.com/BVSHAI/HellFire/main/ETHICS.md).

## Contact

Feel free to reach out at:

`murgimasalatikka[@]gmail[.]com`
