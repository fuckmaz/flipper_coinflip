
# Flipper Coin Flip


Simple Coin Flip App for the [Flipper Zero](https://www.flipperzero.one)






## Installation

Download the **coinflip.fap** from the [latest release](https://www.flipperzero.one) and copy it to the **apps/Games** directory on your **Flipper Zero** 


## Build

Clone both the repository for the firmware and  and copy the **coinflip** directory to the **applications_user** folders within the firmware:

```
git clone https://github.com/flipperdevices/flipperzero-firmware.git
git clone https://github.com/fuckmaz/flipper_coinflip.git flipperzero-firmware/applications_user/coinflip
```

Plug in your **Flipper Zero** and build the app from within the firmware base-directory:
```
cd flipperzero-firmware
./fbt launch_app APPSRC=applications_user/coinflip
```

The **Flipper Coin Flip** app will automatically be launched on your Flipper after compilation is done.


## TODO

- add coin flip animation

xoxo - maz <3

## Stargazers over time
[![Stargazers over time](https://starchart.cc/fuckmaz/flipper_cigarette.svg?background=%23000000&axis=%23ffffff&line=%23f848dd)](https://starchart.cc/fuckmaz/flipper_coinflip)
