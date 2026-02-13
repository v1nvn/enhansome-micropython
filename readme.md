<p align="center">
  <a href="https://awesome-micropython.com/" style="display:block"><img src="https://raw.githubusercontent.com/mcauser/awesome-micropython/master/docs/img/logo.svg"></a>
</p>
<p align="center">
  <a href="https://awesome.re">
    <img alt="Awesome" src="https://awesome.re/badge-flat.svg">
  </a>
</p>
<hr>

A curated list of awesome MicroPython libraries, frameworks, software and resources.

[MicroPython](https://micropython.org/) is a lean and efficient implementation of the Python 3 programming language that includes a small subset of the Python standard library and is optimised to run on microcontrollers and in constrained environments.

## Contents

* [Libraries](#libraries)
  * [AI](#ai)
  * [Audio](#audio)
  * [Communications](#communications)
  * [Cryptography](#cryptography)
  * [Display](#display)
  * [IO](#io)
  * [Mathematics](#mathematics)
  * [Motion](#motion)
  * [Sensors](#sensors)
  * [Scheduling](#scheduling)
  * [Storage](#storage)
  * [Threading](#threading)
  * [User Interface](#user-interface)
  * [Utilities](#utilities)
* [Community](#community)
* [Tutorials](#tutorials)
* [Books](#books)
* [Frameworks](#frameworks)
* [Resources](#resources)
* [Development](#development)
  * [Code Generation](#code-generation)
  * [Debugging](#debugging)
  * [Firmware](#firmware)
  * [IDEs](#ides)
  * [Logging](#logging)
  * [Shells](#shells)
  * [Tools](#tools)
* [Miscellaneous](#miscellaneous)
* [Contributing](#contributing)

## Libraries

Other places you can look for MicroPython Libraries:

* [PyPi](https://pypi.org/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+MicroPython) - This filter shows just the MicroPython libraries on PyPi. Note: You cannot `pip install` MicroPython libraries. See the [MicroPython docs](https://docs.micropython.org/en/latest/reference/packages.html) for more information on managing packages with MicroPython.
* [GitHub Search](https://github.com/search?q=micropython) - Search GitHub for repositories containing MicroPython.
* [GitHub Topic - MicroPython](https://github.com/topics/micropython) - Browse GitHub Topics for projects tagged with MicroPython.
* [Libraries.io](https://libraries.io/search?q=micropython) - Libraries.io query for MicroPython.
* [GitLab Explore](https://gitlab.com/explore?sort=latest_activity_desc\&utf8=%E2%9C%93\&name=micropython\&sort=latest_activity_desc) - Explore repositories on GitLab.
* [Codeberg Explore](https://codeberg.org/explore/repos?tab=\&sort=recentupdate\&q=micropython) - Explore repositories on Codeberg.

### AI

* [MicroMLP](https://github.com/jczic/MicroMLP) ⭐ 194 | 🐛 6 | 🌐 Python | 📅 2020-12-23 - A micro neural network multilayer perceptron for MicroPython (used on ESP32 and Pycom modules).
* [emlearn-micropython](https://github.com/emlearn/emlearn-micropython) ⭐ 148 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2026-01-14 - Efficient Machine Learning engine for MicroPython.
* [upython-chat-gpt](https://github.com/karlsoderby/upython-chat-gpt) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2023-06-05 - ChatGPT for MicroPython.
* [mp\_esp\_dl\_models](https://github.com/cnadler86/mp_esp_dl_models) ⭐ 10 | 🐛 2 | 🌐 C++ | 📅 2025-09-10 - MicroPython binding for the ESP DL vision models like face detection.
* [MicroPython-NeuralNetwork](https://gitlab.com/olivierlenoir/MicroPython-NeuralNetwork) - Neural Network for MicroPython.

### Audio

* [micropython-i2s-examples](https://github.com/miketeachman/micropython-i2s-examples) ⭐ 298 | 🐛 14 | 🌐 Python | 📅 2025-01-26 - Examples for I2S support on microcontrollers that run MicroPython.
* [micropython-osc](https://github.com/SpotlightKid/micropython-osc) ⭐ 74 | 🐛 3 | 🌐 Python | 📅 2023-11-15 - A minimal OSC client and server library for MicroPython.
* [micropython-dfplayer](https://github.com/ShrimpingIt/micropython-dfplayer) ⭐ 48 | 🐛 0 | 🌐 Python | 📅 2020-05-17 - Driver for DFPlayer Mini using UART.
* [upy-rtttl](https://github.com/dhylands/upy-rtttl) ⭐ 42 | 🐛 2 | 🌐 Python | 📅 2025-02-17 - Python Parser for Ring Tone Text Transfer Language (RTTTL).
* [umidiparser](https://github.com/bixb922/umidiparser) ⭐ 40 | 🐛 3 | 🌐 Python | 📅 2025-03-26 - MIDI file parser for MicroPython, CircuitPython and Python.
* [micropython-vs1053](https://github.com/peterhinch/micropython-vs1053) ⭐ 34 | 🐛 4 | 🌐 Python | 📅 2023-05-14 - Asynchronous driver for VS1053b MP3 player.
* [micropython-buzzer](https://github.com/fruch/micropython-buzzer) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2025-02-09 - Play Nokia compose and mid files on buzzers.
* [micropython-dfplayer](https://github.com/redoxcode/micropython-dfplayer) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2025-11-16 - Library to control the DFPlayer mini MP3 player module.
* [micropython-jq6500](https://github.com/rdagger/micropython-jq6500) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2021-10-16 - Driver for JQ6500 UART MP3 modules.
* [KT403A-MP3](https://github.com/jczic/KT403A-MP3) ⭐ 17 | 🐛 3 | 🌐 Python | 📅 2017-09-02 - Driver for KT403A, used by DFPlayer Mini and Grove MP3 v2.0.
* [yx5300](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/yx5300.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - MP3 player that can be controlled via a serial interface.
* [IoTy vs1003](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/vs1003.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - Driver for the VS1003 MP3 decoder / encoder. Supports playing of MP3, WMA, MIDI, ADPCM, and recording of ADPCM.
* [micropython-longwave](https://github.com/MattMatic/micropython-longwave) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2015-04-27 - WAV player for MicroPython board.
* [micropython-midi](https://github.com/EMATech/micropython-midi) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2014-10-01 - A MIDI implementation example for MicroPython.
* [micropython-sgtl5000](https://github.com/rdagger/micropython-sgtl5000) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-09-09 - Library for SGTL5000 Low Power Stereo Codec w/ Headphone Amp.
* [micropython-tas2505](https://github.com/miketeachman/micropython-tas2505) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2022-10-22 - MicroPython driver for the Texas Instruments TAS2505 Digital Input Class-D Speaker Amplifier.
* [multi-midi](https://github.com/HLammers/multi-midi) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-08-24 - Library for RP2 boards, providing an interface for UART and PIO based hardware MIDI and USB MIDI 1.0.
* [micropython\_nonblocking\_buzzer](https://github.com/jornamon/micropython_nonblocking_buzzer) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2022-07-28 - A nonblocking implementation of a buzzer class that allows you to play basic melodies or sound patterns without blocking the main loop while the sound is being played.

### Communications

#### APIs

* [micropython-utelegram](https://github.com/jordiprats/micropython-utelegram) ⭐ 89 | 🐛 8 | 🌐 Python | 📅 2023-10-06 - Telegram API wrapper for MicroPython.
* [micropython-telegram-bot](https://github.com/antirez/micropython-telegram-bot) ⭐ 56 | 🐛 0 | 🌐 Python | 📅 2024-10-19 - MicroPython telegram bot library: simple way to put your IoT projects on the cloud.
* [telegram-upy](https://github.com/gabrielebarola/telegram-upy) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2022-03-08 - Telegram API wrapper for MicroPython.
* [micropython-spotify-web-api](https://github.com/tltx/micropython-spotify-web-api) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2021-02-08 - A library for using Spotify's web API from a IoT device with MicroPython.
* [MicroPython-GoogleSheet](https://github.com/PerfecXX/MicroPython-GoogleSheet) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2025-09-27 - Fetch, update or append data in Google Sheets using Google Apps Script API.
* [esp32-youtube-display](https://github.com/alvarowolfx/esp32-youtube-display) ⭐ 17 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-04-20 - Display YouTube metrics using Google API and MicroPython.
* [micropython-youtube-api](https://github.com/UnexpectedMaker/micropython-youtube-api) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2020-11-03 - YouTube API in MicroPython.
* [micropython\_demo\_bot](https://github.com/gsampallo/micropython_demo_bot) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2019-07-01 - Little example of how to create a bot for Telegram.
* [micropython-thingspeak](https://github.com/radeklat/micropython-thingspeak) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2018-06-16 - Library for sending data to thingspeak.com from IoT devices running MicroPython (such as ESP8266).
* [micropython\_esp8266\_tweetbot](https://github.com/ayoko/micropython_esp8266_tweetbot) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2016-10-04 - Tweet bot for MicroPython v1.8.4 (ESP8266).
* [micropython-linenotify](https://github.com/PerfecXX/micropython-linenotify) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2023-09-20 - MicroPython library for sending notifications to Line Notify with ESP8266 and ESP32.
* [uEagle](https://github.com/jcalbert/uEagle) ⭐ 5 | 🐛 3 | 🌐 Python | 📅 2021-04-27 - MicroPython Rainforest EAGLE client.
* [micropython-basicdweet](https://github.com/jacklinquan/micropython-basicdweet) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2022-08-31 - A python module for very basic APIs of the free dweet service.
* [micropython\_pushbullet](https://github.com/gsampallo/micropython_pushbullet) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2019-06-11 - Simple example of how to use PushBullet with MicroPython on ESP8266.
* [micropython-dweeter](https://github.com/jacklinquan/micropython-dweeter) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2022-08-31 - A python module for messaging through the free dweet service.
* [micropython-cryptodweet](https://github.com/jacklinquan/micropython-cryptodweet) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2022-08-30 - A python module for very basic APIs of the free dweet service with encryption.

#### Authentication

* [micropython-firebase-auth](https://github.com/WoolDoughnut310/micropython-firebase-auth) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2022-02-18 - Firebase Auth implementation for MicroPython.

#### Bluetooth

* [MicroPythonBLEHID](https://github.com/Heerkog/MicroPythonBLEHID) ⭐ 318 | 🐛 1 | 🌐 Python | 📅 2026-01-17 - Human Interface Device (HID) over Bluetooth Low Energy (BLE) GATT library for MicroPython.
* [uble](https://github.com/dmazzella/uble) ⭐ 89 | 🐛 0 | 🌐 Python | 📅 2024-08-12 - Lightweight Bluetooth Low Energy driver written in pure Python for MicroPython.
* [upyble](https://github.com/Carglglz/upyble) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2020-08-20 - Command line tool for Bluetooth Low Energy MicroPython devices.
* [BTHome-MicroPython](https://github.com/DavesCodeMusings/BTHome-MicroPython) ⭐ 16 | 🐛 6 | 🌐 Python | 📅 2025-11-09 - MicroPython module to format sensor readings for BTHome BLE advertising payloads.
* [PyBoard-HC05-Android](https://github.com/KipCrossing/PyBoard-HC05-Android) ⭐ 11 | 🐛 0 | 🌐 Java | 📅 2020-05-09 - Pyboard HC05 Bluetooth adapter example application.
* [micropython-aioble-itag](https://github.com/mcauser/micropython-aioble-itag) ⭐ 9 | 🐛 0 | 📅 2024-01-14 - Examples using aioble to interact with iTag BLE keychain tags.
* [micropython\_aioble\_examples](https://github.com/ekspla/micropython_aioble_examples) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-01-29 - A few aioble (asyncio BLE) examples of MicroPython using ESP32.
* [micropython-xiaomi-ble-adv-parse](https://codeberg.org/scy/micropython-xiaomi-ble-adv-parse) - Passively retrieve sensor data from some Xiaomi Bluetooth Low Energy (BLE) sensors.
* [mijia-temphum-upy](https://codeberg.org/scy/mijia-temphum-upy) - MicroPython library to read certain Xiaomi Mijia BLE temperature & humidity sensors.

#### CAN

* [micropython-mcp2515](https://github.com/jxltom/micropython-mcp2515) ⭐ 33 | 🐛 5 | 🌐 Python | 📅 2023-04-13 - MicroPython MCP2515 driver, porting from Arduino MCP2515 CAN interface library.
* [Robomaster-Micropython](https://github.com/JohnieBraaf/Robomaster-Micropython) ⭐ 30 | 🐛 2 | 🌐 Python | 📅 2020-11-22 - Robomaster S1 - MicroPython CAN BUS controller.
* [microPython\_MCP2515](https://github.com/capella-ben/microPython_MCP2515) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2023-11-29 - A MicroPython library for the MCP2515 CAN bus controller.
* [micropython-spacecan](https://gitlab.com/alphaaomega/micropython-spacecan) - Spacecan is a MicroPython implementation of the SpaceCAN protocol for embedded systems.

#### Compression

* [tamp](https://github.com/BrianPugh/tamp) ⭐ 61 | 🐛 5 | 🌐 C | 📅 2026-02-09 - A low-memory, MicroPython-optimized, DEFLATE-inspired lossless compression library.
* [ufastlz](https://github.com/dmazzella/ufastlz) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2022-06-11 - MicroPython wrapper for FastLZ, a lightning-fast lossless compression library.
* [micropython-zipfile](https://github.com/jonnor/micropython-zipfile) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2024-11-04 - Read/write ZIP archive files. Ported from CPython, supports DEFLATE compression.
* [bitstruct-micropython](https://github.com/peterzuger/bitstruct-micropython) ⭐ 6 | 🐛 2 | 🌐 C | 📅 2024-03-22 - MicroPython port of [bitstruct](https://github.com/eerimoq/bitstruct) ⭐ 131 | 🐛 14 | 🌐 C | 📅 2026-02-09.

#### Cryptography

* [embit](https://github.com/diybitcoinhardware/embit) ⭐ 107 | 🐛 48 | 🌐 Python | 📅 2025-11-10 - A minimal Bitcoin library for MicroPython and Python 3 with a focus on embedded systems.
* [ucryptoauthlib](https://github.com/dmazzella/ucryptoauthlib) ⭐ 44 | 🐛 0 | 🌐 Python | 📅 2024-08-12 - Lightweight driver for Microchip Crypto Authentication secure elements written in pure Python for MicroPython.
* [ucrypto](https://github.com/dmazzella/ucrypto) ⭐ 43 | 🐛 0 | 🌐 C | 📅 2025-02-01 - MicroPython package for doing fast RSA and elliptic curve cryptography, specifically digital signatures. ECDSA API design inspired from fastecdsa and implementation based on tomsfastmath.
* [mpyaes](https://github.com/iyassou/mpyaes) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2020-09-15 - MicroPython module for AES encryption.
* [microotp](https://github.com/gdassori/microotp) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2017-04-25 - An ESP8266 MicroPython OTP Generator.
* [micropython-aes](https://github.com/piaca/micropython-aes) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2017-07-06 - AES algorithm with pure python implementation.
* [micropython-rsa-signing](https://github.com/artem-smotrakov/micropython-rsa-signing) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2019-06-30 - RSA signing on MicroPython.
* [ucryptography](https://github.com/dmazzella/ucryptography) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2025-12-06 - Lightweight porting of pyca/cryptography to MicroPython based on ARM Mbed TLS.
* [micropython-cryptocfb](https://github.com/jacklinquan/micropython-cryptocfb) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2022-04-28 - A Python module to encrypt and decrypt data with AES-128 CFB mode.
* [micropython-cryptomsg](https://github.com/jacklinquan/micropython-cryptomsg) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2020-05-26 - A MicroPython module to encrypt and decrypt messages with AES CBC mode.
* [mprsa](https://github.com/git-n-pissed/mprsa) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2023-01-24 - A MicroPython module for creating, importing, and exporting RSA keys in DER and PEM formats with PKCS#1, PKCS#8, and X.509/SPKI structures, and signing/verifying and encryption/decryption using blinding and SHA-1 and SHA-256 hashing algorithms.
* [mpy-mbedtls](https://github.com/Carglglz/mpy-mbedtls) ⭐ 3 | 🐛 1 | 🌐 C | 📅 2025-04-12 - MicroPython bindings for some MbedTLS EC and x509 cert/csr functions.
* [tscp](https://github.com/shariltumin/tscp) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2022-09-05 - An endpoint-to-endpoint encryption based on Diffie-Hellman-Merkle with TLS1.3 styled handshake using MicroPython.
* [usigv4](https://github.com/vhespanha/usigv4) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-09-15 - A minimal AWS signature version 4 (SigV4) implementation for MicroPython/embedded use.

#### DNS

* [MicroDNSSrv](https://github.com/jczic/MicroDNSSrv) ⭐ 76 | 🐛 3 | 🌐 Python | 📅 2018-03-07 - A micro DNS server for MicroPython to simply respond to A queries on multi-domains with or without wildcards (used on Pycom modules & ESP32).
* [tinydns](https://github.com/belyalov/tinydns) ⭐ 34 | 🐛 4 | 🌐 Python | 📅 2023-01-05 - Very simple DNS async server for MicroPython.
* [micropython-captiveportal](https://github.com/metachris/micropython-captiveportal) ⭐ 30 | 🐛 2 | 🌐 Python | 📅 2020-12-03 -  Minimal async captive portal for MicroPython (compatible with uasyncio v3/MicroPython 1.13+ as well as earlier versions).
* [aiodns](https://github.com/vshymanskyy/aiodns) ⭐ 23 | 🐛 5 | 🌐 Python | 📅 2025-01-08 - A small, versatile DNS client that provides an async version of `getaddrinfo` and works with any connectivity.
* [ICantBelieveItsNotDNS](https://github.com/yschaeff/ICantBelieveItsNotDNS) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2016-08-19 - "I Can't Believe It's Not DNS!" (ICBIND) is an authoritative DNS server for the ESP8266 written in MicroPython.
* [Micropython-DNSServer-Captive-Portal](https://github.com/p-doyle/Micropython-DNSServer-Captive-Portal) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2021-04-17 - MicroPython WiFi AP Captive Portal with DNS and Web Server.

#### ESP-NOW

* [mesh-espnow-micropython](https://github.com/shariltumin/mesh-espnow-micropython) ⭐ 12 | 🐛 0 | 📅 2023-09-03 - Dynamic Secure Mesh for Collaborative Nodes of IoT devices.
* [mp\_espnow\_wrapper](https://github.com/cnadler86/mp_espnow_wrapper) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-07-28 - Send and receive data between ESPs over ESP-NOW without worries.

#### Ethernet

* [micropy-ENC28J60](https://github.com/przemobe/micropy-ENC28J60) ⭐ 27 | 🐛 2 | 🌐 Python | 📅 2024-01-14 - ENC28J60 Ethernet chip driver for MicroPython (RP2).
* [RP2040 Ethernet example](https://github.com/SteveSEK/Raspberry-Pi-Pico-MicroPython-Ethernet) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2022-02-15 - Ethernet driver, example Python code and YouTube.
* [micropython-ch9121](https://github.com/wybiral/micropython-ch9121) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2020-11-12 - MicroPython library for controlling CH9121 Ethernet modules.
* [Official WIZnet5k](https://github.com/andrewleech/wiznet_ioLibrary_Driver) ⭐ 2 | 🐛 0 | 📅 2022-04-26 - Driver for the WIZnet5x00 series of Ethernet controllers.

#### FTP

* [FTP-Server-for-ESP8266-ESP32-and-PYBD](https://github.com/robert-hh/FTP-Server-for-ESP8266-ESP32-and-PYBD) ⭐ 161 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - Small FTP server for ESP8266/ESP32/Pyboard on the MicroPython platform.
* [micropython-ftplib](https://github.com/SpotlightKid/micropython-ftplib) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2025-05-03 - An FTP client library for MicroPython.
* [MicroFTPServer](https://github.com/cpopp/MicroFTPServer) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2016-10-30 - Minimal FTP Server that can run on an ESP8266 with MicroPython.
* [FtpTiny-Micropython](https://github.com/MZachmann/FtpTiny-Micropython) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2018-03-04 - Really small FTP server that runs in a thread.
* [micropython-uaioftp](https://github.com/cwyark/micropython-uaioftp) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-07-15 - Lightweight FTP library for MicroPython.

#### GPS

* [Asynchronous GPS driver](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/GPS.md) ⭐ 816 | 🐛 4 | 🌐 Python | 📅 2026-01-30 - Receive and parse GPS data as a uasyncio task.
* [micropyGPS](https://github.com/inmcm/micropyGPS) ⭐ 385 | 🐛 15 | 🌐 Python | 📅 2023-02-18 - Full featured GPS NMEA sentence parser.
* [mpy-agps](https://github.com/pulkin/mpy-agps) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2020-04-22 - MicroPython implementation of assisted location services (AGPS).
* [micropython-gnssl76l](https://github.com/tuupola/micropython-gnssl76l) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2018-01-28 - MicroPython I2C driver for Quectel GNSS L76-L (GPS).

#### GSM

* [micropython-upyphone](https://github.com/jeffmer/micropython-upyphone) ⭐ 426 | 🐛 0 | 🌐 Python | 📅 2017-11-24 - A GSM phone using Pyboard and SIM800l.
* [sim800](https://github.com/basanovase/sim800) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2025-12-08 - Library for interfacing with SIM800 module in MicroPython.
* [micropython-sim800](https://github.com/olablt/micropython-sim800) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2018-04-04 - MicroPython driver for SIM800.
* [sim7600](https://github.com/basanovase/sim7600) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-09-14 - MicroPython library for SIM7600 module.
* [MicroPython-AM7020](https://github.com/JiekangHuang/MicroPython-AM7020) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2021-03-29 - MicroPython driver for AM7020 Narrowband Internet of Things (NBIoT) module.
* [sim900](https://github.com/basanovase/sim900) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-09-14 - MicroPython library for SIM900 GSM/GPRS module.
* [SIM800L-micropython](https://github.com/aleppax/SIM800L-micropython) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-08-26 - MicroPython wrapper for common SIM800L AT commands.

#### HTTP

* [mrequests](https://github.com/SpotlightKid/mrequests) ⭐ 62 | 🐛 0 | 🌐 Python | 📅 2024-06-20 - A HTTP client module (not only) for MicroPython with an API similar to requests.
* [uht](https://github.com/nmattia/uht) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2025-08-06 - Lightweight HTTP server for MicroPython (serve websites and handle requests).

#### IoT

* [micropython-iot](https://github.com/peterhinch/micropython-iot) ⭐ 96 | 🐛 1 | 🌐 Python | 📅 2020-09-20 - An approach to designing IoT applications using ESP8266, ESP32 or Pyboard D endpoints.
* [microhomie](https://github.com/microhomie/microhomie) ⭐ 81 | 🐛 3 | 🌐 Python | 📅 2021-01-18 - MicroPython implementation of the Homie MQTT convention for IoT.
* [uPyEcho](https://github.com/lemariva/uPyEcho) ⭐ 57 | 🐛 2 | 🌐 Python | 📅 2021-08-29 - Emulated Belkin WeMo device that works with Amazon Echo (Alexa) using MicroPython on an ESP32.
* [SonosRemote](https://github.com/foosel/SonosRemote) ⚠️ Archived - A remote for Sonos installations running on an ESP8266 and using Sonos HTTP API.
* [iot-core-micropython](https://github.com/GoogleCloudPlatform/iot-core-micropython) ⚠️ Archived - Use MicroPython to connect to Google Cloud IoT Core.
* [micropython-ha-mqtt-device](https://github.com/agners/micropython-ha-mqtt-device) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2020-05-08 - MicroPython module which allows creating Entites for HomeAssistant using MQTT Discovery.
* [aws-iot-GET-POST-loop](https://github.com/manningt/aws-iot-GET-POST-loop) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2021-05-07 - MicroPython code which uses the AWS IoT REST API to GET/POST device state info.
* [SmartUPy](https://github.com/lemariva/SmartUPy) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2018-10-28 - Controlling "Tuya-type" smart power outlets using MicroPython.
* [sensor-mqtt-homeassistant](https://github.com/DougWilkinson/sensor-mqtt-homeassistant) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2022-07-01 - An ESP8266/ESP32 MicroPython-based sensor platform for GPIO, DHT, analog, LED and more. Includes remote updates for .py code from web server and MQTT/Home Assistant integration.
* [aiomqttc](https://github.com/Tangerino/aiomqttc) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2025-05-21 - Asynchronous MQTT Client for MicroPython AND CPython.
* [uPyIoT](https://github.com/lemariva/uPyIoT) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2021-02-11 - Connect an M5Stack ATOM running MicroPython to the Google Cloud Platform (GCP) to collect air-quality variables obtained from reading sensors.
* [micropython-switchbot-thermometer-hygrometer](https://github.com/hilch/micropython-switchbot-thermometer-hygrometer) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-01-23 - Read SwitchBot Thermometer/Hygrometer via Bluetooth.
* [ESP8266-Home-Assistant-Smart-Socket](https://github.com/AnthonyKNorman/ESP8266-Home-Assistant-Smart-Socket) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2019-01-23 - This MicroPython project is to hack a Hyleton313 cheap WiFi smart socket.
* [ESP8266-Home-Assistant-RGB-Bulb](https://github.com/AnthonyKNorman/ESP8266-Home-Assistant-RGB-Bulb) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2018-10-12 - This MicroPython project is to hack a TYWE3S board in a cheap WiFi RGB Bulb.
* [micropython-home-assistant](https://gitlab.com/aapjeisbaas/micropython-home-assistant) - MicroPython-based scripts to extend your Home Assistant-driven home automation projects.

#### IR

* [micropython\_ir](https://github.com/peterhinch/micropython_ir) ⭐ 299 | 🐛 12 | 🌐 Python | 📅 2025-08-13 - Nonblocking device drivers to receive from IR remotes and for IR "blaster" apps.
* [esp8266\_ir](https://github.com/ruoyu0088/esp8266_ir) ⭐ 51 | 🐛 3 | 🌐 Python | 📅 2017-10-16 - Control IR signal by WebSocket.
* [micropython-ys-irtm](https://github.com/mcauser/micropython-ys-irtm) ⭐ 33 | 🐛 0 | 📅 2019-12-20 - MicroPython examples for YS-IRTM 5V NEC Infrared UART transceivers.
* [pico-ir](https://github.com/bartoszadamczyk/pico-ir) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2024-03-20 - IR library for Raspberry Pi Pico.
* [micropython-amg88xx](https://github.com/peterhinch/micropython-amg88xx) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2020-06-17 - Driver for Grid-EYE thermal infrared array sensor (Adafruit 3538).
* [micropython-necir](https://github.com/MattMatic/micropython-necir) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2015-04-27 - NEC infrared capture for TL1838 IR receiver LEDs.
* [Micropython-IR](https://github.com/designerPing/Micropython-IR) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2017-08-02 - Pyboard infrared remote sniff and replay.
* [esp32-ir-remote](https://github.com/cbrand/esp32-ir-remote) ⭐ 11 | 🐛 2 | 🌐 Python | 📅 2022-07-11 - A MicroPython project for running ESP32 IR remotes.
* [micropython\_espX\_IR\_Transceiver](https://github.com/gamefunc/micropython_espX_IR_Transceiver) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2022-05-08 - MicroPython ESP32 IR Transceiver.

#### LoRa

* [micropython-lora](https://github.com/wybiral/micropython-lora) ⭐ 54 | 🐛 5 | 🌐 Python | 📅 2023-04-19 - MicroPython library for controlling a Semtech SX127x LoRa module over SPI.
* [EByte\_LoRa\_E220\_micropython\_library](https://github.com/xreef/EByte_LoRa_E220_micropython_library) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2025-01-29 - MicroPython LoRa EBYTE E220 devices.
* [loraE22](https://github.com/matthias-bs/loraE22) ⭐ 13 | 🐛 2 | 🌐 Python | 📅 2023-01-11 - A MicroPython class for the Ebyte E22 Series LoRa modules.
* [EByte\_LoRa\_E22\_micropython\_library](https://github.com/xreef/EByte_LoRa_E22_micropython_library) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2025-02-23 - MicroPython LoRa EBYTE E22 devices.
* [EByte\_LoRa\_E32\_micropython\_library](https://github.com/xreef/EByte_LoRa_E32_micropython_library) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2023-12-12 - MicroPython LoRa EBYTE E32 devices.
* [micropython-aiolora](https://github.com/wybiral/micropython-aiolora) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2023-01-14 - MicroPython library for controlling a Semtech SX127x LoRa module with asyncio API.
* [micropython-rylr](https://github.com/wybiral/micropython-rylr) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2020-09-07 - MicroPython library for controlling Reyax LoRa modules (RYLR896, RYLR406).
* [silvergeko\_rfm9x](https://github.com/scopelemanuele/silvergeko_rfm9x) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2020-01-24 - Porting to MicroPython of adafruit\_rfm9x.py library.

#### LoRaWAN

* [uPyLoRaWAN](https://github.com/lemariva/uPyLoRaWAN) ⭐ 242 | 🐛 12 | 🌐 Python | 📅 2023-12-26 - ESP32 using MicroPython meets LoRa and LoRaWAN.
* [micropySX126X](https://github.com/ehong-tl/micropySX126X) ⭐ 157 | 🐛 14 | 🌐 Python | 📅 2025-12-07 - Semtech SX126X LoRa driver for MicroPython and CircuitPython.
* [SX127x\_driver\_for\_MicroPython\_on\_ESP8266](https://github.com/Wei1234c/SX127x_driver_for_MicroPython_on_ESP8266) ⭐ 153 | 🐛 1 | 🌐 Python | 📅 2025-06-10 - SX127x (LoRa transceiver) driver for (Micro)Python on ESP8266/ESP32/Raspberry Pi.
* [u-lora](https://github.com/martynwheeler/u-lora) ⭐ 90 | 🐛 15 | 🌐 Python | 📅 2023-10-05 - Raspi-lora for MicroPython.
* [LightLora\_MicroPython](https://github.com/MZachmann/LightLora_MicroPython) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2025-05-22 - Lightweight Interrupt-driven Semtech SX127x Library for MicroPython.
* [sx127x\_esp](https://github.com/azorg/sx127x_esp) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2018-10-03 - Connect Ra-01 module base on LoRaTM sx127x chip to ESP8266/ESP32 under MicroPython.
* [nanoserver](https://github.com/gradoj/nanoserver) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2020-02-24 - MicroPython embedded LoRaWAN server.

#### MDNS

* [micropython-mdns](https://github.com/cbrand/micropython-mdns) ⭐ 83 | 🐛 0 | 🌐 Python | 📅 2025-12-29 - A pure Python implementation of MDNS with support for Service Discovery.

#### Modbus

* [micropython-modbus](https://github.com/brainelectronics/micropython-modbus) ⭐ 145 | 🐛 28 | 🌐 Python | 📅 2024-07-01 - ModBus TCP and RTU library supporting client and host mode. Based on pycom-modbus from Pycom.
* [micropython-modbus](https://github.com/techbase123/micropython-modbus) ⭐ 77 | 🐛 8 | 🌐 Python | 📅 2018-09-05 - Modbus Master library for MicroPython ESP32 devices. Based on pycom-modbus from Pycom.
* [mp\_modbus](https://github.com/eydam-prototyping/mp_modbus) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2021-09-16 - Modbus library for MicroPython.
* [micropython-modbus](https://gitlab.com/extel-open-source/micropython-modbus) - MicroPython port of modbus-tk.

#### MQTT

* [micropython-mqtt](https://github.com/peterhinch/micropython-mqtt) ⭐ 675 | 🐛 21 | 🌐 Python | 📅 2026-01-29 - A 'resilient' asynchronous MQTT client: recovers from WiFi and broker outages.
* [MQBoard](https://github.com/tve/mqboard) ⭐ 128 | 🐛 20 | 🌐 Python | 📅 2022-05-08 - A micro-framework for using MQTT with asyncio on MicroPython boards, primarily on the ESP32.
* [pysmartnode](https://github.com/kevinkk525/pysmartnode) ⭐ 119 | 🐛 2 | 🌐 Python | 📅 2021-05-31 -  MicroPython Smart Home framework.
* [sonoff-mqtt by davea](https://github.com/davea/sonoff-mqtt) ⭐ 60 | 🐛 1 | 🌐 Python | 📅 2017-12-04 - MicroPython scripts to control Sonoff/ESP8266 using MQTT.
* [micropython-adafruit-mqtt-esp8266](https://github.com/miketeachman/micropython-adafruit-mqtt-esp8266) ⭐ 55 | 🐛 1 | 🌐 Python | 📅 2019-02-15 - Using MQTT to Publish/Subscribe to Adafruit IO. MicroPython/CircuitPython implementation on ESP8266/ESP32.
* [micropython-mqtt](https://github.com/chrismoorhouse/micropython-mqtt) ⭐ 41 | 🐛 5 | 🌐 Python | 📅 2018-04-01 - Async MQTT library with auto reconnect for MicroPython devices such as the ESP32 or Pycom devices.
* [micropython-thingspeak-mqtt-esp8266](https://github.com/miketeachman/micropython-thingspeak-mqtt-esp8266) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2022-06-25 - Publish and Subscribe to ThingSpeak using MQTT with MicroPython running on ESP8266/ESP32 platforms.
* [micropython-mqtt-thingspeak](https://github.com/miketeachman/micropython-mqtt-thingspeak) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2022-06-25 - Publish and Subscribe to ThingSpeak using MQTT with MicroPython.
* [umqtt\_aws\_iot](https://github.com/juwul/umqtt_aws_iot) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2017-03-21 - Publish UMQTT messages with MicroPython to AWS IoT.
* [micropython-sparkplugb](https://github.com/sciotaio/micropython-sparkplugb) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2024-10-04 - MicroPython compatible implementation of the Eclipse Sparkplug B Specification.
* [micropython-sonoff-switch](https://github.com/kfricke/micropython-sonoff-switch) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2016-10-13 - Implements an MQTT-controllable switch for the iTead Sonoff Switch using MicroPython.
* [uMQTT](https://github.com/andrewmk/uMQTT) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2015-11-02 - MQTT publish for MicroPython on the WiPy board.
* [tinymqtt](https://github.com/belyalov/tinymqtt) ⭐ 8 | 🐛 3 | 🌐 Python | 📅 2018-08-24 - Async MQTT client for MicroPython.
* [mqtt\_upython](https://github.com/matbgn/mqtt_upython) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2021-09-16 - MQTT Client using MicroPython on ESP8266.

#### NBD

* [unbd](https://github.com/pulkin/unbd) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2023-03-21 - Micro implementation of network block device (NBD) for MicroPython.

#### NFC

* [NFC\_PN532\_SPI](https://github.com/Carglglz/NFC_PN532_SPI) ⭐ 45 | 🐛 5 | 🌐 Python | 📅 2023-07-17 - Partial port of Adafruit CircuitPython to MicroPython of PN532 NFC/RFID control library (SPI).
* [micropython-nfc](https://github.com/rolandvs/micropython-nfc) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-01-12 - Using NFC with MicroPython.
* [micropython\_pn532](https://github.com/luiz-brandao/micropython_pn532) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2022-03-23 - Driver for PN532 NFC/RFID breakout boards based on Adafruit CircuitPython (UART).

#### NTP

* [micropython-ntp](https://github.com/ekondayan/micropython-ntp) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2025-05-25 - Robust NTP library for MicroPython.
* [micropython-ntpclient](https://github.com/wieck/micropython-ntpclient) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-07-11 - NTP client for MicroPython using uasyncio.
* [esp8266\_ntp\_webserver](https://github.com/Roterfux/esp8266_ntp_webserver) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2018-12-05 - MicroPython + ESP8266 + NTP + web server.
* [micropython\_ntpserver](https://github.com/GrantGMiller/micropython_ntpserver) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2019-08-29 - An NTP server written for MicroPython.
* [micropython-ntpd](https://github.com/dave2/micropython-ntpd) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2019-04-14 - An implementation of an NTP daemon in MicroPython.
* [micropython-simple-async-ntpclient](https://github.com/dsiggi/micropython-simple_async_ntpclient) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-02-07 - Very simple async MicroPython module to receive the current time from an NTP server.

#### Object Storage

* [uminio](https://github.com/paluigi/uminio) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-12-03 - MicroPython library to upload files into a MinIO object storage server.

#### OneWire

* [Official OneWire](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/bus/onewire) ⭐ 2,751 | 🐛 280 | 🌐 Python | 📅 2025-12-09 - For devices using the OneWire bus, eg Dallas DS18x20.
* [Onewire\_DS18X20](https://github.com/robert-hh/Onewire_DS18X20) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-06-25 - Classes for driving the DS18x20 sensor with the OneWire protocol for Pycom MicroPython.
* [micropython\_arduino\_control](https://github.com/kevinkk525/micropython_arduino_control) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2020-07-20 - MicroPython library to control an Arduino remotely, with corresponding Arduino code.

#### Onkyo EISCP

* [eiscp-micropython](https://github.com/cbrand/eiscp-micropython) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-05-27 - MicroPython port for the Onkyo-EISCP protocol used, among others, by Pioneer.

#### OTA

* [micropython-ota-updater](https://github.com/rdehuyss/micropython-ota-updater) ⭐ 376 | 🐛 9 | 🌐 Python | 📅 2022-03-09 - OTA Updater for MicroPython.
* [senko](https://github.com/RangerDigital/senko) ⭐ 101 | 🐛 5 | 🌐 Python | 📅 2024-02-23 - Simplest OTA update solution for your MicroPython projects.
* [Micropython-ESP32-OTA](https://github.com/AkhileshThorat/Micropython-ESP32-OTA) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2019-05-25 - MicroPython updater based on rdehuyss/micropython-ota-updater.

#### Proxy

* [uProxy](https://github.com/shawwwn/uProxy) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2024-01-16 - An asyncio-based, memory-efficient HTTP/HTTPS/SOCKS4/SOCKS5 forward proxy server for MicroPython, compatible with CPython.

#### Radio

* [Official nRF24L01](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/radio/nrf24l01) ⭐ 2,751 | 🐛 280 | 🌐 Python | 📅 2025-12-09 - Official driver for nRF24L01 2.4GHz radio modules.
* [micropython\_remote](https://github.com/peterhinch/micropython_remote) ⭐ 83 | 🐛 2 | 🌐 Python | 📅 2021-12-17 - Capture and replay 433MHz remote control codes. Control remote switched power adaptors.
* [micropython-radio](https://github.com/peterhinch/micropython-radio) ⭐ 60 | 🐛 2 | 🌐 Python | 📅 2022-12-26 - Protocols for nRF24L01 2.4GHz radio modules.
* [micropython-TEA5767](https://github.com/alankrantas/micropython-TEA5767) ⭐ 53 | 🐛 0 | 🌐 Python | 📅 2024-02-03 - MicroPython ESP8266/ESP32 driver for TEA5767 FM radio module.
* [micropython-rfsocket](https://github.com/wuub/micropython-rfsocket) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2018-12-06 - MicroPython implementation of popular 433MHz-based RFSockets.
* [ESP32-433Mhz-Transmitter](https://github.com/Aschhoff/ESP32-433Mhz-Transmitter) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2021-03-18 - A pure MicroPython RF transmitter. You can create and add your own encoder.
* [pico\_dcf77\_tx](https://github.com/elehobica/pico_dcf77_tx) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-03-05 - DCF77 transmitter for Raspberry Pi Pico W.
* [micropython-ppm-decoder](https://github.com/dastultz/micropython-ppm-decoder) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2016-08-11 - Utility for decoding an R/C receiver PPM frame signal.
* [ESP32-433Mhz-Receiver-and-Tools](https://github.com/Aschhoff/ESP32-433Mhz-Receiver-and-Tools) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2022-07-07 - ESP32 433MHz receiver written in MicroPython and tools for Windows.
* [pico\_jjy\_tx](https://github.com/elehobica/pico_jjy_tx) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2024-03-08 - JJY transmitter for Raspberry Pi Pico W.
* [micropython-ys-rf34t](https://github.com/mcauser/micropython-ys-rf34t) ⭐ 9 | 🐛 0 | 📅 2019-12-26 - MicroPython examples using YS-RF34T 433MHz ASK/OOK UART transceivers.
* [FM\_Talkie](https://github.com/Wei1234c/FM_Talkie) ⭐ 9 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-02-14 - FM Walkie Talkie using RDA5820N.
* [micropython\_dcf77](https://github.com/dsiggi/micropython-dcf77) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-01-23 - DCF77 receiver and decoder.

#### RC receiver

* [micropython-ppm\_reader](https://github.com/redoxcode/micropython-ppm_reader) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2025-11-16 - Library to decode PPM signals coming from a RC receiver.

#### REPL

* [webrepl](https://micropython.org/webrepl) - MicroPython WebREPL.
* [zepl](https://gitlab.com/zepl1/zepl) - MicroPython WebREPL Console Application using ZeroMQ.
* [jupyter\_micropython\_remote](https://gitlab.com/alelec/jupyter_micropython_remote) - Jupyter kernel to directly execute code on a MicroPython board over the serial/web REPL.
* [FBConsole](https://github.com/boochow/FBConsole) ⭐ 64 | 🐛 1 | 🌐 Python | 📅 2019-10-12 - Framebuffer console class for MicroPython.

#### RFID

* [micropython-mfrc522](https://github.com/wendlers/micropython-mfrc522) ⭐ 181 | 🐛 21 | 🌐 Python | 📅 2024-01-18 - Driver for NXP MFRC522 RFID reader/writer.
* [micropython-wiegand](https://github.com/pjz/micropython-wiegand) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2022-10-27 - Wiegand protocol reader.
* [urdm6300](https://github.com/membermatters/urdm6300) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2024-12-19 - A MicroPython driver for the popular RDM6300 RFID card reader.

#### RPC

* [ujrpc](https://github.com/zcattacz/ujrpc) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2024-12-30 - JSON RPC for MicroPython.

#### RTC

* [micropython-tinyrtc-i2c](https://github.com/mcauser/micropython-tinyrtc-i2c) ⭐ 69 | 🐛 2 | 🌐 Python | 📅 2023-01-13 - Driver for DS1307 RTC and AT24C32N EEPROM.
* [micropython-ds1302-rtc](https://github.com/omarbenhamid/micropython-ds1302-rtc) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2021-07-12 - DS1302 RTC Clock driver for MicroPython.
* [micropython-DS3231-AT24C32](https://github.com/pangopi/micropython-DS3231-AT24C32) ⭐ 34 | 🐛 2 | 🌐 Python | 📅 2024-07-25 - MicroPython driver for DS3231 RTC.
* [DS3231micro](https://github.com/notUnique/DS3231micro) ⭐ 16 | 🐛 3 | 🌐 Python | 📅 2023-03-06 - MicroPython library for DS3231.
* [PCF8563\_PythonLibrary](https://github.com/lewisxhe/PCF8563_PythonLibrary) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2025-05-24 - MicroPython library for NXP PCF8563 Real-time clock/calendar.
* [micropython-ds1307](https://github.com/brainelectronics/micropython-ds1307) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2023-06-12 - MicroPython driver for DS1307 RTC.
* [esp-ds3231-micropython](https://github.com/HAIZAKURA/esp-ds3231-micropython) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2025-05-22 - A DS3231 library for ESP8266/ESP32 with MicroPython.
* [Micropython\_TinyRTC](https://github.com/AnthonyKNorman/Micropython_TinyRTC) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2016-11-03 - Driver for DS1307 RTC.
* [DS1307](https://github.com/peter-l5/DS1307) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2023-05-24 - MicroPython driver for the DS1307 real time clock.
* [micropython-mcp7940](https://github.com/mattytrentini/micropython-mcp7940) ⭐ 1 | 🐛 10 | 🌐 Python | 📅 2025-05-22 - Driver for the Microchip MCP7940 RTC.
* [micropython-ds1302-rtc](https://github.com/PaszaVonPomiot/micropython-ds1302-rtc) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-04-27 - DS1302 RTC Clock driver for MicroPython.
* [DS3231](https://github.com/octaprog7/DS3231) ⚠️ Archived - MicroPython module for the DS3231 clock from Maxim Integrated.
* [micropython\_rx-8035](https://github.com/ekspla/micropython_rx-8035) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-02-04 - A MicroPython Driver for Seiko Epson's RTC, RX-8035SA/LC.

#### Serial

* [I2C Slave](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/I2C.md) ⭐ 816 | 🐛 4 | 🌐 Python | 📅 2026-01-30 - Uses the Pyboard's I2C slave mode to implement a full duplex asynchronous link. Principal use case is for ESP8266 which has only one UART.
* [mpy-miniterm](https://github.com/jeffmakes/mpy-miniterm) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2024-01-16 - Tool for seamless serial debug and file synchronisation with MicroPython devices via the serial REPL.
* [microSDI12](https://github.com/insighio/microSDI12) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2025-11-27 - A mini SDI-12 implementation for getting sensor info over RS-485.
* [MicroPython-MorseCode](https://gitlab.com/olivierlenoir/MicroPython-MorseCode) - International Morse Code using a microcontroller with MicroPython.

#### Serialization

* [minipb](https://github.com/dogtopus/minipb) ⭐ 63 | 🐛 6 | 🌐 Python | 📅 2023-03-28 - Mini Protobuf {de}serializer in pure Python.
* [micropython-msgpack](https://github.com/peterhinch/micropython-msgpack) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2025-06-30 - MessagePack serialisation library optimised for MicroPython.
* [micropython-uprotobuf](https://github.com/jazzycamel/micropython-uprotobuf) ⭐ 24 | 🐛 2 | 🌐 Python | 📅 2023-02-10 - A lightweight implementation of Google's Protocol Buffers (protobuf) for MicroPython.
* [ucbor](https://github.com/dmazzella/ucbor) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2024-08-19 - Lightweight implementation of cbor for MicroPython.
* [upy-msgpack](https://github.com/SpotlightKid/upy-msgpack) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-05-07 - A lightweight MessagePack (de)serialization library (not only) for MicroPython.
* [micropython-msgpack](https://github.com/gitcnd/micropython-msgpack) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-07-23 - MessagePack serialisation library optimised for MicroPython.

#### SMTP

* [uMail](https://github.com/shawwwn/uMail) ⭐ 97 | 🐛 1 | 🌐 Python | 📅 2025-05-16 - A lightweight, scalable SMTP client for sending email in MicroPython.

#### Sockets

* [XAsyncSockets](https://github.com/jczic/XAsyncSockets) ⭐ 43 | 🐛 3 | 🌐 Python | 📅 2024-04-02 - XAsyncSockets is an efficient Python/MicroPython library of managed asynchronous sockets.

#### SOCKS

* [micropython-socks](https://github.com/kost/micropython-socks) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2020-10-11 - MicroPython library implementing SOCKS server.

#### TCP

* [us2n](https://github.com/tiagocoutinho/us2n) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2017-12-16 - MicroPython bridge between UART and TCP for the ESP32.

#### Telnet

* [MicroTelnetServer](https://github.com/cpopp/MicroTelnetServer) ⭐ 79 | 🐛 7 | 🌐 Python | 📅 2024-05-27 - Simple telnet server for MicroPython and the ESP8266 allowing telnet clients access to the REPL.
* [telnetd](https://github.com/gitcnd/telnetd) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-08-17 - Powerful telnetd server to access MicroPython REPL (with strong password support, and unlimited connections).

#### Text-to-Speech

* [micropython-SYN6988](https://github.com/scruss/micropython-SYN6988) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2023-06-29 - MicroPython library for the VoiceTX SYN6988 text to speech module.
* [micropython-samtts](https://github.com/jacklinquan/micropython-samtts) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-04-20 - A MicroPython port of Software Automatic Mouth Text-To-Speech program.

#### Time

* [ustrftime](https://github.com/iyassou/ustrftime) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-07-31 - A MicroPython implementation of time.strftime.

#### VoIP

* [uPyVoip](https://github.com/RetepRelleum/uPyVoip) ⭐ 25 | 🐛 2 | 🌐 Python | 📅 2020-12-06 - VoIP for MicroPython ESP32 with Interactive Voice Response.

#### Web

* [microdot](https://github.com/miguelgrinberg/microdot) ⭐ 2,070 | 🐛 5 | 🌐 Python | 📅 2026-02-04 - The impossibly small web framework for MicroPython.
* [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) ⭐ 712 | 🐛 55 | 🌐 Python | 📅 2025-08-18 - The last micro web server for IoTs (MicroPython) or large servers (CPython), that supports WebSocket, routes, template engine and with really optimized architecture (mem allocations, async I/Os).
* [MicroWebSrv](https://github.com/jczic/MicroWebSrv) ⭐ 662 | 🐛 13 | 🌐 Python | 📅 2023-01-17 - A micro HTTP web server that supports WebSockets, HTML/Python language templating and routing handlers, for MicroPython (used on Pycom modules & ESP32).
* [tinyweb](https://github.com/belyalov/tinyweb) ⭐ 279 | 🐛 20 | 🌐 Python | 📅 2024-05-14 - Simple and lightweight HTTP async server for MicroPython.
* [uwebsockets](https://github.com/danni/uwebsockets) ⭐ 216 | 🐛 15 | 🌐 Python | 📅 2023-06-09 - MicroPython WebSocket implementation for ESP8266.
* [micropyserver](https://github.com/troublegum/micropyserver) ⭐ 157 | 🐛 3 | 🌐 Python | 📅 2025-01-12 - MicroPyServer is a simple HTTP server for MicroPython projects.
* [micropython-nanoweb](https://github.com/hugokernel/micropython-nanoweb) ⭐ 118 | 🐛 1 | 🌐 Python | 📅 2025-11-14 - Full async MicroPython web server with small memory footprint.
* [upy-websocket-server](https://github.com/BetaRavener/upy-websocket-server) ⭐ 85 | 🐛 3 | 🌐 Python | 📅 2023-03-15 - MicroPython (ESP8266) WebSocket server implementation.
* [microCoAPy](https://github.com/insighio/microCoAPy) ⭐ 68 | 🐛 5 | 🌐 Python | 📅 2025-06-20 - A mini client/server implementation of CoAP (Constrained Application Protocol) into MicroPython.
* [MicroWebCli](https://github.com/jczic/MicroWebCli) ⭐ 56 | 🐛 9 | 🌐 Python | 📅 2020-12-12 - A micro HTTP web client for MicroPython (used on Pycom modules & ESP32).
* [micropython-urouter](https://github.com/majoson-chen/micropython-urouter) ⭐ 53 | 🐛 0 | 🌐 Python | 📅 2023-01-16 - A lightweight HTTP request routing processing support library based on MicroPython. The previous name was micro-route.
* [micropython-captive-portal](https://github.com/amora-labs/micropython-captive-portal) ⭐ 51 | 🐛 3 | 🌐 Python | 📅 2018-06-04 - A captive portal demo for MicroPython.
* [ESP8266WebServer](https://github.com/codemee/ESP8266WebServer) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2022-04-03 - ESP8266 web server for MicroPython.
* [uPyPortal](https://github.com/lemariva/uPyPortal) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2017-11-12 - A captive portal for MicroPython using ESP32 (Wemos).
* [micropython-aioweb](https://github.com/wybiral/micropython-aioweb) ⭐ 36 | 🐛 4 | 🌐 Python | 📅 2023-01-13 - A minimalist asyncio web framework for MicroPython.
* [MicroRESTCli](https://github.com/jczic/MicroRESTCli) ⭐ 30 | 🐛 2 | 🌐 Python | 📅 2020-12-12 - A micro JSON REST web client based on MicroWebCli for MicroPython (used on Pycom modules & ESP32).
* [thimble](https://github.com/DavesCodeMusings/thimble) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2025-03-28 - A tiny web framework for MicroPython.
* [micropython-noggin](https://github.com/larsks/micropython-noggin) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2017-11-17 - A very simple web server for MicroPython.
* [micropython-configserver](https://github.com/carstenblt/micropython-configserver) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2017-08-21 - Captive portal for MicroPython including a dumb DNS server and a web server to configure WiFi networks.
* [micropidash](https://github.com/kritishmohapatra/micropidash) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-02-12 – Simple web dashboard served directly from MicroPython boards (ESP32, Pico W).
* [microsky](https://github.com/nakagami/microsky) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-01-05 - A [Bluesky](https://bsky.app/) client for Python and MicroPython.
* [CaptiveWebServer](https://github.com/joewez/CaptiveWebServer) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-10-06 - Simple MicroPython web server for serving a website from a captive portal.
* [wlan-relays](https://github.com/oliver-joos/wlan-relays) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-11-01 - Very simple HTTP server written in MicroPython for controlling the pins of an ESP32 board.

#### WiFi

* [WiFiManager](https://github.com/tayfunulu/WiFiManager) ⭐ 409 | 🐛 27 | 🌐 Python | 📅 2025-08-08 - WiFi manager for ESP8266 - ESP12 - ESP32 - MicroPython.
* [micropython-wifimanager](https://github.com/mitchins/micropython-wifimanager) ⭐ 69 | 🐛 0 | 🌐 Python | 📅 2025-07-23 - A simple network configuration utility for MicroPython on the ESP8266 board.
* [micropython-wifi\_manager](https://github.com/ferreira-igor/micropython-wifi_manager) ⭐ 67 | 🐛 6 | 🌐 Python | 📅 2023-10-09 - WiFi Manager for ESP8266 and ESP32 using MicroPython.
* [Micropython-ESP-WiFi-Manager](https://github.com/brainelectronics/Micropython-ESP-WiFi-Manager) ⭐ 37 | 🐛 7 | 🌐 Python | 📅 2023-06-16 - WiFi Manager to configure and connect to networks.
* [HueBridge](https://github.com/FRC4564/HueBridge) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2019-09-06 - Philips Hue Bridge.
* [mpy-wpa\_supplicant](https://github.com/Carglglz/mpy-wpa_supplicant) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-04-10 - MicroPython module to connect to the nearest known Wifi AP.

#### Zigbee

* [ZbPy](https://github.com/osresearch/ZbPy) ⭐ 52 | 🐛 3 | 🌐 Python | 📅 2020-09-12 - MicroPython IEEE802.15.4 / Zigbee parser.

### Cryptography

#### Historical

* [enigmapython](https://github.com/denismaggior8/micropython-enigma-python) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-01-06 - A simple yet faithful library to emulate different Enigma machines models using MicroPython.

### Display

#### E-Paper

* [micropython-waveshare-epaper](https://github.com/mcauser/micropython-waveshare-epaper) ⭐ 383 | 🐛 21 | 🌐 Python | 📅 2021-09-01 - Drivers for various Waveshare ePaper modules.
* [uc8151\_micropython](https://github.com/antirez/uc8151_micropython) ⭐ 162 | 🐛 4 | 🌐 Python | 📅 2024-04-05 - UC8151 / IL0373 MicroPython e-paper display driver with support for greyscales and fast updates.
* [Inkplate-micropython](https://github.com/SolderedElectronics/Inkplate-micropython) ⭐ 89 | 🐛 5 | 🌐 Python | 📅 2026-02-09 - MicroPython driver for Inkplate boards.
* [micropython-waveshare-epd](https://github.com/ayoy/micropython-waveshare-epd) ⭐ 57 | 🐛 3 | 🌐 Python | 📅 2018-04-03 - Waveshare ePaper Display driver for devices running Pycom-flavored MicroPython.
* [uPyEINK](https://github.com/lemariva/uPyEINK) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2020-02-23 - Control a Waveshare 7.5" E-INK display using an ESP32 running MicroPython.
* [eInk-micropython](https://github.com/dhallgb/eInk-micropython) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2025-05-31 - eInk library for Waveshare 4.3inch device on MicroPython.
* [eink](https://github.com/chevdor/eink) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2021-11-09 - An eInk, ePaper display driver for MicroPython and ESP32.
* [micropython-inkplate6](https://github.com/tve/micropython-inkplate6) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2021-04-11 - MicroPython driver for the Inkplate 6.
* [micropython\_DEPG0213BN](https://github.com/Inqbus/micropython_DEPG0213BN) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2021-09-04 - Pure MicroPython driver for the DEPG0213BN eInk display found on the TTGO T5 V2.3 ESP32 boards.
* [MicroPython-2.9-inch-ePaper-Library](https://github.com/rdagger/MicroPython-2.9-inch-ePaper-Library) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - MicroPython Display Driver for WaveShare 2.9inch e-Paper Display (B).
* [ssd1675a](https://github.com/mattytrentini/ssd1675a) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - Driver for SSD1675-based e-paper displays.
* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) ⚠️ Archived - SSD1606 active matrix ePaper display 128x180.

#### Fonts

* [micropython-font-to-py](https://github.com/peterhinch/micropython-font-to-py) ⭐ 453 | 🐛 8 | 🌐 Python | 📅 2025-05-28 - A Python 3 utility to convert fonts to Python source capable of being frozen as bytecode.
* [writer](https://github.com/peterhinch/micropython-font-to-py/blob/master/writer/WRITER.md) ⭐ 453 | 🐛 8 | 🌐 Python | 📅 2025-05-28 - A simple way to render above Python fonts to displays whose driver is subclassed from `framebuf`.
* [microfont](https://github.com/antirez/microfont) ⭐ 72 | 🐛 2 | 🌐 Python | 📅 2026-01-31 - Text drawing library for MicroPython framebuffer.
* [packed-font](https://github.com/mark-gladding/packed-font) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2023-06-05 -  Memory efficient MicroPython fonts for the Pico Pi and SSD1306 OLED Display.
* [ttgo-hershey-fonts](https://github.com/russhughes/ttgo-hershey-fonts) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2021-02-25 - MicroPython Hershey font demo for the TTGO-LCD board.
* [ssd1306big](https://github.com/nickpmulder/ssd1306big) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2021-02-08 - A font for MicroPython on 128x64 pixel SSD1306 OLED display.
* [framebuf2](https://github.com/peter-l5/framebuf2) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2023-05-30 - MicroPython FrameBuffer extension: larger and rotated font, triangles and circles.
* [micropython\_GT30L24T3Y\_big5\_font](https://github.com/alankrantas/micropython_GT30L24T3Y_big5_font) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2021-08-20 - MicroPython driver for reading BIG-5 Chinese characters from GT30L24T3Y / ER3303-1 SPI module.

#### Graphics

* [micropython-stage](https://github.com/python-ugame/micropython-stage) ⭐ 43 | 🐛 1 | 🌐 Python | 📅 2021-09-02 - A MicroPython port of the Stage game library.
* [mpy-img-decoder](https://github.com/remixer-dec/mpy-img-decoder) ⭐ 40 | 🐛 1 | 🌐 Python | 📅 2020-09-24 - PNG and JPEG decoder / parser / renderer in pure MicroPython.
* [microplot](https://github.com/romilly/microplot) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2021-03-23 - Simple MicroPython plotting package.
* [Tempe](https://github.com/unital/tempe) ⭐ 21 | 🐛 25 | 🌐 Python | 📅 2025-10-31 - Efficient MicroPython graphics library built on top of `framebuf`.
* [micropython-png](https://github.com/Ratfink/micropython-png) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2016-08-20 - Derivative of PyPNG for use with MicroPython.
* [micropython-oled-progressbars](https://github.com/follower46/micropython-oled-progressbars) ⭐ 14 | 🐛 4 | 🌐 Python | 📅 2019-08-01 - A collection of progress bars for use with ESP8266 and ESP32 on OLED displays.
* [micropython-microbmp](https://github.com/jacklinquan/micropython-microbmp) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-04-23 - A small Python module for BMP image processing.
* [mp\_jpeg](https://github.com/cnadler86/mp_jpeg) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2025-12-13 - A very fast MicroPython JPEG encoder and decoder for the ESP32.
* [MicroPython\_UPLOT](https://github.com/jposada202020/MicroPython_UPLOT) ⚠️ Archived - MicroPython Small Graphics Framework.

#### GUI

* [micropython-nano-gui](https://github.com/peterhinch/micropython-nano-gui) ⭐ 631 | 🐛 2 | 🌐 Python | 📅 2026-02-02 - A tiny display-only GUI with a limited set of GUI objects (widgets) for displays whose display driver is subclassed from the `framebuf` class. With drivers for TFT, ePaper and OLED displays.
* [micro-gui](https://github.com/peterhinch/micropython-micro-gui) ⭐ 338 | 🐛 12 | 🌐 Python | 📅 2026-01-19 - Derived from nano-gui and supporting the same displays and hosts, this provides for user input via push buttons or a navigation joystick and an optional rotary encoder.
* [lvgl](https://github.com/lvgl/lv_binding_micropython) ⭐ 336 | 🐛 64 | 🌐 C | 📅 2025-09-17 - An object-oriented, component-based high-level GUI library with MicroPython binding.
* [TFT-GUI](https://github.com/peterhinch/micropython-tft-gui) ⭐ 95 | 🐛 2 | 🌐 Python | 📅 2020-06-16 - A fast touch GUI for large displays based on SSD1963 controller with XPT2046 touch controller.
* [micropython-core2](https://github.com/lemariva/micropython-core2) ⭐ 62 | 🐛 4 | 🌐 C | 📅 2022-03-29 - Extends LV-MicroPython for the M5Stack CORE2 with MPU6886, ILI9342C, BM8563 and AXP192 drivers.
* [micropython-touch](https://github.com/peterhinch/micropython-touch) ⭐ 58 | 🐛 6 | 🌐 Python | 📅 2025-12-21 - Derived from nano-gui and supporting the same displays and hosts, this offers touch input. Supports various touch controllers.
* [micropython-lcd160cr-gui](https://github.com/peterhinch/micropython-lcd160cr-gui) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2020-11-30 - Simple touch-driven event based GUI for the Pyboard and LCD160CR colour display.
* [micropython-nextion](https://github.com/brainelectronics/micropython-nextion) ⭐ 13 | 🐛 5 | 🌐 Python | 📅 2023-06-12 - Control Nextion displays using MicroPython.
* [micropython\_ra8875](https://github.com/peterhinch/micropython_ra8875) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2021-04-16 - MicroPython device driver and nano-GUI for RA8875 based displays.
* [mp\_lvgl\_widgets](https://github.com/kdschlosser/mp_lvgl_widgets) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-04-12 - Widgets for the MicroPython Port of LVGL.

#### LCD Character

* [python\_lcd](https://github.com/dhylands/python_lcd) ⭐ 326 | 🐛 18 | 🌐 Python | 📅 2023-02-17 - Driver for HD44780-compatible dot matrix LCDs.
* [micropython-i2c-lcd](https://github.com/Bucknalla/micropython-i2c-lcd) ⭐ 38 | 🐛 0 | 🌐 Python | 📅 2025-05-04 - Driver for I2C 2x16 LCD Screens.
* [micropython-lcd](https://github.com/wjdp/micropython-lcd) ⭐ 21 | 🐛 3 | 🌐 Python | 📅 2014-10-27 - Class for controlling the HD44780 from a MicroPython Pyboard.
* [micropython-i2c-lcd](https://github.com/brainelectronics/micropython-i2c-lcd) ⭐ 19 | 🐛 4 | 🌐 Python | 📅 2023-10-21 - MicroPython package to control HD44780 LCD displays 1602 and 2004 via I2C.
* [LCM1602-14\_LCD\_Library](https://github.com/Bhavithiran97/LCM1602-14_LCD_Library) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2021-11-22 - driver for AIP31068L [3.3 V I2C and SPI 1602 Serial Character LCDs](https://www.cytron.io/p-3v3-i2c-and-spi-1602-serial-character-lcd).
* [micropython-charlcd](https://github.com/rdagger/micropython-charlcd) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2017-07-01 - Driver for HD44780-compatible LCDs.
* [micropython\_i2c\_lcd](https://github.com/Thomascountz/micropython_i2c_lcd) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2024-06-21 - MicroPython library for interacting with HD44780-based LCD displays through a PCF8574 I/O expander. It offers a high-level API for LCD control, including text display, cursor manipulation, and backlight settings, while also providing lower-level access to the GPIO operations on the PCF8574.
* [lcdi2c](https://github.com/slothyrulez/lcdi2c) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2016-02-22 - Driver for HD44780-compatible dot matrix LCDs.
* [Grove\_RGB\_LCD](https://github.com/dda/MicroPython/blob/master/Grove_RGB_LCD.py) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2014-12-05 - Driver for SeeedStudio's Grove RGB LCD.
* [pyboard-LCD-character-display](https://github.com/scitoast/pyboard-LCD-character-display) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2016-04-19 - Pyboar driver for HDD44780-compatible 1602 LCDs.
* [HD44780-lcd-upy](https://gitlab.com/rafalosa/HD44780-lcd-upy) - MicroPython module for controlling a generic HD44780 LCD.

#### LCD Graphic

* [Official LCD160CR](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/display/lcd160cr) ⭐ 2,751 | 🐛 280 | 🌐 Python | 📅 2025-12-09 - Driver for official MicroPython LCD160CR display with resistive touch sensor.
* [micropython-pcd8544](https://github.com/mcauser/micropython-pcd8544) ⭐ 73 | 🐛 2 | 🌐 Python | 📅 2018-08-23 - Driver for Nokia 5110 PCD8544 84x48 LCD modules.
* [micropython-st7565](https://github.com/nquest/micropython-st7565) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2018-02-14 - Driver for ST7565 128x64 LCDs.
* [micropython-st7920](https://github.com/ShrimpingIt/micropython-st7920) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2020-05-17 - Library for simple graphic primitives on ST7920 128x64 monochrome LCD panel using ESP8266 and SPI.
* [micropython-SHARP\_Memory\_Display](https://github.com/pramasoul/micropython-SHARP_Memory_Display) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2015-11-01 - MicroPython driver for SHARP memory display.
* [micropython-hx1230](https://github.com/mcauser/micropython-hx1230) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2020-12-05 - MicroPython library for HX1230 96x68 LCD modules.
* [MicroPython\_PCD8544](https://github.com/AnthonyKNorman/MicroPython_PCD8544) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2016-10-24 - ESP8266 driver for Nokia 5110 PCD8544.
* [micropython-lcd-AQM1248A](https://github.com/forester3/micropython-lcd-AQM1248A) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2018-07-11 - ESP8266 driver for AQM1248A graphic LCD.

#### LCD TFT

* [st7789\_mpy](https://github.com/russhughes/st7789_mpy) ⭐ 688 | 🐛 37 | 🌐 Python | 📅 2026-02-11 - Fast MicroPython driver for ST7789 display module written in C.
* [micropython-ili9341](https://github.com/rdagger/micropython-ili9341) ⭐ 288 | 🐛 3 | 🌐 Python | 📅 2025-03-02 - MicroPython ILI9341 display & XPT2046 touch screen driver.
* [MicroPython-ST7735](https://github.com/boochow/MicroPython-ST7735) ⭐ 267 | 🐛 9 | 🌐 Python | 📅 2022-12-30 - ESP32 version of GuyCarvers's ST7735 TFT LCD driver.
* [st7789py\_mpy](https://github.com/russhughes/st7789py_mpy) ⭐ 233 | 🐛 16 | 🌐 Python | 📅 2024-08-05 - Driver for 320x240, 240x240 and 135x240 ST7789 displays written in MicroPython.
* [st7789\_mpy](https://github.com/devbis/st7789_mpy) ⭐ 224 | 🐛 10 | 🌐 C | 📅 2024-01-23 - Fast pure-C driver for MicroPython that can handle display modules on ST7789 chip.
* [gc9a01\_mpy](https://github.com/russhughes/gc9a01_mpy) ⭐ 199 | 🐛 23 | 🌐 Python | 📅 2025-03-24 - Fast MicroPython driver for GC9A01 display modules written in C.
* [micropython-ili9341](https://github.com/jeffmer/micropython-ili9341) ⭐ 144 | 🐛 5 | 🌐 Python | 📅 2020-05-21 - MicroPython Driver for ILI9341 display.
* [s3lcd](https://github.com/russhughes/s3lcd) ⭐ 106 | 🐛 10 | 🌐 Python | 📅 2024-03-20 - ESP\_LCD based MicroPython driver for ESP32-S3 Devices with ST7789 or compatible displays.
* [st7789py\_mpy](https://github.com/devbis/st7789py_mpy) ⭐ 95 | 🐛 5 | 🌐 Python | 📅 2019-12-27 - Slow MicroPython driver for 240x240 ST7789 display without CS pin from AliExpress, written in MicroPython.
* [st7789s3\_mpy](https://github.com/russhughes/st7789s3_mpy) ⭐ 80 | 🐛 4 | 🌐 Python | 📅 2024-03-20 - MicroPython display driver for the TTGO T-Display-S3 ST7789 written in C.
* [ili9342c\_mpy](https://github.com/russhughes/ili9342c_mpy) ⭐ 59 | 🐛 3 | 🌐 Python | 📅 2024-03-20 - ILI9342C Fast 'C' Driver for MicroPython (M5Stack Core).
* [gc9a01py](https://github.com/russhughes/gc9a01py) ⭐ 57 | 🐛 7 | 🌐 Python | 📅 2021-05-06 - GC9A01 Display driver in MicroPython.
* [ST77xx-pure-MP](https://github.com/antirez/ST77xx-pure-MP) ⭐ 50 | 🐛 4 | 🌐 Python | 📅 2025-03-25 - Pure MicroPython driver for ST77xx displays. Low memory requirements.
* [st7735-esp8266-micropython](https://github.com/cheungbx/st7735-esp8266-micropython) ⭐ 35 | 🐛 2 | 🌐 Python | 📅 2020-07-13 - An ESP8266 MicroPython library for ST7735 160x80, 128x128, 128x160 TFT LCD displays.
* [SSD1963-TFT-Library-for-PyBoard-and-RP2040](https://github.com/robert-hh/SSD1963-TFT-Library-for-PyBoard-and-RP2040) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2021-04-02 - SSD1963 TFT Library for Pyboard and Raspberry Pi Pico.
* [MicroPython\_ST7735](https://github.com/AnthonyKNorman/MicroPython_ST7735) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2016-11-03 - Driver for ST7735 128x128 TFT.
* [micropython-st7735](https://github.com/hosaka/micropython-st7735) ⭐ 28 | 🐛 2 | 🌐 Python | 📅 2016-06-27 - Driver for ST7735 TFT LCDs.
* [st7789s3\_esp\_lcd](https://github.com/russhughes/st7789s3_esp_lcd) ⭐ 20 | 🐛 2 | 🌐 Python | 📅 2024-03-20 - Fast ESP\_LCD based MicroPython driver for the TTGO T-Display-S3 st7789 display written in C.
* [micropython-ili934x](https://github.com/tuupola/micropython-ili934x) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2018-02-16 - SPI driver for ILI934X series based TFT / LCD displays.
* [TTGO-ST7789-MicroPython](https://github.com/schumixmd/TTGO-ST7789-MicroPython) ⭐ 18 | 🐛 3 | 🌐 C | 📅 2025-09-22 - MicroPython ST7789 display driver for TTGO T-Display ESP32 CP2104 WiFi Bluetooth Module 1.14 Inch LCD.
* [wt32sc01py](https://github.com/russhughes/wt32sc01py) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2023-09-15 - WT32SC01 Plus MicroPython Display Driver.
* [micropython-ili9341](https://github.com/tkurbad/micropython-ili9341) ⚠️ Archived - ILI9341 TFT driver for MicroPython on ESP32.
* [t-display-s3](https://github.com/russhughes/t-display-s3) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2022-10-08 - MicroPython display driver for the TTGO T-Display-S3 ST7789 written in Python.
* [lvgl\_esp32\_gc9a01](https://github.com/minyiky/lvgl_esp32_gc9a01) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2021-05-26 - Driver for displays using the GC901 driver for use with LVGL MicroPython.
* [thmi\_py](https://github.com/russhughes/thmi_py) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2023-05-27 - MicroPython display driver for the LILYGO T-HMI written in Python.
* [upy-st7789](https://github.com/OneMadGypsy/upy-st7789) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2021-06-09 - A simple ST7789 driver written in MicroPython.
* [micropython-ili9341](https://github.com/mcauser/deshipu-micropython-ili9341) ⚠️ Archived - Collection of drivers for TFT displays, ILI9341, SH1106, SSD1606, ST7735.
* [st7735\_micropython](https://github.com/cheungbx/st7735_micropython) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2019-09-29 - ST7735 MicroPython drivers for 80x160, 128x128, 128x160 for ESP8266.
* [mp-ili9341](https://github.com/tkurbad/mp-ili9341) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2019-10-26 - MicroPython Driver for ILI9341 TFT Display.
* [ili934x-micropython](https://gitlab.com/mhepp63/ili934x-micropython) - Library for using ILI9341 display drivers with MicroPython.
* [micropython-st7735-esp8266](https://gitlab.com/mo_krauti/micropython-st7735-esp8266) - MicroPython driver for ST7735 TFT displays on the ESP8266.

#### LED Matrix

* [micropython-max7219](https://github.com/mcauser/micropython-max7219) ⭐ 205 | 🐛 8 | 🌐 Python | 📅 2019-07-03 - Driver for MAX7219 8x8 LED matrix modules.
* [micropython-max7219](https://github.com/vrialland/micropython-max7219) ⭐ 42 | 🐛 2 | 🌐 Python | 📅 2022-07-25 - MicroPython driver for MAX7219 8x8 LED matrix.
* [micropython-matrix8x8](https://github.com/JanBednarik/micropython-matrix8x8) ⭐ 15 | 🐛 4 | 🌐 Python | 📅 2024-03-09 - Driver for Adafruit 8x8 LED Matrix display with HT16K33 backpack.
* [micropython-ht1632c](https://github.com/vrialland/micropython-ht1632c) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2018-01-10 - Driver for HT1632C 32x16 bicolor LED matrix.
* [LED\_panel\_upy](https://github.com/CatMeowByte/LED_panel_upy) ⚠️ Archived - MicroPython driver module for Panel P10 32x16 Matrix display and its variants.
* [micropython-wemos-led-matrix-shield](https://github.com/mattytrentini/micropython-wemos-led-matrix) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - Driver for Wemos D1 Mini Matrix LED shield, using TM1640 chip.
* [MatrixDisplay](https://github.com/octaprog7/MatrixDisplay) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2022-11-29 - MicroPython module for work with MAX7219 LED matrix 8x8 display.

#### LED Segment

* [micropython-tm1637](https://github.com/mcauser/micropython-tm1637) ⭐ 225 | 🐛 5 | 🌐 Python | 📅 2023-07-04 - Driver for TM1637 quad 7-segment LED modules.
* [micropython-tm1638](https://github.com/mcauser/micropython-tm1638) ⭐ 36 | 🐛 4 | 🌐 Python | 📅 2023-06-15 - Driver for TM1638 dual quad 7-segment LED modules with switches.
* [max7219\_8digit](https://github.com/pdwerryhouse/max7219_8digit) ⭐ 24 | 🐛 4 | 🌐 Python | 📅 2023-03-18 - Driver for MAX7219 8-digit 7-segment LED modules.
* [micropython-tm1640](https://github.com/mcauser/micropython-tm1640) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2023-07-01 - Driver for TM1740 8x8 LED matrix modules.
* [micropython-my9221](https://github.com/mcauser/micropython-my9221) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2018-08-07 - Driver for MY9221 10-segment LED bar graph modules.
* [TM74HC595](https://github.com/Sakartu/TM74HC595) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2017-09-18 - Driver for shift register-controlled 5 pin display modules.
* [micropython-max7219](https://github.com/JulienBacquart/micropython-max7219) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2017-06-11 - Driver for MAX7219 8-digit 7-segment LED modules.
* [LKM1638](https://github.com/arikb/LKM1638) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2016-07-07 - Driver for JY-LKM1638 displays based on TM1638 controller.
* [micropython-hpdl1414](https://github.com/rdagger/micropython-hpdl1414) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-07-14 - MicroPython HPDL-1414 Display Driver.
* [micropython-sevenseg](https://github.com/kritishmohapatra/micropython-sevenseg) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-01-25 - Lightweight MicroPython library for single-digit 7-segment displays (common anode & cathode) with ESP32, ESP8266 and RP2040 support.
* [max7219\_8digit](https://github.com/GM-Script-Writer-62850/max7219_8digit) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-10-16 - MicroPython driver for the MAX7219 with 8 x 7-segment display.
* [micropython-tm1640](https://gitlab.com/robhamerling/micropython-tm1640) - MicroPython Library for 16 digits 7-segment displays controlled by a TM1640.
* [micropython-tm1638spi](https://gitlab.com/robhamerling/micropython-tm1638spi) - MicroPython Library for a popular board with 8 7-segment digits, 8 separate LEDs and 8 push buttons controlled by a TM1638.

#### LEDs

* [micropython-ws2812](https://github.com/JanBednarik/micropython-ws2812) ⭐ 198 | 🐛 3 | 🌐 Python | 📅 2023-02-05 - Driver for WS2812 RGB LEDs.
* [micropython-ht16k33](https://github.com/hybotix/micropython-ht16k33) ⭐ 47 | 🐛 1 | 🌐 Python | 📅 2022-05-26 - MicroPython driver for the HT16K33, a LED matrix, 7-Segment Numeric, and 14-Segment Alphanumeric display driver IC.
* [ws2812-SPI](https://github.com/nickovs/ws2812-SPI) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2020-10-30 - An efficient MicroPython WS2812 (NeoPixel) driver.
* [micropython\_fastled](https://github.com/kdschlosser/micropython_fastled) ⭐ 25 | 🐛 1 | 🌐 C++ | 📅 2020-08-18 - Port of FastLED to MicroPython.
* [micropython-dotstar](https://github.com/mattytrentini/micropython-dotstar) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - A MicroPython port of the Adafruit CircuitPython APA102/DotStar library.
* [micropython-rgbled](https://github.com/Warringer/micropython-rgbled) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2019-08-11 - This wrapper module aims to reduce the work needed to work with NeoPixel (WS2812) and DotStar (APA102) RGB LED strips and matrices.
* [micropython-morsecode](https://github.com/mampersat/micropython-morsecode) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-03-08 - Blink an LED with Morse Coded message.
* [micropython-p9813](https://github.com/mcauser/micropython-p9813) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2024-02-13 - Driver for P9813 RGB LED used in SeeedStudio's Grove chainable RGB LED.
* [tlc5940-micropython](https://github.com/oysols/tlc5940-micropython) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2017-02-15 - Driver for TLC5940 16 channel LED driver.
* [micropython-ws2801](https://github.com/HeMan/micropython-ws2801) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2019-09-27 - A MicroPython library to interface with strands of WS2801 RGB LEDs.
* [micropython-ws2812-7seg](https://github.com/HubertD/micropython-ws2812-7seg) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2017-11-03 - 7-segment display using WS2812 RGB LEDs.
* [IS31FL3197](https://github.com/omeErik/IS31FL3197) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-02-10 - I2C driver for the IS31FL3197 chip, found on the Arduino GIGA Display Shield.
* [micropython-aw210xx](https://github.com/eosti/micropython-aw210xx) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-10-31 - Driver for Awinic's AW210xx line of 8-bit LED drivers.
* [Official APA102](https://docs.micropython.org/en/latest/esp8266/quickref.html#apa102-driver) - ESP8266 APA102/DotStar RGB LED driver.
* [Official WS2811](https://docs.micropython.org/en/latest/esp8266/quickref.html#neopixel-driver) - ESP8266 WS2811/NeoPixel RGB LED driver.
* [tlc5947-rgb-micropython](https://gitlab.com/peterzuger/tlc5947-rgb-micropython) - Driver for the TLC5947 24 channel 12-bit PWM LED driver.
* [micropython-rgb-led-driver](https://gitlab.com/Athanaze/micropython-rgb-led-driver) - Tiny driver to control an RGB LED with PWM.

#### OLED

* [Official SSD1306](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/display/ssd1306) ⭐ 2,751 | 🐛 280 | 🌐 Python | 📅 2025-12-09 - Driver for SSD1306 128x64 OLED displays.
* [SH1106](https://github.com/robert-hh/SH1106) ⭐ 235 | 🐛 2 | 🌐 Python | 📅 2025-05-22 - Driver for the SH1106 OLED display.
* [micropython-ssd1351](https://github.com/rdagger/micropython-ssd1351) ⭐ 62 | 🐛 0 | 🌐 Python | 📅 2025-03-15 - Driver for SSD1351 OLED displays.
* [micropython-ssd1309](https://github.com/rdagger/micropython-ssd1309) ⭐ 52 | 🐛 3 | 🌐 Python | 📅 2025-02-11 - MicroPython SSD1309 Monochrome OLED Display Driver.
* [SH1107](https://github.com/peter-l5/SH1107) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2025-05-28 - Driver for SH1107 OLED displays (128x128 and 128x64 pixels).
* [micropython-ssd1327](https://github.com/mcauser/micropython-ssd1327) ⭐ 31 | 🐛 2 | 🌐 Python | 📅 2022-11-03 - Driver for SSD1327 128x128 4-bit greyscale OLED displays.
* [micropython-ssd1322](https://github.com/rdagger/micropython-ssd1322) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2024-09-29 - MicroPython display driver for SSD1322 grayscale OLED.
* [MicroPython\_SSD1306](https://github.com/AnthonyKNorman/MicroPython_SSD1306) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2016-10-24 - ESP8266 driver for SSD1306 OLED 128x64 displays.
* [sh1107-micropython](https://github.com/nemart69/sh1107-micropython) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2022-12-08 - MicroPython driver for SH1107-based OLED display (64x128).
* [micropython-oled](https://github.com/mcauser/deshipu-micropython-oled) ⚠️ Archived - Collection of drivers for monochrome OLED displays, PCD8544, SH1106, SSD1306, UC1701X.
* [Grove\_OLED](https://github.com/dda/MicroPython/blob/master/Grove_OLED.py) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2014-12-05 - Driver for SSD1327 used by SeeedStudio's Grove OLED Display 1.12" v1.0.
* [micropython-ssd1306](https://github.com/rdagger/micropython-ssd1306) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-07-10 - MicroPython SPI & I2C Display Driver for SSD1306 monochrome OLED.

#### Printer

* [micropython-thermal-printer](https://github.com/ayoy/micropython-thermal-printer) ⚠️ Archived - The MicroPython port of Python Thermal Printer by Adafruit.

### IO

#### ADC

* [ads1x15](https://github.com/robert-hh/ads1x15) ⭐ 111 | 🐛 3 | 🌐 Python | 📅 2025-09-17 - Driver for the ADS1015/ADS1115 ADC, I2C interface.
* [MicroPython-ADC\_Cal](https://github.com/matthias-bs/MicroPython-ADC_Cal) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2026-02-12 - ESP32 ADC driver using reference voltage calibration value from efuse.
* [micropython-ads1220](https://github.com/rdagger/micropython-ads1220) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2021-08-13 - MicroPython library for ADS1220 24-bit analog-to-digital converter.
* [CS1237](https://github.com/robert-hh/CS1237) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-08-08 - MicroPython driver for the CS1237 ADC.
* [Micropython\_ADS1115](https://github.com/AnthonyKNorman/Micropython_ADS1115) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2016-10-26 - ADS1115 16-bit ADC, 4 channels with programmable gain, I2C interface.
* [micropython-ads1219](https://github.com/miketeachman/micropython-ads1219) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2019-11-18 - MicroPython module for the Texas Instruments ADS1219 ADC.
* [MCP342x\_LoPy](https://github.com/jajberni/MCP342x_LoPy) ⭐ 3 | 🐛 3 | 🌐 Python | 📅 2023-09-18 - MicroPython driver for the MCP342x ADC.
* [PCF8591\_micropython\_library](https://github.com/xreef/PCF8591_micropython_library) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - MicroPython library for PCF8591 8-bit ADC/DAC.
* [ADS1256](https://github.com/robert-hh/ADS1256) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-08-22 - Driver for the ADS1256 24-bit low noise ADC, both as a generic MicroPython version and using the RP2040/RP2350 PIO.
* [micropython-ads1015](https://github.com/mcauser/deshipu-micropython-ads1015) ⚠️ Archived - ADS1015 12-Bit and ADS1115 16-bit ADC, 4 channels with programmable gain, I2C interface.
* [ADS7818](https://github.com/robert-hh/ADS7818) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - Python class interfacing the ADS7818 AD-converter.
* [ads1115](https://github.com/octaprog7/ads1115) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-12-01 - MicroPython module for managing ADS1115, multichannel, differential I2C ADC from TI.
* [mcp3421](https://github.com/octaprog7/mcp3421) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-09-04 - MicroPython module for controlling MCP342X, 18-bit analog-to-digital converter with I2C interface.
* [micropython-MCP3001](https://github.com/scruss/micropython-MCP3001) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-11-06 - MicroPython driver for the MCP3001 1-channel 10-bit ADC with SPI interface.
* [micropython-pcf8591](https://gitlab.com/cediddi/micropython-pcf8591) - MicroPython driver for PCF8591 ADC/DAC, I2C interface.

#### DAC

* [micropython-mcp4725](https://github.com/wayoda/micropython-mcp4725) ⭐ 12 | 🐛 2 | 🌐 Python | 📅 2016-09-06 - Driver for the MCP4725 I2C DAC.
* [mcp4728](https://github.com/openfablab/mcp4728) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2020-07-01 - Helper library for the Microchip MCP4728 I2C 12-bit Quad DAC.
* [mpyDAC](https://github.com/octaprog7/mpyDAC) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-11-08 - MicroPython module for controlling MCP4725, 12-bit digital analog converter (CAP) with EEPROM memory.

#### GPIO

* [micropython-inputs](https://github.com/alanmitchell/micropython-inputs) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2015-04-20 - Classes to count pulses, debounce digital inputs, and calculate moving averages of analog inputs for a MicroPython board.
* [micropython-debounce-switch](https://github.com/selfhostedhome/micropython-debounce-switch) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2018-09-17 - MicroPython Class for Debouncing Switches.
* [ubutton](https://gitlab.com/WiLED-Project/ubutton) - A MicroPython library for controlling reading and debouncing pushbutton inputs, including "short" and "long" press callbacks.

#### IO-Expander

* [micropython-mcp23017](https://github.com/mcauser/micropython-mcp23017) ⭐ 87 | 🐛 5 | 🌐 Python | 📅 2024-02-05 - MicroPython driver for MCP23017 16-bit I/O Expander.
* [micropython-pcf8574](https://github.com/mcauser/micropython-pcf8574) ⭐ 43 | 🐛 0 | 🌐 Python | 📅 2024-02-11 - MicroPython driver for PCF8574 8-Bit I2C I/O Expander with Interrupt.
* [micropython-mcp230xx](https://github.com/ShrimpingIt/micropython-mcp230xx) ⭐ 31 | 🐛 5 | 🌐 Python | 📅 2021-10-21 - Driver for MCP23017 and MCP23008 GPIO expanders.
* [micropython-pcf8575](https://github.com/mcauser/micropython-pcf8575) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2024-02-11 - MicroPython driver for PCF8575 16-Bit I2C I/O Expander with Interrupt.
* [ESP8266\_MCP23S17](https://github.com/AnthonyKNorman/ESP8266_MCP23S17) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2017-10-11 - MicroPython library for using the MCP23S17 16-bit I/O expander with the ESP8266.
* [micropython-sx1509](https://github.com/rdagger/micropython-sx1509) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-05-21 - MicroPython SX1509 I/O Expander Library.
* [micropython-mcp230xx](https://github.com/dsiggi/micropython-mcp230xx) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2021-10-21 - Driver for MCP23017 and MCP23008 GPIO expanders, extended with interrupt handling.
* [pcf8574](https://github.com/octaprog7/pcf8574) ⚠️ Archived - MicroPython module for working with the PCF8574(A) I2C 8-bit I/O expander from NXP.
* [mcp23017](https://github.com/octaprog7/mcp23017) ⚠️ Archived - MicroPython module for MCP23017, 16-Bit I/O Expander with Serial Interface.

#### Joystick

* [esp32-microgamepad-ble](https://github.com/insighio/esp32-microgamepad-ble) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2020-12-03 - Dual analog joystick on ESP32 over BLE (Nordic UART Service - NUS) using MicroPython.
* [micropython-nunchuck](https://github.com/kfricke/micropython-nunchuck) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2016-11-21 - Driver for Nunchuk game controller, I2C interface.
* [Micropython\_Joystick](https://github.com/cnadler86/Micropython_Joystick) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2025-01-25 - A simple and fast library for joysticks over ADC.
* [micropython-joystick-2-unit](https://github.com/HowManyOliversAreThere/micropython-joystick-2-unit) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-01-27 - Driver for the [M5Stack Joystick 2 Unit](https://docs.m5stack.com/en/unit/Unit-JoyStick2).

#### Keyboard

* [pico-rgbkeypad](https://github.com/martinohanlon/pico-rgbkeypad) ⭐ 71 | 🐛 1 | 🌐 Python | 📅 2022-01-09 - A Python class for controlling the Pimoroni RGB Keypad for Raspberry Pi Pico.
* [micropython-keyboard](https://github.com/mcameron/micropython-keyboard) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2017-11-22 - 47 key keyboard running on a MicroPython Pyboard.
* [MicroPython-SimpleKeypad](https://github.com/PerfecXX/MicroPython-SimpleKeypad) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2025-06-03 - MicroPython library for interfacing with a keypad matrix.
* [micropython-aiobutton](https://github.com/jacklinquan/micropython-aiobutton) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2020-09-18 - A MicroPython module for asyncio button.

#### Multiplexer

* [micropython-tca9548a](https://github.com/mcauser/micropython-tca9548a) ⭐ 16 | 🐛 0 | 📅 2020-09-27 - MicroPython examples using TCA9548A I2C multiplexer.
* [tca9548a](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/tca9548a.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - MicroPython driver for the TCA9548A I2C multiplexer.

#### Potentiometers

* [mcp4131](https://github.com/scruss/mcp4131) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-10-06 - MicroPython module to control MicroChip's MCP4131 SPI digital potentiometer.
* [micropython-ad840x](https://github.com/dsiggi/micropython-ad840x) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-05-30 - MicroPython SPI-based manipulation of the AD series digital potentiometers AD8400, AD8402 and AD8403.
* [MicroPython\_DS1841](https://github.com/jposada202020/MicroPython_DS1841) ⚠️ Archived - MicroPython Driver for the DS1841 Potentiometer.
* [MicroPython\_DS3502](https://github.com/jposada202020/MicroPython_DS3502) ⚠️ Archived - MicroPython Driver for the DS3502 Potentiometer.

#### Power Management

* [AXP202\_PythonLibrary](https://github.com/lewisxhe/AXP202_PythonLibrary) ⚠️ Archived - MicroPython AXP202 Library.
* [micropython\_hourly\_sleeper\_library](https://github.com/costastf/micropython_hourly_sleeper_library) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2017-06-20 - A MicroPython library that enables an ESP8266 to sleep for hourly increments for a setup amount of hours.

#### PWM

* [upwmcontroller](https://gitlab.com/WiLED-Project/upwmcontroller) - A MicroPython library for controlling PWM outputs in an asyncio loop, with features including fading and blinking.

#### Relay

* [micropython-xl9535-kxv5-relay](https://github.com/mcauser/micropython-xl9535-kxv5-relay) ⭐ 13 | 🐛 2 | 🌐 Python | 📅 2024-02-04 - A MicroPython library for jxl XL9535-KxV5 I2C relay boards.

#### Rotary Encoder

* [asynchronous encoder driver](https://github.com/peterhinch/micropython-async/blob/master/v3/primitives/encoder.py) ⭐ 816 | 🐛 4 | 🌐 Python | 📅 2026-01-30 - Interface an encoder to uasyncio code.
* [encoders](https://github.com/peterhinch/micropython-samples/blob/master/encoders/ENCODERS.md) ⭐ 523 | 🐛 13 | 🌐 Python | 📅 2025-09-14 - Short document explaining issues around encoder technology.
* [micropython-rotary](https://github.com/miketeachman/micropython-rotary) ⭐ 333 | 🐛 17 | 🌐 Python | 📅 2024-04-30 - MicroPython module to read a rotary encoder.
* [encodermenu](https://github.com/sgall17a/encodermenu) ⭐ 117 | 🐛 2 | 🌐 Python | 📅 2021-04-08 - Simple GUI menu for MicroPython using a rotary encoder and basic display.
* [AS5600](https://github.com/sgall17a/AS5600) ⭐ 40 | 🐛 4 | 🌐 Python | 📅 2025-10-05 - AS5600 MicroPython library for reading this magnetic sensor.
* [rotary-encoder](https://github.com/gurgleapps/rotary-encoder) ⭐ 30 | 🐛 2 | 🌐 Python | 📅 2023-09-14 - MicroPython code to drive a KY-040 rotary encoder.
* [encoderLib](https://github.com/BramRausch/encoderLib) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2016-08-28 - MicroPython library to handle a rotary encoder.
* [micropython-quiic-twist](https://github.com/rdagger/micropython-quiic-twist) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2021-08-15 - MicroPython Driver for Quiic Twist RGB Rotary Encoder.
* [AS5600](https://github.com/octaprog7/AS5600) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-01-22 - MicroPython module for controlling single-turn magnetic encoder AS5600.
* [micropython-encoder-knob](https://github.com/infinite-tree/micropython-encoder-knob) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2021-02-15 - A very simple lightweight encoder knob library with button support.
* [micropython-8encoder](https://github.com/HowManyOliversAreThere/micropython-8encoder) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-07-12 - Driver for the I2C [M5Stack 8-Encoder Unit](https://shop.m5stack.com/products/8-encoder-unit-stm32f030).
* [uencoder](https://gitlab.com/WiLED-Project/uencoder) - A MicroPython library for reading from a rotary encoder.

#### Shift Registers

* [micropython-74hc595](https://github.com/mcauser/micropython-74hc595) ⭐ 38 | 🐛 3 | 🌐 Python | 📅 2025-04-27 - MicroPython driver for 74HC595 8-bit shift registers.
* [MicroPython-SN74HCS264](https://gitlab.com/olivierlenoir/MicroPython-SN74HCS264) - MicroPython Driver for SN74HCS264 8-Bit Parallel-Out Serial Shift Registers With Schmitt-Trigger Inputs and Inverted Outputs.

#### Waveform Generator

* [Signal\_Generators](https://github.com/Wei1234c/Signal_Generators) ⭐ 24 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-03-12 - Signal generators (AD9833, AD9834, AD9850, ADF4351) toolbox.
* [Micropython-AD9833](https://github.com/KipCrossing/Micropython-AD9833) ⭐ 19 | 🐛 2 | 🌐 Python | 📅 2019-05-18 - Pyboard driver for AD9833, SPI interface.
* [AD9833-MicroPython-Module](https://github.com/owainm713/AD9833-MicroPython-Module) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2025-06-28 - MicroPython module to use the AD9833 programmable waveform generator.
* [Clock\_Generators](https://github.com/Wei1234c/Clock_Generators) ⭐ 8 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-02-14 - Clock generators (Si5351 for now) toolbox.
* [pico-wave-vibration-generator](https://github.com/gurgleapps/pico-wave-vibration-generator) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-03-29 - A MicroPython-based frequency generator for Raspberry Pi Pico designed to create vibrations on solenoids or speakers, enabling wave experimentation and exploration at home.
* [micropython-m5stack-dds](https://github.com/mattytrentini/micropython-m5stack-dds) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - MicroPython driver for the M5Stack DDS frequency generator.

### Mathematics

* [Sun and Moon](https://github.com/peterhinch/micropython-samples/blob/master/astronomy/README.md) ⭐ 523 | 🐛 13 | 🌐 Python | 📅 2025-09-14 - Determine Sun and Moon rise and set times, Moon phases.
* [micropython-ulab](https://github.com/v923z/micropython-ulab) ⭐ 491 | 🐛 50 | 🌐 C | 📅 2025-10-08 - A NumPy-like fast vector module for MicroPython.
* [micropython-fourier](https://github.com/peterhinch/micropython-fourier) ⭐ 92 | 🐛 0 | 🌐 Python | 📅 2025-10-31 - Fast Fourier transform in MicroPython's inline ARM assembler.
* [Filters](https://github.com/peterhinch/micropython-filters) ⭐ 71 | 🐛 3 | 🌐 Python | 📅 2022-01-26 - FIR filters using ARM Thumb assembler. Using an online utility you can go from a graph of required frequency response to a filter implementation.
* [ulinalg](https://github.com/jalawson/ulinalg) ⭐ 32 | 🐛 2 | 🌐 Python | 📅 2019-03-22 - Small size matrix handling module with a few linear algebra operations specifically for MicroPython (Python 3).
* [uMath](https://github.com/albaEDA/uMath) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2017-02-27 - Computer Algebra for microcontrollers.
* [umatrix](https://github.com/iyassou/umatrix) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2022-02-14 - A matrix library for the MicroPython language.
* [MicroPython\_Statistics](https://github.com/rcolistete/MicroPython_Statistics) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2018-10-26 - Statistics module for MicroPython.
* [micropython-npyfile](https://github.com/jonnor/micropython-npyfile/) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2025-11-30 - Numpy .npy file support for MicroPython, supports read/write/streaming.
* [uumpy](https://github.com/nickovs/uumpy) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2024-08-29 - A subset of NumPy for MicroPython.
* [micropython-fractions](https://github.com/mattytrentini/micropython-fractions) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - A MicroPython port of the CPython standard Fractions library.
* [Micropython Perlin](https://github.com/sjaak31367/micropython_perlin) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2024-09-11 - A Perlin noise generator module.
* [upyuncertainties](https://github.com/rcolistete/upyuncertainties) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2020-03-08 - Uncertainty calculations for MicroPython.
* [micropython-mtx](https://gitlab.com/nickoala/micropython-mtx) - Fast Matrix Multiplication and Linear Solver on MicroPython.
* [micropython-vec](https://gitlab.com/nickoala/micropython-vec) - Vector Operations on MicroPython.
* [MicroPython-Matrix](https://gitlab.com/olivierlenoir/MicroPython-Matrix) - MicroPython basic matrix operations.

### Motion

* [MicroPython Motor Kit](https://github.com/cnadler86/MicroPython_Motor) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-01-02 - General motor control libraries.

#### DC Motor

* [MicroPython-L298](https://gitlab.com/olivierlenoir/MicroPython-L298) - Drive L298 dual H-bridge with MicroPython.
* [pyl298](https://github.com/marcio-pessoa/pyl298) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2019-12-09 - Driver for the L298 dual full-bridge motor controller.

#### Servo

* [micropython-servo](https://github.com/redoxcode/micropython-servo) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2025-11-16 - Library to control RC servos using direct PWM output in a tidy way.
* [MicroPython\_PCA9685](https://github.com/jposada202020/MicroPython_PCA9685) ⚠️ Archived - MicroPython Driver for the PCA9685 PWM control IC, commonly used to control servos, LEDs and motors.
* [micropython-pca9685](https://github.com/mcauser/deshipu-micropython-pca9685) ⚠️ Archived - 16-channel 12-bit PWM/servo driver.
* [MicroPython\_MOTOR](https://github.com/jposada202020/MicroPython_MOTOR) ⚠️ Archived - MicroPython Helper for controlling PWM based motors.
* [pca9685](https://github.com/octaprog7/pca9685) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-02-24 - MicroPython module for managing a 16-channel SHIM controller, PCA9685

#### Stepper

* [micropython-upybbot](https://github.com/jeffmer/micropython-upybbot) ⭐ 92 | 🐛 0 | 🌐 Python | 📅 2015-05-14 - A4988 driver for bipolar stepper motors.
* [uln2003](https://github.com/IDWizard/uln2003) ⭐ 49 | 🐛 1 | 🌐 Python | 📅 2017-07-29 - Driver for 5V 28BYJ-48 stepper motors.
* [AccelStepper-MicroPython](https://github.com/pedromneto97/AccelStepper-MicroPython) ⭐ 45 | 🐛 3 | 🌐 Python | 📅 2019-04-16 - AccelStepper Library for MicroPython - ESP32.
* [micropython-stepper](https://github.com/redoxcode/micropython-stepper) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2025-11-16 - Library to control common stepper drivers in a tidy way.
* [ticlib](https://github.com/jphalip/ticlib) ⭐ 21 | 🐛 4 | 🌐 Python | 📅 2025-04-19 - Driver for Pololu Tic stepper motor controllers.
* [uPySteppers](https://github.com/lemariva/uPySteppers) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2020-05-31 - DIY rotating platform using an ESP32 connected to WiFi.
* [micropython-stepper-motor](https://github.com/larsks/micropython-stepper-motor) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-01-14 - Drive a 28BYJ-48 motor attached to a ULN2003 driver.
* [pystepper](https://github.com/marcio-pessoa/pystepper) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2019-12-10 - MicroPython Stepper Motor Sequence Control.
* [microPython\_TMC5160](https://github.com/capella-ben/microPython_TMC5160) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2021-12-22 - A MicroPython library for the Trinamic TMC5160 Motion Controller.
* [microPython\_AMIS-30543](https://github.com/capella-ben/microPython_AMIS-30543) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2021-09-04 - MicroPython library for Stepper Driver control using AMIS-30543 driver.
* [micropython-multiaxis](https://gitlab.com/olivierlenoir/micropython-multiaxis) - Multiaxis with MicroPython ESP32 and DRV8825.
* [micropython-drv8825](https://gitlab.com/robhamerling/micropython-drv8825) - Driver and example in MicroPython to control a stepper motor via a DRV8825 controller board.

### Sensors

#### Accelerometer Digital

* [MicroPython-LIS3DH](https://github.com/tinypico/tinypico-micropython/tree/master/lis3dh%20library) ⭐ 69 | 🐛 2 | 🌐 Python | 📅 2022-10-28 - I2C driver for LIS3DH 3-axis accelerometer.
* [ADXL345\_spi\_micropython](https://github.com/AlekseyFedorovich/ADXL345_spi_micropython) ⭐ 20 | 🐛 3 | 🌐 Python | 📅 2024-08-19 - Library for interacting through the SPI protocol with an 'Analog Devices ADXL345' accelerometer from an MCU flashed with MicroPython.
* [micropython-lis2hh12](https://github.com/tuupola/micropython-lis2hh12) ⭐ 11 | 🐛 3 | 🌐 Python | 📅 2024-02-23 - I2C driver for LIS2HH12 3-axis accelerometer.
* [bma423-pure-mp](https://github.com/antirez/bma423-pure-mp) ⭐ 10 | 🐛 6 | 🌐 Python | 📅 2024-04-06 - MicroPython Driver for the Bosch 423 accelerometer. Includes FIFO support. ⏩
* [adxl345\_micropython](https://github.com/fanday/adxl345_micropython) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2017-09-13 - Driver for ADXL345 16g 3-axis accelerometer.
* [msa301-micropython-driver](https://github.com/wojciech-szmyt/msa301-micropython-driver) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-06-02 - Homebrew MicroPython driver for MSA301 3-axis accelerometer. Tested on Raspberry Pico.
* [MMA7660](https://github.com/Bucknalla/MicroPython-3-Axis-Accelerometer/blob/master/MMA7660.py) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2017-01-16 - Driver for MMA7660 1.5g 3-axis accelerometer.
* [MicroPython\_LIS3DH](https://github.com/jposada202020/MicroPython_LIS3DH) ⚠️ Archived - MicroPython Driver for the LIS3DH 3-axis accelerometer.
* [MicroPython\_KX132](https://github.com/jposada202020/MicroPython_KX132) ⚠️ Archived - MicroPython Driver for the Kionix KX132 Accelerometer.
* [MicroPython\_QMC5883L](https://github.com/jposada202020/MicroPython_QMC5883L) ⚠️ Archived - MicroPython Driver for the QMC5883L Accelerometer.
* [MicroPython\_MMA8451](https://github.com/jposada202020/MicroPython_MMA8451) ⚠️ Archived - MicroPython module for the MMA8451 3-axis accelerometer.
* [ADXL345-with-Pyboard](https://github.com/AbhinayBandaru/ADXL345-with-Pyboard) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2016-04-22 - Driver for ADXL345 16g 3-axis accelerometer.
* [MicroPython\_ADXL343](https://github.com/jposada202020/MicroPython_ADXL343) ⚠️ Archived - MicroPython Driver for the Analog Devices ADXL343 Accelerometer.
* [MicroPython\_BMA220](https://github.com/jposada202020/MicroPython_BMA220) ⚠️ Archived - MicroPython Driver for the Bosch BMA220 Accelerometer.
* [MicroPython\_BMA400](https://github.com/jposada202020/MicroPython_BMA400) ⚠️ Archived - MicroPython Driver for the Bosch BMA400 Accelerometer.
* [MicroPython\_H3LIS200DL](https://github.com/jposada202020/MicroPython_H3LIS200DL) ⚠️ Archived - MicroPython Driver for the ST H3LIS200DL Accelerometer.
* [Micropython\_MC3479](https://github.com/jposada202020/Micropython_MC3479) ⚠️ Archived - MicroPython Driver for the MC3479 Accelerometer.
* [MicroPython\_MMA8452Q](https://github.com/jposada202020/MicroPython_MMA8452Q) ⚠️ Archived - MicroPython Driver for the NXP MMA8452Q Accelerometer.

#### Air Quality

* [micropython-pms7003](https://github.com/pkucmus/micropython-pms7003) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2021-12-08 - MicroPython driver for the PMS7003 Air Quality Sensor.
* [upython-aq-monitor](https://github.com/ayoy/upython-aq-monitor) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2020-05-30 - Air Quality monitor using PMS5003 sensor and WiPy.
* [pms5003\_micropython](https://github.com/kevinkk525/pms5003_micropython) ⭐ 25 | 🐛 4 | 🌐 Python | 📅 2021-11-06 - Driver for PMS5003 air quality sensor for MicroPython.
* [polly](https://github.com/g-sam/polly) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2017-07-11 - SDS011 pollution sensor + Wemos D1 mini pro + MicroPython.
* [micropython-pms5003-minimal](https://github.com/miketeachman/micropython-pms5003-minimal) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2019-11-15 - Driver for P air quality sensor for MicroPython.
* [CCS811](https://github.com/Ledbelly2142/CCS811) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2018-01-04 - CCS811 Air Quality Sensor.
* [micropython-SNGCJA5](https://github.com/aleppax/micropython-SNGCJA5) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-01-13 - MicroPython driver for Panasonic SN-GCJA5 particulate matter (PM) sensor.

#### Barometer - Air and Water Pressure

* [BME280](https://github.com/robert-hh/BME280) ⭐ 127 | 🐛 2 | 🌐 Python | 📅 2025-06-15 - MicroPython driver for the BME280 sensor, target platform Pycom devices.
* [micropython-bmp280](https://github.com/dafvid/micropython-bmp280) ⭐ 114 | 🐛 4 | 🌐 Python | 📅 2023-11-18 - Module for the BMP280 sensor.
* [micropython-bmp180](https://github.com/micropython-IMU/micropython-bmp180) ⭐ 90 | 🐛 6 | 🌐 Python | 📅 2021-12-24 - Driver for Bosch BMP180 temperature, pressure and altitude sensor.
* [mpy\_bme280\_esp8266](https://github.com/catdog2/mpy_bme280_esp8266) ⭐ 74 | 🐛 5 | 🌐 Python | 📅 2021-05-22 - Bosch BME280 temperature/pressure/humidity sensor.
* [micropython\_bme280\_i2c](https://github.com/triplepoint/micropython_bme280_i2c) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2018-09-06 - A MicroPython module for communicating with the Bosch BME280 temperature, humidity, and pressure sensor.
* [MicroPython-BMPxxx](https://github.com/bradcar/MicroPython_BMPxxx) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-10-23 - Driver for BMP585, BMP581, BMP390, BMP280 Bosch temperature/pressure sensors.
* [MicroPython-BME280](https://github.com/neliogodoi/MicroPython-BME280) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2019-03-10 - Driver to digital sensor of Temperature, Pressure and Humidity.
* [mp-bmp3xx-full](https://github.com/jornamon/mp-bmp3xx-full) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-11-20 - MicroPython driver for the Bosch BMP3xx range of barometric pressure sensors. Includes FIFO support. ⏩
* [micropython-bme280](https://github.com/kevbu/micropython-bme280) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2020-12-13 - Driver for the Bosch BME280 temperature/pressure/humidity sensor.
* [MPL3115A2\_MicroPython](https://github.com/PinsonJonas/MPL3115A2_MicroPython) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-05-26 - MicroPython library for the MPL3115A2 altimeter.
* [ms5803-micropython](https://github.com/minyiky/ms5803-micropython) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2021-02-09 - A MicroPython implementation of the driver for an MS5803 air/water pressure & temperature sensor.
* [BMP390](https://github.com/octaprog7/BMP390) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-10-17 - MicroPython module for BMP390 pressure & temperature sensor.
* [BMP180](https://github.com/octaprog7/BMP180) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-11-07 - MicroPython module for BMP180 pressure & temperature sensor.
* [D6F-PH](https://github.com/ekspla/D6F-PH) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-02-04 - MicroPython module for differential pressure sensor, D6F-PH (OMRON).
* [bmp581](https://github.com/octaprog7/bmp581) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-06-08 - MicroPython module for BMP581, pressure and ambient temperature sensor from Bosch Sensortec.
* [MicroPython\_DPS310](https://github.com/jposada202020/MicroPython_DPS310) ⚠️ Archived - MicroPython Driver for the DPS310 Sensor. (Archived)
* [MicroPython\_ICP10111](https://github.com/jposada202020/MicroPython_ICP10111) ⚠️ Archived - MicroPython Driver for the TDK ICP-10111 Barometric Pressure and Temperature sensor. (Archived)
* [MicroPython\_BMP581](https://github.com/jposada202020/MicroPython_BMP581) ⚠️ Archived - MicroPython driver for the Bosch BMP581 pressure & temperature sensor. (Archived)
* [MicroPython\_MMR902](https://github.com/jposada202020/MicroPython_MMR902) ⚠️ Archived - MicroPython Driver for the Mitsumi MMR902 Micro Pressure Sensor. (Archived)
* [MicroPython\_MPL3115A2](https://github.com/jposada202020/MicroPython_MPL3115A2) ⚠️ Archived - MicroPython driver for the NXP MPL3115A2 Pressure and Temperature sensor. (Archived)
* [MicroPython\_MS5611](https://github.com/jposada202020/MicroPython_MS5611) ⚠️ Archived - MicroPython Driver for the TE MS5611 Pressure and Temperature Sensor. (Archived)
* [micropython-bmp180](https://gitlab.com/flowolf/micropython-bmp180) - A module for MicroPython which provides a class for the BMP180 pressure sensor.

#### Battery

* [Micropython-LC709203F](https://github.com/scopelemanuele/Micropython-LC709203F) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2019-12-22 - A simple MicroPython library for LC709293F Fuel Gauge.

#### Biometric

* [MAX30102-MicroPython-driver](https://github.com/n-elia/MAX30102-MicroPython-driver) ⭐ 83 | 🐛 0 | 🌐 Python | 📅 2024-04-10 - A MAX30102 driver ported to MicroPython. It should also work for MAX30105.
* [micropython-fingerprint](https://github.com/chrisb2/micropython-fingerprint) ⭐ 20 | 🐛 3 | 🌐 Python | 📅 2020-05-01 - MicroPython library for reading Grow and ZhianTec fingerprint sensors.
* [max30102](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/max30102.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - MicroPython driver for the MAX30102, with heartbeat detection and BPM measurement.

#### Camera

* [micropython-camera-driver](https://github.com/lemariva/micropython-camera-driver) ⭐ 551 | 🐛 34 | 🌐 C | 📅 2023-10-22 - OV2640 camera driver for MicroPython on ESP32.
* [uPyCam](https://github.com/lemariva/uPyCam) ⭐ 164 | 🐛 11 | 🌐 Python | 📅 2022-02-02 - Take a photo with an ESP32-CAM running MicroPython.
* [micropython-camera-API](https://github.com/cnadler86/micropython-camera-API) ⭐ 139 | 🐛 1 | 🌐 C | 📅 2026-01-12 - Project with the aim of supporting cameras across various ports in MicroPython, starting with the ESP32 port and Omnivision cameras (OV2640 & OV5640).
* [micropython-ov2640](https://github.com/namato/micropython-ov2640) ⭐ 121 | 🐛 8 | 🌐 Python | 📅 2022-10-05 - MicroPython class for OV2640 camera.
* [esp32-cam-micropython](https://github.com/shariltumin/esp32-cam-micropython) ⭐ 95 | 🐛 11 | 🌐 Makefile | 📅 2022-06-13 - MicroPython ESP32-CAM.
* [IoTy huskylib](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/huskylib.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - MicroPython driver for the DFRobot Husky Lens. An easy-to-use AI Camera / Vision Sensor, featuring face recognition, object tracking, object recognition, line tracking, color recognition, and QR code recognition.
* [IoTy mv](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/mv.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - A simple machine vision library that provides blob and circle detection.
* [MQTT-Cam](https://github.com/jono-allen/MQTT-Cam) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2020-04-05 - ESP32-CAM MicroPython MQTT AWS S3 Uploader.
* [OV2640\_uPy](https://github.com/FunPythonEC/OV2640_uPy) ⭐ 9 | 🐛 3 | 🌐 Python | 📅 2019-04-26 - OV2640 camera library for MicroPython.
* [Nikon-Trigger-for-MicroPython](https://github.com/Thekegman/Nikon-Trigger-for-MicroPython) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2018-07-01 - Remote trigger for a Nikon camera using an IR LED. For Pyboard v1.1.

#### Colour

* [micropython-gy33](https://github.com/QuirkyCort/micropython-gy33) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-04-22 - UART and I2C drivers for GY-33 module (TCS3472 color sensor).
* [TCS3200-MicroPython](https://github.com/uraich/TCS3200-MicroPython) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2022-06-28 - A MicroPython driver and test programs for the TCS3200 color sensor.
* [veml6040](https://github.com/octaprog7/veml6040) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-02-10 - MicroPython module for managing a color sensor RGBW, VEML6040 from Vishay.
* [MicroPython\_ISL29125](https://github.com/jposada202020/MicroPython_ISL29125) ⚠️ Archived - MicroPython Driver for the Intersil ISL29125 Color Sensor.
* [MicroPython\_TCS3430](https://github.com/jposada202020/MicroPython_TCS3430) ⚠️ Archived - MicroPython driver for the AMS TCS3430 Color and ALS sensor.
* [micropython-tcs34725](https://gitlab.com/robhamerling/micropython-tcs34725) - Driver class for TCS34725 and TCS34727 color sensors.
* [micropython-as7341](https://gitlab.com/robhamerling/micropython-as7341) - MicroPython library for AS7341.

#### Compass

* [micropython-esp8266-hmc5883l](https://github.com/gvalkov/micropython-esp8266-hmc5883l) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2024-09-07 - 3-axis digital compass on the ESP8266.
* [QMC5883](https://github.com/robert-hh/QMC5883) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2025-05-21 - Python class for the QMC5883 Three-Axis Digital Compass IC.
* [microPython\_AS5600L](https://github.com/capella-ben/microPython_AS5600L) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2021-09-04 - MicroPython driver for AS5600L magnet rotary position sensor.
* [QMC5883](https://github.com/octaprog7/QMC5883) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2023-10-11 - MicroPython module for control QMC5883L geomagnetic sensor.

#### Current

* [pyb\_ina219](https://github.com/chrisb2/pyb_ina219) ⭐ 63 | 🐛 3 | 🌐 Python | 📅 2023-08-05 - Driver for INA219 current sensor.
* [TI\_INA226\_micropython](https://github.com/elschopi/TI_INA226_micropython) ⭐ 39 | 🐛 3 | 🌐 Python | 📅 2022-03-26 - MicroPython driver for Texas Instruments INA226 power measuring IC.
* [INA219](https://github.com/robert-hh/INA219) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2025-05-22 - INA219 MicroPython driver.
* [micropythonINA219](https://github.com/kabel42/micropythonINA219) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2017-11-04 - Driver for INA219 current sensor.
* [INA\_TI](https://github.com/octaprog7/INA_TI) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-06-08 - MicroPython module for controlling INA219, INA226 - A two-directional current / power monitor with the I2C interface.
* [micropython-current-monitor](https://gitlab.com/n.rj.powers/micropython-current-monitor) - Current monitor using the INA219 and an SSD1306 OLED.

#### Distance IR

* [GP2Y0A21YK](https://github.com/basanovase/GP2Y0A21YK) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-09-14 - GP2Y0A21YK MicroPython library.
* [micropython-gp2y0e03](https://github.com/mcauser/deshipu-micropython-gp2y0e03) ⚠️ Archived - IR-LED distance measuring sensor using Sharp GP2Y0E03.
* [micropython-vl6180](https://github.com/mcauser/deshipu-micropython-vl6180) ⚠️ Archived - Time-of-Flight sensor, ambient light sensor & IR emitter.

#### Distance Laser

* [VL53L0X](https://github.com/uceeatz/VL53L0X) ⭐ 48 | 🐛 9 | 🌐 Python | 📅 2022-04-24 - MicroPython Library for LiDAR Sensor VL53L0X.
* [vl53l1x\_pico](https://github.com/drakxtwo/vl53l1x_pico) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2021-04-08 - MicroPython driver for the VL53L1X ToF sensor.
* [vl53l5cx](https://github.com/mp-extras/vl53l5cx) ⭐ 21 | 🐛 8 | 🌐 Python | 📅 2024-05-10 - MicroPython and CircuitPython Package for the [VL53L5CX](https://www.st.com/en/imaging-and-photonics-solutions/vl53l5cx.html) (4x4/8x8 ToF sensor array).
* [vl53l1x](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/vl53l1x.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - MicroPython driver for the VL53L1X ToF sensor.
* [IoTy lds02rr](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/lds02rr.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - Driver for the LDS02RR 360 degree LiDAR.
* [IoTy coind4](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/coind4.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - Driver for the COIN-D4 360 degree LiDAR.
* [IoTy delta2d](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/delta2d.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - Driver for the Delta-2D 360 degree LiDAR.
* [tf-luna-micropython](https://github.com/davmoz/tf-luna-micropython) ⭐ 13 | 🐛 4 | 🌐 Python | 📅 2026-01-14 - A simple MicroPython I2C library for TF-Luna LiDAR Module.
* [VL6180X](https://github.com/Ledbelly2142/VL6180X) ⭐ 9 | 🐛 5 | 🌐 Python | 📅 2020-10-14 - MicroPython driver for the VL6180X sensor on the ESP32.
* [vl53l0x-nb](https://github.com/antirez/vl53l0x-nb) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2024-03-04 - Fork of MicroPython driver for vl53l0x TOF sensor to add non-blocking mode.
* [Qwiic\_TOF\_Module\_RFD77402](https://github.com/ZIOCC/Qwiic_TOF_Module_RFD77402) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2020-05-29 - Qwiic TOF Module (RFD77402) time-of-flight rangefinding module.
* [micropython-vl53l0x](https://github.com/mcauser/deshipu-micropython-vl53l0x) ⚠️ Archived - Time-of-Flight laser-ranging sensor.
* [LidarLight\_v3HP\_micropython](https://github.com/Dnapert/LidarLight_v3HP_micropython) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-08-11 - A MicroPython library for the Garmin Lidar Lite v3HP.

#### Distance Ultrasonic

* [micropython-hcsr04](https://github.com/rsc1975/micropython-hcsr04) ⭐ 167 | 🐛 2 | 🌐 Python | 📅 2023-03-08 - Driver for HC-SR04 ultrasonic distance sensors.
* [micropython-us100](https://github.com/kfricke/micropython-us100) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2018-03-09 - MicroPython driver for the US-100 sonar distance sensor.
* [micropython-i2c-ultrasonic](https://github.com/HowManyOliversAreThere/micropython-i2c-ultrasonic) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-02-22 - MicroPython driver for the RCWL-9620-based M5 I2C Ultrasonic Distance Unit.
* [micropython-grove-ultrasonic-ranger](https://github.com/mores/TheMissingLink/tree/main/Seeed_MicroPython_UltrasonicRanger) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-01-15 - Driver for SeeedStudio's Grove Ultrasonic Ranger.

#### Dust

* [pyGP2Y](https://github.com/amigcamel/pyGP2Y) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-09-06 - MicroPython library for the Sharp GP2Y1014AU0F Dust Sensor.

#### Energy

* [micropython-p1meter](https://github.com/Josverl/micropython-p1meter) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2025-09-21 - A ESP32 sensor to read a p1 electricity meter and publish this to MQTT and Home Assistant, written in MicroPython.
* [MCP39F521](https://github.com/warpme/MCP39F521) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2017-07-03 - ESP8266 scripts for reading MCP39F521 power monitors.
* [ATM90E26\_Micropython](https://github.com/whatnick/ATM90E26_Micropython) ⭐ 3 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2020-01-08 - Driver for ATM90E26 energy metering device.
* [cs5490\_micropython](https://github.com/whatnick/cs5490_micropython) ⭐ 1 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2019-04-20 - MicroPython Driver for CS5490 Energy Monitor IC.
* [esp32-solar2](https://github.com/octopusengine/esp32-solar2) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2020-05-17 - Simple solar regulator - MicroPython project.

#### Gaseous

* [MQ135](https://github.com/rubfi/MQ135) ⭐ 48 | 🐛 7 | 🌐 Python | 📅 2020-08-22 - Driver for MQ135 gas sensor.
* [CCS811](https://github.com/Notthemarsian/CCS811) ⭐ 32 | 🐛 4 | 🌐 Python | 📅 2020-11-02 - Basic MicroPython driver for CCS811 on ESP8266 boards.
* [micropython-scd30](https://github.com/agners/micropython-scd30) ⭐ 31 | 🐛 4 | 🌐 Python | 📅 2023-02-27 - MicroPython I2C driver for Sensirion SCD30 CO2 sensor module.
* [micropython-MQ](https://github.com/kartun83/micropython-MQ) ⭐ 25 | 🐛 4 | 🌐 Python | 📅 2017-09-27 - Drivers for MQ series gas sensors.
* [SCD4x](https://github.com/octaprog7/SCD4x) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-10-20 - MicroPython module for work with SCD4x (SCD40, SCD41) low power CO2, temperature & humidity electroacoustic sensor from Sensirion.
* [MicroPython\_SCD4X](https://github.com/peter-l5/MicroPython_SCD4X) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2025-07-25 - MicroPython I2C driver for Sensirion SCD40 and SCD41 CO2 sensors.
* [micropython-sgp40](https://github.com/agners/micropython-sgp40) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2020-11-01 - MicroPython I2C driver for SGP40 VOC sensor module.
* [ens160](https://github.com/octaprog7/ens160) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-06-06 - MicroPython module for work with ENS160 Digital Metal-Oxide Multi-Gas Sensor.
* [MicroPython\_AGS02MA](https://github.com/jposada202020/MicroPython_AGS02MA) ⚠️ Archived - MicroPython Driver for the AGS02MA TVOC sensor.
* [MICS6814-Micropython-driver](https://gitlab.com/DanNduati/MICS6814-Micropython-driver) - ESP32 MicroPython driver for the Pimoroni MICS6814 breakout board.

#### Human Presence

* [ld2410](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/ld2410.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - 24GHz human presence sensing module, capable of detecting moving and stationary targets, and providing an approximate range.

#### Humidity

* [MicroPython\_HTS221](https://github.com/jposada202020/MicroPython_HTS221) ⚠️ Archived - MicroPython Driver for the HTS221 Humidity Sensor.

#### Light

* [bh1750](https://github.com/PinkInk/upylib/tree/master/bh1750) ⭐ 56 | 🐛 0 | 🌐 Python | 📅 2018-06-12 - BH1750 I2C digital light sensor driver.
* [mpy\_bh1750fvi\_esp8266](https://github.com/catdog2/mpy_bh1750fvi_esp8266) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2016-07-01 - ESP8266 driver for BH1750FVI sensor.
* [veml7700](https://github.com/palouf34/veml7700) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2019-12-21 - Library for MicroPython for VEML7700 light sensor.
* [MicroPython-SI1145](https://github.com/neliogodoi/MicroPython-SI1145) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2020-04-03 - SI1145 UV index, IR, visible light and proximity sensor.
* [BH1750](https://github.com/octaprog7/BH1750) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-12-12 - MicroPython module for the BH1750 ambient light sensor (ALS).
* [micropython-tsl2561](https://github.com/kfricke/micropython-tsl2561) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2016-02-11 - Driver for the TSL2561 illumination sensor from TAOS / ams.
* [MicroPython\_MAX44009\_driver](https://github.com/rcolistete/MicroPython_MAX44009_driver) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2019-11-23 - MicroPython driver for MAX44009 light sensor.
* [MicroPython-VEML6075](https://github.com/neliogodoi/MicroPython-VEML6075) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2019-09-30 - Driver base for the VEML6075 UV light sensor.
* [micropython-max44009](https://github.com/mcauser/micropython-max44009) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2020-09-25 - MicroPython driver for the MAX44009 ambient light sensor.
* [bh1750.py](https://github.com/adyavanapalli/bh1750.py) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-08-10 - MicroPython BH1750 ambient light sensor driver.
* [veml7700](https://github.com/octaprog7/veml7700) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-04-13 - MicroPython module for the VEML7700 ambient light sensor (ALS) from Vishay.
* [opt3001](https://github.com/octaprog7/opt3001) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-11-07 - MicroPython module for OPT3001, external lighting sensor from Texas Instruments.
* [ltr390uv](https://github.com/octaprog7/ltr390uv) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-04-28 - MicroPython module for LTR390UV, ambient light sensor in the visible and ultraviolet ranges.

#### Load Cell

* [micropython-hx711](https://github.com/SergeyPiskunov/micropython-hx711) ⭐ 87 | 🐛 3 | 🌐 Python | 📅 2024-01-16 - MicroPython driver for HX711 24-Bit Analog-to-Digital Converter.
* [hx711](https://github.com/robert-hh/hx711) ⭐ 66 | 🐛 2 | 🌐 Python | 📅 2025-09-09 - MicroPython driver for the HX711 load cell interface.
* [hx710](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/hx710.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - MicroPython driver for the HX710.
* [hx711\_mpy-driver](https://github.com/HowManyOliversAreThere/hx711_mpy-driver) ⭐ 8 | 🐛 3 | 🌐 Python | 📅 2025-05-22 - MicroPython Driver for the HX711 weighing sensor.
* [hx710](https://github.com/robert-hh/hx710) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-09-14 - MicroPython driver for the HX710 load cell interface.

#### Magnetometer

* [MicroPython\_MLX90393](https://github.com/jposada202020/MicroPython_MLX90393) ⚠️ Archived - MicroPython Driver for the MLX90393 Magnetometer.
* [RM3100](https://github.com/octaprog7/RM3100) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2023-10-12 - MicroPython module for RM3100 geomagnetic sensor.
* [MicroPython\_LIS3MDL](https://github.com/jposada202020/MicroPython_LIS3MDL) ⚠️ Archived - MicroPython Driver for the ST LIS3MDL magnetometer.
* [MicroPython\_MMC5603](https://github.com/jposada202020/MicroPython_MMC5603) ⚠️ Archived - MicroPython driver for the Memsic MMC5603 Magnetometer.
* [MicroPython\_BMM150](https://github.com/jposada202020/MicroPython_BMM150) ⚠️ Archived - MicroPython Driver for the Bosch BMM150 Magnetometer.
* [MicroPython\_LIS2MDL](https://github.com/jposada202020/MicroPython_LIS2MDL) ⚠️ Archived - MicroPython Driver for the ST LIS2MDL Magnetometer sensor.
* [MicroPython\_MMC5983](https://github.com/jposada202020/MicroPython_MMC5983) ⚠️ Archived - MicroPython Library for the Memsic MMC5983 Magnetometer.
* [MMC5603](https://github.com/octaprog7/MMC5603) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2023-11-30 - MicroPython module for MMC5603 geomagnetic sensor.
* [HSCDTD008A](https://github.com/octaprog7/HSCDTD008A) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-10-22 - MicroPython module for HSCDTD008A geomagnetic sensor.

#### Motion Inertial

* [micropython-fusion](https://github.com/micropython-IMU/micropython-fusion) ⭐ 345 | 🐛 5 | 🌐 Python | 📅 2020-08-26 - Sensor fusion calculates heading, pitch and roll from the outputs of motion tracking devices.
* [micropython-mpu9x50](https://github.com/micropython-IMU/micropython-mpu9x50) ⭐ 276 | 🐛 3 | 🌐 Python | 📅 2024-10-23 - Driver for the InvenSense MPU9250 inertial measurement unit.
* [micropython-mpu9250](https://github.com/tuupola/micropython-mpu9250) ⭐ 164 | 🐛 7 | 🌐 Python | 📅 2024-03-01 - I2C driver for MPU9250 9-axis motion tracking device.
* [MPU6050-ESP8266-MicroPython](https://github.com/adamjezek98/MPU6050-ESP8266-MicroPython) ⭐ 91 | 🐛 7 | 🌐 Python | 📅 2021-04-05 - ESP8266 driver for MPU6050 accelerometer/gyroscope.
* [py-mpu6050](https://github.com/larsks/py-mpu6050) ⭐ 86 | 🐛 5 | 🌐 Python | 📅 2022-01-31 - ESP8266 driver for MPU6050 accelerometer/gyroscope.
* [flight\_controller](https://github.com/wagnerc4/flight_controller) ⭐ 76 | 🐛 0 | 🌐 Python | 📅 2015-12-16 - MicroPython flight controller.
* [micropython-bno055](https://github.com/micropython-IMU/micropython-bno055) ⭐ 61 | 🐛 2 | 🌐 Python | 📅 2025-10-11 - Bosch BNO055 driver for MicroPython. IMU with hardware sensor fusion.
* [micropython-mpu6886](https://github.com/tuupola/micropython-mpu6886) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2020-03-27 - MicroPython I2C driver for MPU6886 6-axis motion tracking device.
* [upy-motion](https://github.com/OneMadGypsy/upy-motion) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2021-06-24 - A simple MPU6050 driver written in MicroPython.
* [MicroPython\_ICM20948](https://github.com/jposada202020/MicroPython_ICM20948) ⚠️ Archived - ARCHIVED. MicroPython Driver for the TDK ICM20948 Accelerometer/Gyro Sensor.
* [micropython-mpu6050-mqtt-streamer](https://github.com/mozanunal/micropython-mpu6050-mqtt-streamer) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2019-11-17 - Stream data from MPU6050 to MQTT server using MicroPython on ESP8266.
* [MicroPython\_BMI270](https://github.com/jposada202020/MicroPython_BMI270) ⚠️ Archived - ARCHIVED. MicroPython Driver for the Bosch BMI270 Accelerometer/Gyro Sensor.
* [micropython-bmx055](https://github.com/micropython-IMU/micropython-bmx055) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2017-02-19 - Driver for Bosch BMX055 IMU sensor.
* [micropython-bno08x-rvc](https://github.com/rdagger/micropython-bno08x-rvc) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-09-09 - MicroPython library for BNO08x.
* [micropython-bno055](https://github.com/deshipu/micropython-bno055) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2018-04-24 - Bosch Sensortec BNO055 9DOF IMU sensor, I2C interface.
* [micropython-lsm9ds0](https://github.com/micropython-IMU/micropython-lsm9ds0) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2022-06-21 - LSM9DS0 g-force linear acceleration, Gauss magnetic and DPS angular rate sensors.
* [MicroPython\_BMI160](https://github.com/jposada202020/MicroPython_BMI160) ⚠️ Archived - ARCHIVED. MicroPython Driver for the Bosch BMI160 Accelerometer/Gyro Sensor.
* [MicroPython\_LSM6DSOX](https://github.com/jposada202020/MicroPython_LSM6DSOX) ⚠️ Archived - ARCHIVED. MicroPython Library for the ST LSM6DSOX accelerometer/gyro Sensor.
* [micropython-mpu6050](https://github.com/wybiral/micropython-mpu6050) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2020-11-27 - MicroPython library for reading from MPU-6050 accelerometer and gyroscope modules.
* [MPU6050-ESP32-MicroPython](https://github.com/gitcnd/MPU6050-ESP32-MicroPython) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-07-30 - MPU6050 (Accelerometer/Gyroscope) driver which works on ESP32.
* [MicroPython\_ICG20660](https://github.com/jposada202020/MicroPython_ICG20660) ⚠️ Archived - ARCHIVED. MicroPython Driver for the TDK ICG20660 Accelerometer/Gyro sensor.
* [micropython-mpu9250](https://gitlab.com/nnayo/micropython-mpu9250) - MicroPython MPU-9250 (MPU-6500 + AK8963) I2C driver.

#### Proximity

* [apds9960](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/apds9960.py) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-03 - MicroPython Driver for the APDS9960, with simple gesture detection.
* [uPy\_APDS9960](https://github.com/rlangoy/uPy_APDS9960) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2025-01-30 - MicroPython proximity library for ESP8266 using APDS9960.
* [MicroPython\_VCNL4010](https://github.com/jposada202020/MicroPython_VCNL4010) ⚠️ Archived - MicroPython Driver for the Vishay VCNL4010 Proximity and Ambient Light Sensor.

#### Radiation

* [ESPGeiger](https://github.com/biemster/ESPGeiger) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2016-09-28 - MicroPython library for the ESP8266 Geiger counter.
* [micropython-geiger](https://github.com/Wangzhaotian725/micropython-geiger) ⭐ 0 | 🐛 0 | 📅 2014-11-19 - Geiger counter with MicroPython card.

#### Soil Moisture

* [MicroPython-MiFlora](https://github.com/matthias-bs/MicroPython-MiFlora) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2025-05-23 - Xiaomi Mi Flora (aka flower care) BLE plant sensors (soil moisture/conductivity/light intensity/temperature).
* [micropython-chirp](https://github.com/robberwick/micropython-chirp) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2016-10-31 - Driver for the Chirp Soil Moisture Sensor.
* [micropython-miflora](https://github.com/agners/micropython-miflora) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2020-04-26 - MicroPython library for Xiaomi Mi Flora BLE plant sensors.

#### Spectral

* [AS726X\_LoPy](https://github.com/jajberni/AS726X_LoPy) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2018-03-27 - MicroPython driver for the AS726X spectral sensor.
* [MicroPython\_AS7262X\_driver](https://github.com/rcolistete/MicroPython_AS7262X_driver) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2018-09-20 - MicroPython driver for AS7262/AS7263 nano spectrometer sensor.

#### Temperature Analog

* [max31865](https://github.com/sufyanaslam198/max31865) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2024-05-25 - Precision resistance-to-digital converter optimized for platinum resistance temperature detectors, SPI interface.
* [micropython-generic-thermistor](https://github.com/Trexation/micropython-generic-thermistor) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2024-02-04 - MicroPython Generic Thermistor Library for simplified temperature sensing using NTC thermistors with voltage dividers.
* [max31856](https://github.com/alinbaltaru/max31856) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2016-10-28 - Precision thermocouple to digital converter with linearization, SPI interface.
* [micropython-max31855](https://github.com/mcauser/deshipu-micropython-max31855) ⚠️ Archived - Thermocouple amplifier, SPI interface.
* [micropython-simple-thermistor](https://github.com/scruss/micropython-simple-thermistor) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-10-30 - Read NTC thermistor temperature wired in a potential divider.
* [mcp9700](https://gitlab.com/CrispyCrafter/mcp9700) - Generic MicroPython driver for MCP9700.

#### Temperature Digital

* [Official DHT11+DHT12](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/sensor/dht) ⭐ 2,751 | 🐛 280 | 🌐 Python | 📅 2025-12-09 - ESP8266 driver for DHT11 and DHT12 temperature and humidity sensor.
* [HTU21D](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/HTU21D.md) ⭐ 816 | 🐛 4 | 🌐 Python | 📅 2026-01-30 - Asynchronous driver for HTU21D temperature and humidity sensor.
* [micropython-sht30](https://github.com/rsc1975/micropython-sht30) ⭐ 52 | 🐛 5 | 🌐 Python | 📅 2019-06-07 - Driver for SHT30 temperature and humidity sensor.
* [micropython\_ahtx0](https://github.com/targetblank/micropython_ahtx0) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2023-10-12 - MicroPython driver for the AHT10 and AHT20 temperature and humidity sensors.
* [BME680-Micropython](https://github.com/robert-hh/BME680-Micropython) ⭐ 48 | 🐛 3 | 🌐 Python | 📅 2025-05-22 - MicroPython driver for the BME680 sensor.
* [micropython-sht31](https://github.com/kfricke/micropython-sht31) ⭐ 26 | 🐛 1 | 🌐 Python | 📅 2023-07-16 - Driver for the SHT31 temperature and humidity sensor.
* [micropython-am2320](https://github.com/mcauser/micropython-am2320) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2024-02-16 - Aosong AM2320 temperature and humidity sensor, I2C interface.
* [bme680-pure-mp](https://github.com/antirez/bme680-pure-mp) ⭐ 17 | 🐛 3 | 🌐 Python | 📅 2024-02-27 - Pure MicroPython Bosch BME680 sensor driver.
* [micropython-dht12](https://github.com/mcauser/micropython-dht12) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2024-02-16 - Aosong DHT12 temperature and humidity sensor, I2C interface.
* [bme680-mqtt-micropython](https://github.com/robmarkcole/bme680-mqtt-micropython) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2018-11-09 - Driver for BME680 gas, pressure, temperature and humidity sensor.
* [micropython-si7021](https://github.com/chrisbalmer/micropython-si7021) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2017-01-05 - SI7021 Temperature and humidity sensor, I2C interface.
* [MicroPython\_SHT4X](https://github.com/jposada202020/MicroPython_SHT4X) ⚠️ Archived - MicroPython Driver for the Sensirion Temperature and Humidity SHT40 and SHT45 Sensor.
* [micropython-mcp9808](https://github.com/kfricke/micropython-mcp9808) ⭐ 8 | 🐛 3 | 🌐 Python | 📅 2023-01-16 - Driver for the Microchip MCP9808 temperature sensor.
* [micropython-tmp102](https://github.com/khoulihan/micropython-tmp102) ⚠️ Archived - Driver for TMP102 digital temperature sensor.
* [esp-sht3x-micropython](https://github.com/HAIZAKURA/esp-sht3x-micropython) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2020-09-19 - A SHT3x (SHT30/31/35) library for ESP8266/ESP32 with MicroPython.
* [micropython-lm75a](https://github.com/mcauser/micropython-lm75a) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2020-09-25 - Driver for the NXP LM75A digital temperature sensor.
* [htu21d-esp8266](https://github.com/julianhille/htu21d-esp8266) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2018-06-25 - This is a MicroPython module / class to measure data from the HTU21D.
* [micropython-hdc1008](https://github.com/kfricke/micropython-hdc1008) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2016-05-14 - Driver for the Texas Instruments HDC1008 humidity and temperature sensor.
* [sht25-micropython](https://github.com/Miceuz/sht25-micropython) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2018-01-22 - Driver for SHT25 temperature and humidity sensor.
* [MicroPython\_SHTC3](https://github.com/jposada202020/MicroPython_SHTC3) ⚠️ Archived - MicroPython Driver for the Sensirion SHTC3 Temperature and Humidity Sensor.
* [LM75-MicroPython](https://github.com/OldhamMade/LM75-MicroPython) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-07-24 - Driver for LM75 digital temperature sensor, I2C interface.
* [micropython-sht11](https://github.com/2black0/micropython-sht11) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2025-05-02 - Driver for Sensirion SHT11 temperature and humidity sensor.
* [micropython-sht30](https://github.com/schinckel/micropython-sht30) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2019-08-01 - SHT30 sensor driver in pure Python based on I2C bus.
* [SHT30](https://github.com/robert-hh/SHT30) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - MicroPython driver for the Sensirion SHT3x sensor.
* [micropython-hdc1080](https://github.com/mcauser/micropython-hdc1080) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-02-04 - MicroPython driver for the HDC1080 temperature and humidity sensor.
* [micropython-mpl115a2](https://github.com/khoulihan/micropython-mpl115a2) ⚠️ Archived - Pyboard driver for the MPL115A2 barometric pressure sensor.
* [micropython-Si70xx](https://github.com/billyrayvalentine/micropython-Si70xx) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2017-01-12 - Silicon Labs Si70xx series of relative humidity and temperature sensors, I2C interface.
* [MicroPython\_TMP117](https://github.com/jposada202020/MicroPython_TMP117) ⚠️ Archived - MicroPython Driver for the TMP117 Temperature Sensor.
* [TMP117](https://github.com/octaprog7/TMP117) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-11-23 - MicroPython module for the TMP117 temperature sensor from Texas Instruments.
* [micropython-Si7005](https://github.com/Smrtokvitek/micropython-Si7005) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2016-01-02 - Driver for Si7005 relative humidity and temperature sensor.
* [micropython-Si705x](https://github.com/billyrayvalentine/micropython-Si705x) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2017-01-12 - Silicon Labs Si705x series of temperature sensors, I2C interface.
* [MicroPython\_HTU31D](https://github.com/jposada202020/MicroPython_HTU31D) ⚠️ Archived - MicroPython library for TE HTU31D temperature and humidity sensors.
* [MicroPython\_SHT20](https://github.com/jposada202020/MicroPython_SHT20) ⚠️ Archived - MicroPython Driver for the Sensirion SHT20 Temperature Sensor.
* [MicroPython\_MCP9808](https://github.com/jposada202020/MicroPython_MCP9808) ⚠️ Archived - MicroPython Driver for the Microchip MCP9808 Temperature Sensor.
* [MicroPython\_HDC1080](https://github.com/jposada202020/MicroPython_HDC1080) ⚠️ Archived - MicroPython driver for the TI HDC1080 Temperature and Humidity sensor.
* [BME680](https://github.com/octaprog7/BME680) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2022-10-09 - MicroPython module for the BME680, Bosch low power gas, pressure, temperature & humidity sensor.
* [micropython-si7021](https://github.com/mcauser/deshipu-micropython-si7021) ⚠️ Archived - SI7021 Temperature and humidity sensor, I2C interface.
* [micropython-tmp1075](https://github.com/mattytrentini/micropython-tmp1075) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2025-05-22 - Driver for the TI TMP1075 temperature sensor.
* [sht85](https://github.com/octaprog7/sht85) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2022-12-23 - MicroPython driver for the [Sensiron SHT85](https://sensirion.com/products/catalog/SHT85/) humidity and temperature sensor.
* [micropython-zacwire](https://github.com/mdaeron/micropython-zacwire) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-11-01 - MicroPython driver for the ZACwire protocol used in TSic 506F temperature sensors.
* [MicroPython\_SI7021](https://github.com/jposada202020/MicroPython_SI7021) ⚠️ Archived - MicroPython Library for the Temperature and Humidity SI7021 Sensor.
* [MicroPython\_ADT7410](https://github.com/jposada202020/MicroPython_ADT7410) ⚠️ Archived - MicroPython Driver for the Analog Devices ADT7410 Temperature Sensor.
* [MicroPython\_WSENTIDS](https://github.com/jposada202020/MicroPython_WSENTIDS) ⚠️ Archived - MicroPython library for the WSEN WSEN-TIDS temperature Sensor.
* [MicroPython\_HS3003](https://github.com/jposada202020/MicroPython_HS3003) ⚠️ Archived - MicroPython Driver for the Renesas HS3003 Temperature and Humidity Sensor.
* [MicroPython\_STTS22H](https://github.com/jposada202020/MicroPython_STTS22H) ⚠️ Archived - MicroPython Driver for the STTS22H Temperature Sensor.
* [MicroPython\_HTU21DF](https://github.com/jposada202020/MicroPython_HTU21DF) ⚠️ Archived - MicroPython HTU21D-F Temperature & Humidity driver.
* [MicroPython\_AS6212](https://github.com/jposada202020/MicroPython_AS6212) ⚠️ Archived - MicroPython Library for the ASM AS6212 Temperature Sensor.
* [MicroPython\_PCT2075](https://github.com/jposada202020/MicroPython_PCT2075) ⚠️ Archived - MicroPython Driver for the NXP Semiconductors PCT2075 Temperature Sensor.
* [SHT4X](https://github.com/octaprog7/SHT4X) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-06-27 - MicroPython module for controlling the SHT4x - 4th generation relative humidity and temperature sensor.
* [sht25-micropython](https://gitlab.com/miceuz/sht25-micropython) - MicroPython implementation of API of SHT25 humidity and temperature sensor.

#### Temperature IR

* [micropython-mlx90614](https://github.com/mcauser/micropython-mlx90614) ⭐ 37 | 🐛 5 | 🌐 Python | 📅 2024-04-16 - Driver for Melexis MLX90614 IR temperature sensor.
* [MicroPython\_MLX90615\_driver](https://github.com/rcolistete/MicroPython_MLX90615_driver) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2020-06-06 - MicroPython driver for Melexis MLX90615 IR temperature sensor.

#### Touch Capacitive

* [micropython-mpr121](https://github.com/mcauser/micropython-mpr121) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2020-02-14 - Driver for MPR121 capacitive touch keypads and breakout boards.
* [micropython-TTP229-BSF](https://github.com/alankrantas/micropython-TTP229-BSF) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2021-08-04 - MicroPython ESP8266/ESP32 driver for TTP229-BSF 16-key capacitive keypad in serial interface mode.
* [micropython-ft6x06](https://github.com/antirez/micropython-ft6x06) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2024-03-03 - Simple driver for FT6x06 capacitive touch sensor in pure Python.
* [micropython-ttp223](https://github.com/mcauser/micropython-ttp223) ⭐ 9 | 🐛 0 | 📅 2018-08-07 - Examples using TTP223 capacitive touch module.
* [uFT6336U](https://github.com/fantasticdonkey/uFT6336U) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2021-02-21 - MicroPython I2C driver for the Focus LCDs FT6336U capacitive touch panel controller IC.
* [MicroPythonTrill](https://github.com/Heerkog/MicroPythonTrill) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2024-05-24 - Trill touch sensor library for MicroPython.
* [L58Touch](https://github.com/russhughes/L58Touch) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2022-05-26 - L58 Multi-Touch MicroPython Module.

#### Touch Resistive

* [XPT2046-touch-pad-driver](https://github.com/robert-hh/XPT2046-touch-pad-driver) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - Driver for XPT2046 touch pad controller used in many TFT modules.

### Scheduling

* [Schedule](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/SCHEDULE.md) ⭐ 816 | 🐛 4 | 🌐 Python | 📅 2026-01-30 - A scheduler for asyncio based applications. Schedule events at specified times and dates or with reference to Sun and Moon rise and set.
* [micropython-mcron](https://github.com/fizista/micropython-mcron) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2021-11-06 - MicroCRON is a time-based task scheduling program for MicroPython.
* [micropython-aioschedule](https://github.com/ThinkTransit/micropython-aioschedule) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-09-17 - A persistent uasyncio scheduler that supports deepsleep between task runs.
* [micropython-scron](https://github.com/fizista/micropython-scron) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2020-06-03 - SimpleCRON is a time-based task scheduling program inspired by the well-known cron program for Unix systems.
* [Suntime](https://github.com/lorcap/micropython-suntime) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-01-07 - Approximated calculation of sunrise and sunset time. Given a `date` and the coordinate pair `(latitude, longitude)` of a place on Earth, this library computes when sun rises above the horizon and when it sets down on that day in that place.

### Storage

#### Configuration file

* [uPyftsConf](https://github.com/aleppax/upyftsconf) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2024-03-23 - MicroPython Far Too Simple Config File. Single file library that writes configurations to itself.
* [toml](https://github.com/gitcnd/toml) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-08-09 - Read and write .toml files. Works in MicroPython and CircuitPython.

#### Database

* [uSQLite](https://github.com/spatialdude/usqlite) ⭐ 126 | 🐛 15 | 🌐 C | 📅 2024-11-01 - SQLite library module for MicroPython.
* [micropg](https://github.com/nakagami/micropg) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2025-01-06 - PostgreSQL database driver for MicroPython.
* [micropython-firebase-realtime-database](https://github.com/ckoever/micropython-firebase-realtime-database) ⭐ 25 | 🐛 3 | 🌐 Python | 📅 2024-08-06 - Firebase implementation for MicroPython optimized for ESP32.
* [uPyMySQL](https://github.com/dvrhax/uPyMySQL) ⭐ 24 | 🐛 5 | 🌐 Python | 📅 2020-05-07 - Pure MicroPython MySQL Client.
* [micropython-redis](https://github.com/dwighthubbard/micropython-redis) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2016-07-04 - A Redis client implementation designed for use with MicroPython.
* [MicroPyDatabase](https://github.com/sungkhum/MicroPyDatabase) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2023-03-11 - A low-memory JSON-based database for MicroPython.
* [nmongo](https://github.com/nakagami/nmongo) ⭐ 20 | 🐛 2 | 🌐 Python | 📅 2025-02-07 - MongoDB client for CPython and MicroPython, with MongoDB shell-like APIs.
* [picoredis](https://github.com/SpotlightKid/picoredis) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2021-05-02 - A very minimal Redis client (not only) for MicroPython.
* [micropython-cratedb](https://github.com/crate/micropython-cratedb/) ⭐ 10 | 🐛 5 | 🌐 Python | 📅 2026-02-10 - MicroPython driver for CrateDB databases.
* [micropython-firebase-firestore](https://github.com/WoolDoughnut310/micropython-firebase-firestore) ⭐ 8 | 🐛 7 | 🌐 Python | 📅 2022-12-23 - Firebase Firestore implementation for MicroPython.
* [micropg\_lite](https://github.com/TimonW-Dev/micropg_lite) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-07-06 - Lightweight version of micropg with some slight limitations (e.g. error handling), in order to run on low-RAM microcontrollers (works with ESP8266).
* [simple-db](https://github.com/ctimmer/simple-db) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-10-05 - MicroPython relational database using B-tree.
* [micropg\_superlite](https://github.com/TimonW-Dev/micropg_superlite) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-02-10 - The lightest PostgreSQL database driver for MicroPython based on micropg\_lite/micropg, but has even stronger restrictions in functionality and focuses only on the absolutely necessary functions.

#### EEPROM

* [micropython\_eeprom](https://github.com/peterhinch/micropython_eeprom) ⭐ 84 | 🐛 7 | 🌐 Python | 📅 2024-09-29 - Cross-platform MicroPython device drivers for memory chips (EEPROM, FRAM, Flash, PSRAM).
* [micropython-eeprom](https://github.com/brainelectronics/micropython-eeprom) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2023-06-12 - MicroPython driver for AT24Cxx EEPROM.
* [mb\_24x256\_512](https://github.com/MarksBench/mb_24x256_512) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-06-04 - Very simple MicroPython module/driver for Microchip 24x256 and 24x512 I2C EEPROM devices.

#### Flash

* [micropython\_data\_to\_py](https://github.com/peterhinch/micropython_data_to_py) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2023-08-01 - A Python 3 utility to convert an arbitrary binary file to Python source for freezing as bytecode in Flash.
* [freezeFS](https://github.com/bixb922/freezeFS) ⭐ 32 | 🐛 1 | 🌐 Python | 📅 2025-10-25 - Create self-extracting compressed or self-mounting archives for MicroPython.
* [micropython-winbond](https://github.com/brainelectronics/micropython-winbond) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2024-05-30 - Interact with Winbond W25Q Flash chips via SPI.

#### FRAM

* [micropython-fram](https://github.com/rolandvs/micropython-fram) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2018-01-04 - Pyboard driver for Ferroelectric RAM module.

#### PSRAM

* [mb\_PSRAM\_64Mb\_SPI](https://github.com/MarksBench/mb_PSRAM_64Mb_SPI) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2021-06-10 - Very simple MicroPython module to use a generic 64Mbit PSRAM (ie Adafruit 4677) with a Raspberry Pi Pico (RP2040).

#### SD

* [mp-sdcard-littleFS](https://github.com/jornamon/mp-sdcard-littleFS) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2024-02-21 - MicroPython SD card driver that works with LittleFS2 (implements extended interface).

#### SRAM

* [mb\_23LC1024](https://github.com/MarksBench/mb_23LC1024) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2021-06-04 - Very simple MicroPython module to use a Microchip 23LC1024 SPI SRAM with a Raspberry Pi Pico (RP2040).
* [mb\_47x16](https://github.com/MarksBench/mb_47x16) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-06-04 - Very simple MicroPython module/driver for Microchip 47x16 EERAM devices (47L/47C).

### Threading

* [MicroWorkers](https://github.com/jczic/MicroWorkers) ⭐ 49 | 🐛 1 | 🌐 Python | 📅 2019-09-19 - A micro workers class that easily manages a pool of threads to optimise simultaneous jobs and jobs endings, for MicroPython (used on Pycom modules & ESP32).

### User Interface

* [upymenu](https://github.com/jplattel/upymenu) ⭐ 35 | 🐛 6 | 🌐 Python | 📅 2022-12-08 - MicroPython Menu for LCD Displays.

### Utilities

* [micropython-hexdump](https://github.com/mattytrentini/micropython-hexdump) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-05-22 - An implementation of Hexdump for MicroPython.
* [mp\_wcwidth](https://github.com/Josverl/mp_wcwidth) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-01-27 - Python port of [wcwidth](https://github.com/jquast/wcwidth) ⭐ 438 | 🐛 1 | 🌐 Python | 📅 2026-02-06 to handle wide unicode characters such as "你好世界" in terminal output.
* [micropython-units](https://github.com/WoolleySheep/micropython-units) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-08-15 - A library for working with physical quantities in MicroPython.

## Community

* [MicroPython Discussions on GitHub](https://github.com/orgs/micropython/discussions) - GitHub discussions for all things related to MicroPython.
* [MicroPython Forum (archive)](https://forum.micropython.org/) - Archived community conversations on all things related to MicroPython.
* [Discord](https://micropython.org/discord) - Get an invite to the MicroPython Discord server.
* [MicroPython on Mastodon / Fediverse](https://fosstodon.org/@MicroPython) - Follow MicroPython in the Fediverse.
* [MicroPython on Twitter](https://twitter.com/micropython) - Follow MicroPython on Twitter for latest news and updates.
* [MicroPython on Facebook](https://www.facebook.com/micropython) - Like MicroPython on Facebook for competitions, news and updates.
* [Melbourne MicroPython Meetup](https://www.meetup.com/en-au/micropython-meetup/) - Regular meetup at CCHS in Melbourne, Australia.

## Tutorials

* [asyncio](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/TUTORIAL.md) ⭐ 816 | 🐛 4 | 🌐 Python | 📅 2026-01-30 - Write asynchronous code which interfaces to hardware devices.
* [Asynchronous drivers](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/DRIVERS.md) ⭐ 816 | 🐛 4 | 🌐 Python | 📅 2026-01-30 - Tutorial and code for asynchronous interfaces to switches, pushbuttons, encoders and ADCs.
* [3D rotation with quaternions](https://github.com/peterhinch/micropython-samples/blob/master/QUATERNIONS.md) ⭐ 523 | 🐛 13 | 🌐 Python | 📅 2025-09-14 - Tutorial and code for the easy way to do 3D rotation.
* [Pyboard micropower](https://github.com/peterhinch/micropython-micropower) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2023-09-11 - Tutorial and code for low power applications on Pyboard 1.x and Pyboard D.
* [CoderDojo Twin Cities MicroPython](https://github.com/CoderDojoTC/micropython) ⭐ 31 | 🐛 2 | 🌐 Python | 📅 2025-04-03 - Full coding curriculum for teaching MicroPython to children.
* [Miguel Grinberg](https://blog.miguelgrinberg.com/category/MicroPython) - MicroPython and the Internet of Things.
* [Bhavesh Kakwani](https://bhave.sh/) - MicroPython videos + written tutorials.
* [MicroPython Tutorials for ESP32 boards](https://www.upesy.com/blogs/tutorials/tutorials-for-esp32-with-micropython-code) - Tutorials with code examples to learn the basic of MicroPython with ESP32 boards.
* [Learn MicroPython with a Pi Pico board](https://www.upesy.com/blogs/tutorials/tutorials-for-rpi-pi-pico-with-micropython-code) - Tutorials on MicroPython with the Raspberry Pi Pico / RP240 boards.

## Books

* [Programming with MicroPython: Embedded Programming with Microcontrollers and Python](https://www.oreilly.com/library/view/programming-with-micropython/9781491972724/) - By Nicholas H. Tollervey. ISBN 9781491972731.
* [MicroPython for the Internet of Things: A Beginner's Guide to Programming with Python on Microcontrollers](https://link.springer.com/book/10.1007/978-1-4842-3123-4) - By Charles Bell. ISBN 9781484231227.
* [Beginning MicroPython with the Raspberry Pi Pico: Build Electronics and IoT Projects](https://link.springer.com/book/10.1007/978-1-4842-8135-2) - By Charles Bell. ISBN 9781484281345.
* [MicroPython Cookbook](https://www.packtpub.com/en-us/product/micropython-cookbook-9781838641955) - By Marwan Alsabbagh. ISBN 9781838649951.
* [Python for Microcontrollers: Getting Started with MicroPython](https://www.mhprofessional.com/python-for-microcontrollers-getting-started-with-micropython-9781259644535-usa-group) - By Donald Norris. ISBN 9781259644535.
* [Advanced Programming in MicroPython By Example](https://www.amazon.com/Advanced-Programming-MicroPython-Example-Magda/dp/1090900937) - By Yury Magda. ISBN 9781090900937.
* [MicroPython Projects](https://www.packtpub.com/en-us/product/micropython-projects-9781789952537) - By Jacob Beningo. ISBN 9781789958034.
* [Get Started with MicroPython on Raspberry Pi Pico 2nd Edition](https://store.rpipress.cc/collections/books/products/get-started-with-micropython-on-raspberry-pi-pico-2nd-edition) - By Gareth Halfacree and Ben Everard. ISBN 9781912047291.
* [MicroPython for Microcontrollers](https://www.elektor.com/micropython-for-microcontrollers-e-book) - By Günter Spanner. ISBN 9783895764370.
* [MicroPython for the Raspberry Pi Pico W: A gentle introduction to programming digital circuits with Python](https://www.amazon.com/MicroPython-Raspberry-Pico-introduction-programming/dp/B0BKSCV18D) - By Miguel Grinberg. ISBN 9798361302710.
* [Programming ESP32: Learn MicroPython Coding and Electronics](https://www.amazon.com/Programming-ESP32-MicroPython-Coding-Electronics/dp/1739487451/) - By Simon Monk. ISBN 9781739487454.

## Frameworks

* [micrOS](https://github.com/BxNxM/micrOS) ⭐ 129 | 🐛 0 | 🌐 Python | 📅 2026-02-11 - MicroPython-based IoT Framework.
* [terkin-datalogger](https://github.com/hiveeyes/terkin-datalogger) ⭐ 64 | 🐛 32 | 🌐 Python | 📅 2022-12-03 - Flexible data logger application for MicroPython and CPython.
* [meerkat](https://github.com/crdietrich/meerkat) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2023-03-19 - I2C Data Acquisition for MicroPython and Raspberry Pi.
* [public-micropython-iot-platform](https://github.com/wolfen351/public-micropython-iot-platform) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2025-07-21 - Project Fred MicroPython IOT Platform, code to control relays, temp sensors, buttons, touchscreen, GPS etc. Has a responsive Web UI, MQTT, Home Assistant and ThingsBoard support.
* [perthensis](https://codeberg.org/scy/perthensis) - Perthensis: an asynchronous framework for MicroPython.

## Resources

* [MicroPython on GitHub](https://github.com/micropython/micropython) ⭐ 21,463 | 🐛 1,844 | 🌐 C | 📅 2026-02-12 - Submit bug reports, follow and join in development on GitHub.
* [MicroPython Wiki](https://github.com/micropython/micropython/wiki) ⭐ 21,463 | 🐛 1,844 | 🌐 C | 📅 2026-02-12 - Community generated documentation and examples of the features of MicroPython and the Pyboard.
* [awesome-micropythons](https://github.com/adafruit/awesome-micropythons) ⭐ 48 | 🐛 1 | 📅 2020-02-18 - The many forks & ports of MicroPython.
* [MicroPython](https://micropython.org) - Project website. Test drive the Pyboard. Try MicroPython online with Unicorn.
* [MicroPython Official Documentation](https://docs.micropython.org/) - For various ports, including quick reference, general information, examples and tutorials.
* [MicroPython Newsletter](https://micropython.org/newsletter) - Subscribe to the MicroPython newsletter for news and announcements including new features and new products.
* [MicroPython Store](https://store.micropython.org/) - Where you can buy the Pyboard, housings, skins, books, connectors and peripherals.
* [MicroPython on Wikipedia](https://en.wikipedia.org/wiki/MicroPython) - MicroPython on Wikipedia.

## Development

### Code Generation

* [micropy-cli](https://github.com/BradenM/micropy-cli) ⭐ 332 | 🐛 51 | 🌐 Python | 📅 2026-02-12 - Micropy CLI is a project management/generation tool for writing MicroPython code in modern IDEs such as Visual Studio Code.
* [micropython-stubs](https://github.com/Josverl/micropython-stubs) ⭐ 287 | 🐛 28 | 🌐 Python | 📅 2026-02-12 - Stubs of most MicroPython ports, boards and versions to make writing code that much simpler.
* [micropython-stubber](https://github.com/Josverl/micropython-stubber) ⭐ 244 | 🐛 24 | 🌐 Python | 📅 2026-02-11 - Generate and use stubs for different MicroPython firmwares to use with Visual Studio Code or any IDE and linter.
* [wasm2mpy](https://github.com/vshymanskyy/wasm2mpy) ⭐ 153 | 🐛 0 | 🌐 C | 📅 2025-01-09 - Compile WebAssembly to native MicroPython `.mpy` files. Allows writing code in various statically compiled languages, and translating them to C for near-native performance.
* [micropy-stubs](https://github.com/BradenM/micropy-stubs) ⭐ 30 | 🐛 6 | 🌐 Python | 📅 2022-12-08 - Automatically Generated Stub Packages for Micropy-Cli and whomever else.
* [micropython-extmod-generator](https://github.com/prusnak/micropython-extmod-generator) ⭐ 24 | 🐛 3 | 🌐 Python | 📅 2022-11-20 - Generator for MicroPython external modules written in C.
* [micropython-package-template](https://github.com/brainelectronics/micropython-package-template) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2024-09-30 - GitHub workflow supported MicroPython package template with deploys to the [Python Package Index](https://pypi.org/) on a push to the main branch and test deploys to the [Test Python Package Index](https://test.pypi.org/) on PRs.
* [micropython-usermod](https://micropython-usermod.readthedocs.io) - Online book about MicroPython external modules writen in C.

### Debugging

* [Asynchronous monitor](https://github.com/peterhinch/micropython-monitor) ⭐ 41 | 🐛 0 | 🌐 Python | 📅 2025-11-03 - Use a Raspberry Pico and a logic analyser or scope to monitor asynchronous code.
* [esp32-backtrace](https://github.com/tve/esp32-backtrace) ⭐ 30 | 🐛 2 | 🌐 Shell | 📅 2019-08-21 - ESP32 Exception Stack Backtrace Analyzer.
* [micropython-usyslog](https://github.com/kfricke/micropython-usyslog) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2023-07-13 - Simple remote syslog client for MicroPython.
* [micropython-aiosentry](https://github.com/devbis/micropython-aiosentry) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2019-03-12 - Asynchronous Sentry.io micro client for MicroPython.

### Firmware

* [micropython-builder](https://github.com/jonahbron/micropython-builder) ⭐ 0 | 🐛 0 | 🌐 Nix | 📅 2024-04-29 - Tool for building and flashing a custom MicroPython firmware.
* [mpflash](https://pypi.org/project/mpflash/) -⚡Your Ultimate MicroPython Flashing Companion for stm32, rp2, esp32, esp8266, samd.

### IDEs

* [ESP32-MPY-Jama](https://github.com/jczic/ESP32-MPY-Jama) ⭐ 483 | 🐛 33 | 🌐 Python | 📅 2023-05-03 - Tool for managing Espressif ESP32 microcontrollers with MicroPython.
* [pye](https://github.com/robert-hh/Micropython-Editor) ⭐ 250 | 🐛 3 | 🌐 Python | 📅 2026-01-22 - On device editor.
* [uPIDE](https://github.com/harbaum/upide) ⭐ 31 | 🐛 4 | 🌐 Python | 📅 2023-10-26 - µPIDE is a simple IDE for MicroPython.
* [Pyboard File Manager](https://github.com/joewez/PyboardFileManager) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2022-02-06 - Pyboard File Manager: Windows GUI for Pyboard.py compatible devices.
* [BIPES](https://bipes.net.br/ide/) - Web-based IDE for MicroPython with file manager, editor, code generation from blocks, IoT dashboard and Serial/USB/Bluetooth/WebREPL console on the web browser. Source: <https://github.com/BIPES>.
* [Embedible](https://embedible.io/) - an AI hardware copilot that helps you design, wire, and code MicroPython projects for ESP32 and Raspberry Pi Pico W.
* [JetBrains IntelliJ/PyCharm MicroPython Plugin](https://plugins.jetbrains.com/plugin/9777-micropython) - Plugin for MicroPython devices in IntelliJ and PyCharm.
* [MicroPython IDE for VSCode](https://marketplace.visualstudio.com/items?itemName=dphans.micropython-ide-vscode) - MicroPython IDE for Visual Studio Code.
* [MicroPython-REPLink for VSCode](https://marketplace.visualstudio.com/items?itemName=SWC-Fablab.micropython-replink) - Handy shortcuts for interacting with a MicroPython REPL terminal.
* [MPRemote for VSCode](https://marketplace.visualstudio.com/items?itemName=DavesCodeMusings.mpremote) - An extension to provide easy access to some of mpremote's functionality from within Visual Studio Code.
* [Mu Editor](https://codewith.mu/) -  Code with Mu: a simple Python/MicroPython/CircuitPython editor for beginner programmers.
* [Thonny IDE](https://thonny.org/) - Thonny: Python IDE for beginners.
* [ViperIDE](https://viper-ide.org) - An innovative MicroPython / CircuitPython IDE for Web and Mobile. No installation required.

### Logging

* [micropython-ulogger](https://github.com/majoson-chen/micropython-ulogger) ⭐ 40 | 🐛 6 | 🌐 Python | 📅 2022-06-16 - Lightweight log module customized for MicroPython.
* [scd30logger](https://github.com/agners/scd30logger) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2019-06-24 - Sensirion SCD30 based CO2, Humidity and Temperature Logger for MicroPython.
* [sht15logger](https://github.com/agners/sht15logger) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2019-06-17 - MicroPython Temperature and Humidity Logger using Sensirion SHT15.

### Shells

#### Jupyter

* [micropython-magic](https://github.com/josverl/micropython-magic) ⭐ 30 | 🐛 10 | 🌐 Python | 📅 2026-01-17 - MicroPython integrated into Jupyter notebooks.
* [jupyter\_upydevice\_kernel](https://github.com/Carglglz/jupyter_upydevice_kernel) ⭐ 16 | 🐛 4 | 🌐 Python | 📅 2022-03-04 - Jupyter kernel to interact with a MicroPython board over its REPL interface.

#### On Device

* [Micropython-Editor](https://github.com/robert-hh/Micropython-Editor) ⭐ 250 | 🐛 3 | 🌐 Python | 📅 2026-01-22 - Small on-board editor for Pyboard, WiPy, ESP8266, ESP32, PyCom and Adafruit devices written in Python.
* [upy-shell](https://github.com/dhylands/upy-shell) ⭐ 42 | 🐛 9 | 🌐 Python | 📅 2018-03-23 - A simple command line-based shell for MicroPython.
* [mpy\_shell](https://github.com/gitcnd/mpy_shell) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-08-17 - Linux-like shell for MicroPython. Full featured, very lightweight.

#### On Host

* [mpremote](https://github.com/micropython/micropython/blob/master/tools/mpremote/README.md) ⭐ 21,463 | 🐛 1,844 | 🌐 C | 📅 2026-02-12 - Powerful official shell that supports mounting the host's current directory on the target. Run code without changing the target's filesystem.
* [rshell](https://github.com/dhylands/rshell) ⭐ 1,031 | 🐛 132 | 🌐 Python | 📅 2024-12-04 - Copy or sync files to boards, enter REPL from your terminal.
* [ampy](https://github.com/scientifichackers/ampy) ⭐ 755 | 🐛 41 | 🌐 Python | 📅 2024-07-16 - Utility to interact with a MicroPython board over a serial connection.
* [mpfshell](https://github.com/wendlers/mpfshell) ⭐ 416 | 🐛 27 | 🌐 Python | 📅 2025-01-09 - A simple shell-based file explorer for ESP8266 and WiPy.
* [mpbridge](https://github.com/AmirHmZz/mpbridge) ⭐ 54 | 🐛 4 | 🌐 Python | 📅 2025-01-24 - A file system bridge to synchronize and manage files on a device running MicroPython.
* [mpr](https://github.com/bulletmark/mpr) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2025-10-11 - Wrapper for MicroPython mpremote tool.
* [uPyExplorer](https://github.com/RetepRelleum/uPyExplorer) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2022-02-20 - Explorer for MicroPython Device.
* [mpsync](https://github.com/thilomichael/mpsync) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2020-09-26 - A tool that automatically synchronizes code to a MicroPython board.
* [MPRemoteEditor](https://github.com/joewez/MPRemoteEditor) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2022-08-28 - A simple Windows IDE for developing with MicroPython MPRemote devices.

### Tools

* [belay](https://github.com/BrianPugh/belay) ⭐ 265 | 🐛 2 | 🌐 Python | 📅 2025-12-13 - Belay is a Python library that enables the rapid development of projects that interact with hardware via a MicroPython-compatible board.
* [ESP-File\_manager](https://github.com/mispacek/ESP-File_manager) ⭐ 18 | 🐛 3 | 🌐 JavaScript | 📅 2024-07-18 - Web-based file manager directly running on ESP32 in MicroPython.
* [mcu\_serial](https://github.com/gitcnd/mcu_serial) ⭐ 3 | 🐛 0 | 🌐 Perl | 📅 2024-07-28 - Command line serial emulator to connect to MicroPython boards.

## Miscellaneous

* [MicroPython Kickstarter](https://www.kickstarter.com/projects/214379695/micro-python-python-for-microcontrollers) - 1,931 backers pledged £97,803 to help bring this project to life.
* [MicroPython on the ESP8266 Kickstarter](https://www.kickstarter.com/projects/214379695/micropython-on-the-esp8266-beautifully-easy-iot) - 1,399 backers pledged £28,534 to help bring this project to life.

## Contributing

Contributions and suggestions are always welcome! Please take a look at the [contribution guidelines](https://github.com/mcauser/awesome-micropython/blob/master/contributing.md) ⭐ 1,744 | 🐛 7 | 🌐 HTML | 📅 2026-02-11 first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could vote for them by adding 👍 to them.
