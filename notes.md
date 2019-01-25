Pro Micro:
sudo make iris:craigargh:avrdude

Elite-C:
dfu-programmer atmega32u4 erase
dfu-programmer atmega32u4 flash --eeprom quantum/tools/eeprom_reset.hex
sudo make iris:craigargh:dfu
