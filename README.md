# Companion Version 2.0.44.634 Windows 

Companion is the bridge between Socket Mobile barcode scanners / RFID-NFC readers and any application integrating a CaptureSDK that supports the Windows platform, e.g. [C# CaptureSDK](https://github.com/SocketMobile/csharp-capturesdk). It must be installed on the Windows host before a CaptureSDK-enabled application can connect to a Socket Mobile device.

The installation of Companion installs tools to manage communications with Socket Mobile devices and provides the Companion App.

## Devices Compatibility and Companion Versions

The device compatibility shows devices available for any CaptureSDK-enabled application.

|                    Devices                     | 2.0 |
| :--------------------------------------------: | :-: |
|                    **S320**                    | ✅  |
|                 **M930/M940**                  | ✅  |
|        **SocketCam C820[UWP/MAUI-Net9]**       | ✅  |
|               **S720/D720/S820**               | ✅  |
|   **S550, and all older barcode scanners**     | ✅  |
|                    **S370**                    | ✅  |
|                    **M963**                    | ✅  |
|                    **S721**                    | ✅  |

Note: The 32-bit build of Companion does not support Bluetooth LE devices such as the S320, S370, S550 and S721.

## What the Companion App Does

The Companion App enables you to:

- Configure Socket Mobile devices into **Application Mode** so they can be driven by CaptureSDK-enabled apps.
- Manage Bluetooth (Classic and LE) connections with Socket Mobile devices.
- Use the integrated **keyboard wedge** to paste scanned data into the focused application / input field.
- Get a quick visual overview of paired and connected devices.

## Installation

Companion can be downloaded from the [Socket Mobile Developer Portal](https://www.socketmobile.com/support/downloads?categories=companion) - see SocketMobileCompanion-Windows[...] or in the [GitHub Release section](https://github.com/SocketMobile/companion-windows/releases).

Choose the build matching your Windows architecture:

- **x64** — recommended, supports Bluetooth LE devices.
- **ARM64** — for Windows on ARM devices, supports Bluetooth LE devices.
- **x86 (32-bit)** — legacy, does not support Bluetooth LE devices.

## Getting Started

1. Get and install Companion.
2. The Companion App runs automatically; open it from the system tray.
3. Follow the **Setup** tab to pair / connect your Socket Mobile device.
4. Once the device appears as connected, launch your CaptureSDK-enabled application.

A Readme is also provided during the installation with additional information.

## Documentation

More documentation on CaptureSDKs can be found [here](https://docs.socketmobile.dev/main/en/captureApi.html).
