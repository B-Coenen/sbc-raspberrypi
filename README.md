# sbc-raspberrypi

This repo provides the overlay for building Raspberry Pi generic (models before Pi 5),
Raspberry Pi 5, and RevolutionPi Talos images.

For example usage instructions follow the boot assets guide:

* using [Image Factory](https://docs.siderolabs.com/talos/v1.13/platform-specific-installations/boot-assets#example-raspberry-pi-generic-with-image-factory)
* using [imager](https://docs.siderolabs.com/talos/latest/platform-specific-installations/boot-assets#example-raspberry-pi-overlay-with-imager)

## Overlay Options

| Option            | Description                                                         |
| ----------------- | ------------------------------------------------------------------- |
| `configTxt`       | Completely replace the `config.txt` file with the contents provided |
| `configTxtAppend` | Append the contents provided to the `config.txt` file               |
