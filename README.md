# Throughput, link budget and RSSI test for Nordic nRF52840 boards

> Tested with the Nordic nRF5 SDK v15.3.0.

This code is based on the throughput test provided by Nordic and adds the link budget and RSSI metrics.

# Installation
The [nRF5 SDK](https://www.nordicsemi.com/Software-and-Tools/Software/nRF5-SDK) must be installed.

- Go to "..\nRF5_SDK_15.3.0_59ac345\examples\ble_central_and_peripheral\experimental".
- Execute `git clone git@github.com:stby4/ble_app_att_mtu_throughput_rssi.git `
- Open the Segger Embedded Studio project in `ble_app_att_mtu_throughput-rssi\pca10056\s140\ses`

# Usage
Flash two nRF52840 DK with the provided firmware. Use the serial output, e.g. in Segger Embedded Studios "Terminal Emulator" and follow the instructions.