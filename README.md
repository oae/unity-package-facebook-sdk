# Facebook SDK Package

[![openupm](https://img.shields.io/npm/v/io.elhan.facebook-sdk?label=openupm&registry_uri=https://package.openupm.com)](https://openupm.com/packages/io.elhan.facebook-sdk/)

This repository makes it possible to use [facebook-sdk-for-unity](https://github.com/facebook/facebook-sdk-for-unity) with Unity Package Manager (UPM)

![facebook-sdk-for-unity](https://i.imgur.com/b0UYtNT.png)

## Installation

### Install via OpenUPM

The package is available on the [openupm registry](https://openupm.com). It's recommended to install it via [openupm-cli](https://github.com/openupm/openupm-cli).

```
openupm add io.elhan.facebook-sdk
```

### Install via Git URL

- Add following dependency to `Packages/manifest.json` in your project;

  ```json
  {
    "dependencies": {
      "io.elhan.play-services-resolver": "https://github.com/oae/unity-package-play-services-resolver.git#0.1.0",
      "io.elhan.facebook-sdk": "https://github.com/oae/unity-package-facebook-sdk.git#0.1.0",
    }
  }
  ```

> For the official plugin, check out the [original repository](https://github.com/facebook/facebook-sdk-for-unity)
