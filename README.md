# X-NUCLEO-NFC10A1

The code has been designed for ST X-NUCLEO-NFC10A1 expansion board to show how to detect, read and write NFC tags.
The X-NUCLEO-NFC10A1 NFC card reader expansion board is based on the ST25R200 device. The expansion board is configured to support ISO14443A/B, ISO15693.
The ST25R200 manages frame coding and decoding in reader mode for standard applications, such as NFC, proximity, and vicinity HF RFID standards. It supports ISO/IEC 14443 type A/B and ISO/IEC 15693 RF communication protocols as well as the detection, reading and writing of NFC Forum type 1, 2, 4, and 5 tags.

## Examples

There is one example with the X-NUCLEO-NFC10A1 library: 
* X_NUCLEO_NFC10A1_HelloWorld: This application is to show how to detect, read and write NFC Forum Type 1, 2, 4 and 5 tags.  
  Pushing the User Button, you can switch to several options like writing a text record, writing a URI record and an Android Application record, formatting an ST tag or reading the content of a tag.

# Dependencies

The X-NUCLEO-NFC10A1 library requires the following STM32duino libraries:

* STM32duino NFC-RFAL: https://github.com/stm32duino/NFC-RFAL
* STM32duino ST25R200: https://github.com/stm32duino/ST25R200

## Documentation

You can find the source files at  
https://github.com/stm32duino/X-NUCLEO-NFC10A1

The ST25R200 datasheet is available at  
https://www.st.com/en/nfc/st25r200.html

