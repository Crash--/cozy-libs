# Cozy Device Helper

![NPM Licence shield](https://img.shields.io/npm/l/cozy-device-helper.svg)
[![npm](https://img.shields.io/npm/v/cozy-device-helper.svg)](https://www.npmjs.com/package/cozy-device-helper)
[![npm](https://img.shields.io/npm/dt/cozy-device-helper.svg)](https://www.npmjs.com/package/cozy-device-helper)

> This library allows to know more information about the device platform

## API

### Platforms

```
import { getPlatform, isWebApp, isMobileApp, isIOSApp, isAndroidApp } from 'cozy-device-helper'
```

To know the platform:
- `getPlatform()`: return `ios`, `android` or `web`
- `isWebApp()`: return `boolean`
- `isMobileApp()`: return `boolean`
- `isIOSApp()`: return `boolean`
- `isAndroidApp()`: return `boolean`

### Device Name

```
import { getDeviceName } from 'cozy-device-helper'
```

To know device name `getDeviceName()`.

### Cordova Plugins

```
import { hasDevicePlugin, hasInAppBrowserPlugin, hasSafariPlugin } from 'cozy-device-helper'
```

- `hasDevicePlugin`: return `boolean`
- `hasInAppBrowserPlugin`: return `boolean`
- `hasSafariPlugin`: return a promise which resolve by a `boolean`
