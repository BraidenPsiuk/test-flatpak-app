Basic app for testing my [flatpak repo](https://flatpak.repo.braiden.dev/) as well as just learning how to build Flatpak apps.

## Prereqs
 - flatpak
 - flatpak-builder

Run with:
```shell
npm i
npm run build # invokes pkg, builds flatpak, installs locally
flatpak run dev.braiden.TestFlatpakApp
```

This is a demo reading from sensor raw accel x (/sys/bus/iio/devices/iio:device2/in_accel_x_raw) on PinePhone Pro via node.js script built as binary with pkg.

*With this I hope dev.braiden.BangleConnect will be coming soon to that flatpak repo!*