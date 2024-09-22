# ESP32-WROOM
- Vendor:
  - [esp32](https://www.espressif.com/en/products/socs/esp32)
  - [Esptool.py Documentation](https://docs.espressif.com/projects/esptool/en/latest/esp32/)
- [MicroPython firmware](https://micropython.org/download/ESP32_GENERIC/)
- [MicroPython documentation](https://docs.micropython.org/en/latest/)
- Commands:
  - `ls /dev/tty.*` >> `/dev/tty.usbserial-0001`
  - `esptool.py --port /dev/tty.usbserial-0001 erase_flash`  
  - `esptool.py --chip esp32 --port /dev/tty.usbserial-0001 --baud 460800 write_flash -z 0x1000 firmfare/esp32-1.23.0.bin` 
  - `python -m serial.tools.miniterm /dev/tty.usbserial-0001 115200` 
  - `ampy`
  - `mpfshell`
  - https://www.youtube.com/watch?v=SHwXH7OQPCI&ab_channel=DavidEldridge

