bTools
======

Tools for versioning, compiling, instaling and uploading blob software

Tools currently included are:

- avrdude.py: overrides avrdude so that it resets devices - to be used with Arduino Leonardo and Micro
- blobmake: runs on top of cmake providing project interdependencies compilation
- ArduinoToolchain.cmake: toolchain for the use of cmake with Arduino development
- Arduino.cmake: toolchain for the use of cmake with Arduino development
- install.sh: script to install all tools in debian system /usr

Dependencies
============

- cmake - version 2.8.5 or higher
- arduino - version 1.0.1 or higher
  - arduino-core
  - gcc-avr 
  - g++-avr 
  - avrdude
