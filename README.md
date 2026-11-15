# libimobiledevice Suite for Windows

Automated Windows (x64) builds of the [libimobiledevice](https://github.com/libimobiledevice) tools, built with GitHub Actions every Sunday from the latest upstream sources.

## Included

- **libimobiledevice** with all its tools (`idevice_id`, `ideviceinfo`, `idevicebackup2`, `afcclient`, …)
- **ideviceinstaller** – install, remove and list apps
- **idevicerestore** and **irecovery** – firmware restore, recovery/DFU mode
- **ideviceactivation** – device activation
- **plistutil**, **iproxy**, **inetcat**
- OpenSSL with SSLv3 support for communicating with iPhone OS 1.x

The exact upstream commits are listed in the release notes and in `versions.txt` inside the ZIP.

## Usage

1. Download `libimobile-suite-latest_w64.zip` from the [latest release](../../releases/latest) and extract it.
2. Install Apple Mobile Device Support (included with iTunes or Apple's device drivers). On Windows it takes the place of the usbmuxd service.
3. Connect your device via USB and run the tools from the extracted folder, e.g. `ideviceinfo.exe`.

## License

The tools are distributed under the licenses of their respective upstream projects (mostly LGPL-2.1 or GPL). The OpenSSL PKGBUILD is taken from [MSYS2 MINGW-packages](https://github.com/msys2/MINGW-packages) via [haozhang96/libimobiledevice](https://github.com/haozhang96/libimobiledevice).
