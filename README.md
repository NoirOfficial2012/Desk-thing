# Desk-thing
DeskThing — Open-Source Spotify Car Thing Alternative

A DIY Spotify Car Thing-style music display built with an ESP32 and a 1.8" TFT display.

SongBox connects to the SongBox web player over Wi-Fi and displays the currently playing track on a small dedicated screen.

✨ Features
Displays the current song
Shows artist name
Animated rotating CD
playback progress + time
i-Fi synchronization
Works with the SongBox web player
Custom lavender UI
Open source
Built from inexpensive hardware
Hardware
ESP32 DevKit V1
1.8" 128×160 SPI TFT display
USB cable/power
Jumper wires

No SD card or physical controls are required.

🔌 Wiring


VCC-3V3

LED-3V3

GND-GND

SCK-GPIO 18

SDA-GPIO 23

AO / DC-GPIO 26

RESET-GPIO 4

CS-GPIO 5

Important: The TFT's SDA pin is being used as SPI MOSI, not I²C SDA.
