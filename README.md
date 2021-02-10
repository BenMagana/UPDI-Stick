# UPDI-Stick

[SOURCE](https://makersportal.com/blog/2018/5/19/attiny85-arduino-board-how-to-flash-the-arduino-bootloader-and-run-a-simple-sketch)

## Addding boards to Board Manager
[Board Manager Package](https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json)

Preferences > add link to boards manager URL list
Boards Manager > ATTiny > install

## Bootloading
![alt text](https://github.com/BenMagana/UPDI-Stick/blob/main/img/ATTiny85-bootloading.png?raw=true)

* Tools > programmer > Arduino as ISP
* Board > ATtiny85
* **Burn Bootloader**

# ATtiny has no UART 😥
## [ATtiny87 does!](https://www.digikey.com/en/products/detail/microchip-technology/ATTINY87-SUR/2508038)


![alt text](https://github.com/BenMagana/UPDI-Stick/blob/main/img/ATTIny87-Pinout.jpg?raw=true)
