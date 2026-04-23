# Changelog

This file tracks released versions of Companion on Windows.

## Version 2.0.44.634

### New

  * Added the kAddDevice property support to start a discovery that retrieves available devices

  * Added the possibility to connect multiple Bluetooth LE devices

  * Added kConnectDiscoveredDevice and kRemoveDevice properties support to initialize automatic connection when the device is available. For both properties, the device's Uuid is required
  
  * Added the kDisconnectDiscoveredDevice property support to disconnect a device providing its uuid



### Improvements

  * Deprecated the kStartDiscovery property support. See kAddDevice property addition

  * Deprecated kFavorite property support. Now use kConnectDiscoveredDevice and kRemoveDevice properties

  * Updated **Setup** tab for better scanner/reader connection guidance



### Bug fixes

  * N/A

