# Infinix X6837 Vendor Configuration

This repository contains the proprietary vendor configuration and generated Android build files required for the **Infinix HOT 40 Pro (X6837)**. It provides the vendor modules, product makefiles, radio configuration, proprietary file manifests, and extracted vendor content used by compatible Android builds.

## Android source-tree location

Place this repository at:

```text
vendor/infinix/X6837
```

The repository is designed to be used with the matching X6837 device tree and kernel-image tree. Keep all three components on compatible branches before starting a build.

## Repository contents

The tree includes Android Blueprint and makefile definitions, vendor product configuration, radio-related files, and the `proprietary/` directory containing extracted vendor components. Generated makefiles should be updated through the project’s documented extraction workflow rather than edited inconsistently by hand.

## Branch and upstream

The active integration branch is `lineage-23.2`. This repository is based on [mt6789-transsion-infinix/vendor_infinix_X6837](https://github.com/mt6789-transsion-infinix/vendor_infinix_X6837).

## Contribution guidelines

Limit changes to X6837-specific vendor integration and reproducible extraction updates. Any change to proprietary file lists or generated build files should identify the source firmware, Android branch, and validation performed.

## Licensing and redistribution

This repository may contain proprietary files supplied by the device vendor. Review upstream licensing terms and applicable redistribution requirements before publishing or distributing build artifacts.

## Related components

- [X6837 device tree](https://github.com/mt6789-x6837/device_infinix_X6837)
- [X6837 kernel-image tree](https://github.com/mt6789-x6837/device_infinix_X6837-kernel)

## Disclaimer

This is a community-maintained project and is not affiliated with or endorsed by Infinix or Transsion.
