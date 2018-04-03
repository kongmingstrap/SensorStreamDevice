SensorStreamDevice
=======

# Requirements

- [Raspberry Pi 2 Model B](http://amzn.asia/5usgt3P)
- [Raspberry Pi用環境センサ基板](https://www.switch-science.com/catalog/1796/)
- microSD card (8 GB)
- NOOBS v2.7.0 later

# Setup Raspberry Pi

## NOOBS

1. Format microSD card to FAT32.
2. Download [NOOBS](https://www.raspberrypi.org/downloads/noobs/).
3. Unzip NOOBS.
4. Copy NOOBS to microSD card.
5. Insert microSD to Raspberry Pi.

## Install Raspbian

1. Connect HDMI, mouse and keyboard to Raspberry Pi.
2. Connect LAN cable to Raspberry Pi.
3. Connect Micro-USB to Raspberry Pi.
4. Install Raspbian

# Setup AWS IoT

## Raspberry Pi

1. `$ sudo pip install AWSIoTPythonSDK`
2. `$ sudo pip install `

## AWS IoT



# Reference
- [Raspberry Pi の接続](https://docs.aws.amazon.com/ja_jp/iot/latest/developerguide/iot-sdk-setup.html)
- [raspberrypi.org](https://www.raspberrypi.org/)
- [NOOBS](https://www.raspberrypi.org/downloads/noobs/)
- [Raspberry Pi のサンプルプログラム（Python）](https://github.com/SWITCHSCIENCE/RPi_EnvSensor/tree/master/Python_RPi)
- [basicPubSub](https://github.com/aws/aws-iot-device-sdk-python/blob/master/samples/basicPubSub/basicPubSub.py)