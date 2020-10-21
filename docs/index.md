# T110 Robot with Bluetooth 4.0

[![GitHub release](https://img.shields.io/github/release/kreier/T110.svg)](https://GitHub.com/kreier/T110/releases/)
[![MIT license](https://img.shields.io/github/license/kreier/T110?color=brightgreen)](https://kreier.mit-license.org/)

### 2019-03-30 Update

I could not find a software using plain Bluetooth 4.0 with iOS devices. But there is a good BLE (Bluetooth Low Energy) controller from DFRobot out there. The communication is a little more complicated than the plain strait forward Serial interface with just 2 defined pins for RX and TX and the connection speed, but I made it work: [Project ESP32](../../../ESP32).

### 2018-10-03 Initial thoughts

Arduino robot with Bluetooth 4.0 control

Since iOS only supports Bluetooth from 4.0 on and the HC-05 module is Bluetooth 2.0 we needed to upgrade our first model T-100 with a different Bluetooth module: Now we use AT-09. Then we can use our iPhones to control it!

How to build a robot in 30 seconds: https://www.youtube.com/watch?v=4jvJJgrxoKo.

More details in the [Wiki](https://github.com/kreier/T110/wiki). 

