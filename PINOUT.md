## ESP32-S3 (ESP32-S3-DevKitC-1 Clone)
#### Left Side Pinout

| Pin | GPIO | Alternative Functions |
|-----|------|----------------------|
| 3.3v | - | 3.3V Power Supply |
| 3.3v | - | 3.3V Power Supply |
| RST | - | Reset |
| 4 | GPIO04 | Touch4, ADC1_3, RTC GPIO4 |
| 5 | GPIO05 | Touch5, ADC1_4, RTC GPIO5 |
| 6 | GPIO06 | Touch6, ADC1_5, RTC GPIO6 |
| 7 | GPIO07 | Touch7, ADC1_6, RTC GPIO7 |
| 15 | GPIO15 | XTAL_32K_P, Touch12, RXD 1, [U1S 0], ADC2_4, RTC GPIO15 |
| 16 | GPIO16 | XTAL_32K_N, TXD 1, [U1S 0], ADC2_5, RTC GPIO16 |
| 17 | GPIO17 | [RXD 1], ADC2_6, RTC GPIO17 |
| 18 | GPIO18 | CLK_OUT3, [TXD 1], ADC2_7, RTC GPIO18 |
| 8 | GPIO08 | SDA, Touch8, ADC1_7, RTC GPIO8 |
| 3 | GPIO03 | JTAG, Touch3, ADC1_2, RTC GPIO3 |
| 46 | GPIO46 | LOG |
| 9 | GPIO09 | SCL, FSPIHD, Touch9, ADC1_8, RTC GPIO9 |
| 10 | GPIO10 | SS, FSPI04, FSPICS0, Touch10, ADC1_9, RTC GPIO10 |
| 11 | GPIO11 | MOSI, FSPI05, FSPID, Touch11, ADC2_0, RTC GPIO11 |
| 12 | GPIO12 | SCK, FSPI06, FSPICLK, Touch12, ADC2_1, RTC GPIO12 |
| 13 | GPIO13 | MISO, FSPI07, FSPIQ, Touch13, ADC2_2, RTC GPIO13 |
| 14 | GPIO14 | FSPIWP, FSPIDQS, Touch14, ADC2_3, RTC GPIO14 |
| 5v | - | 5V Power Supply |
| GND | - | Ground |

#### Right Side Pinout

| Pin | GPIO | Alternative Functions |
|-----|------|----------------------|
| GND | - | Ground |
| 43 | GPIO43 | CLK_OUT1, TXD 0 |
| 44 | GPIO44 | CLK_OUT2, RXD 0 |
| 1 | GPIO01 | RTC GPIO1, ADC1_0, Touch1 |
| 2 | GPIO02 | RTC GPIO2, ADC1_1, Touch2 |
| 42 | GPIO42 | MTMS |
| 41 | GPIO41 | CLK_OUT1, MTDI |
| 40 | GPIO40 | CLK_OUT2, MTD0 |
| 39 | GPIO39 | CLK_OUT3, MTCK |
| 38 | GPIO38 | FSPIWP, BUILTIN LED |
| 37 | GPIO37 | SPIDQS, FSPIQ, MISO OTG |
| 36 | GPIO36 | SPI07, FSPICLK, SCK OTG |
| 35 | GPIO35 | SPI06, FSPID, MOSI OTG |
| 0 | GPIO00 | BOOT |
| 45 | GPIO45 | VSPI |
| 48 | GPIO48 | SPICLK_N, RGB LED |
| 47 | GPIO47 | SPICLK_P |
| 21 | GPIO21 | RTC GPIO21 |
| 20 | GPIO20 | RTC GPIO20, ADC2_9, USB_D+, [U1S 1], CLK_OUT1, TXD 2 |
| 19 | GPIO19 | RTC GPIO19, ADC2_8, USB_D-, [U1S 1], CLK_OUT2, RXD 2 |
| GND | - | Ground |
| GND | - | Ground |

**Note:** Functions shown in square brackets [like this] indicate alternative/secondary functions visible in the pinout diagram.
