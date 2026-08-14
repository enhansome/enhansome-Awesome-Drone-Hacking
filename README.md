<!--lint disable awesome-toc-->

# Awesome Drone Hacking with stars

<!-- markdownlint-disable MD033 -->

<p align="center">
  <a href="https://x.com/intent/tweet?text=Awesome%20Drone%20Hacking%20-%20A%20list%20of%20awesome%20drone%20hacking%20tools%20and%20resources.%0Ahttps%3A%2F%2Fgithub.com%2Fnicholasaleks%2FAwesome-Drone-Hacking&hashtags=awesomelists,drone,hacking,cybersecurity,infosec" target="_blank">
    <img src="https://img.shields.io/badge/Tweet--lightgrey?logo=x&style=social" alt="Tweet" height="20"/>
  </a>

  <img alt="Deadlinks Checked" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/deadlinks.yml/badge.svg">
  <img alt="Awesome Lint" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/awesome-lint.yml/badge.svg">
  <img alt="YAML Lint" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/yamllint.yml/badge.svg">
  <img alt="Action Lint" src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/actions/workflows/actionlint.yml/badge.svg">

  <a href="https://github.com/nicholasaleks/Awesome-Drone-Hacking/graphs/contributors">
    <img alt="Contributors" src="https://img.shields.io/github/contributors/nicholasaleks/Awesome-Drone-Hacking.svg">
  </a>
  <a href="https://github.com/nicholasaleks/Awesome-Drone-Hacking/stargazers">
    <img src="https://img.shields.io/github/stars/nicholasaleks/Awesome-Drone-Hacking.svg?style=social" alt="Stars"/>
  </a>
  <a href="https://github.com/nicholasaleks/Awesome-Drone-Hacking/fork">
    <img src="https://img.shields.io/github/forks/nicholasaleks/Awesome-Drone-Hacking.svg?style=social" alt="Forks"/>
  </a>
</p>

<p align="center">
  <strong>A list of awesome drone hacking tools & resources.</strong><br/>
  <small><a href="README.md"><b>English</b></a> | <a href="README-ko.md">한국어</a></small><br/><br/>

<img
src="https://github.com/nicholasaleks/Awesome-Drone-Hacking/blob/main/Awesome-Drone-Hacking-Banner.png?raw=true"
alt="Awesome Drone Hacking List Logo" />

This repository covers tools, techniques, and research for hacking open-source,
autonomous, FPV (First-Person View), and proprietary drone systems—from telemetry
and flight control to hardware, firmware, and communication protocols.

</p>

*Legend*

* 🌟: Most Awesome
* 💰: Costs Money
* 👻: Outdated / Archived

<!-- markdownlint-enable MD033 -->

***

## 📚 Contents

<!--lint disable awesome-list-item-->

* [🔬 Drone Hacking Labs, CTFs & Workshops](#-drone-hacking-labs-ctfs--workshops)
* [🎤 Conference Talks & Videos](#-conference-talks--videos)
* [💿 Real-Time Operating Systems](#-real-time-operating-systems)
  * [Fuzzing & Analysis Tools](#fuzzing--analysis-tools)
  * [Emulators](#emulators)
* [🔌 Flight Controller & Embedded Systems](#-flight-controller--embedded-systems)
  * [Embedding Hacking Tools](#embedding-hacking-tools)
  * [Common Flight Controller & Embedded System Resources](#common-flight-controller--embedded-system-resources)
* [📻 Radio & Telemetry](#-radio--telemetry)
  * [Remote Identification Discovery & Spoofing Tools](#remote-identification-discovery--spoofing-tools)
  * [Telemetry Detection & Eavesdropping Tools](#telemetry-detection--eavesdropping-tools)
* [Misc RF Tools](#misc-rf-tools)
  * [Common Telemetry Radios](#common-telemetry-radios)
* [📶 Wi-Fi Communications](#-wi-fi-communications)
  * [Wi-Fi Detection & Infiltration Tools](#wi-fi-detection--infiltration-tools)
  * [Common Wi-Fi Protocols & Equipment](#common-wi-fi-protocols--equipment)
* [📺 FPV & Payloads](#-fpv--payloads)
  * [Video Eavesdropping](#video-eavesdropping)
* [📡 BVLOS Communications](#-bvlos-communications)
  * [Cellular Analysis & Tampering Tools](#cellular-analysis--tampering-tools)
  * [Common BVLOS Equipment](#common-bvlos-equipment)
* [🤖 Protocols & Middleware Tools](#-protocols--middleware-tools)
  * [Protocol Analysis & Tampering](#protocol-analysis--tampering)
* [💽 Autopilot Firmware](#-autopilot-firmware)
  * [Firmware Analysis](#firmware-analysis)
  * [Firmware Extraction](#firmware-extraction)
  * [Firmware Modification](#firmware-modification)
* [🧠 Companion Computers](#-companion-computers)
* [🛫 Ground Control Stations](#-ground-control-stations)
* [📱 Mobile GCS Apps](#-mobile-gcs-apps)
* [🧠 Artifical Intelligence Libraries](#-artifical-intelligence-libraries)
* [🏢 Vendor-Specific Research](#-vendor-specific-research)
  * [DJI](#dji)
  * [Parrot](#parrot)
  * [Misc](#misc)
* [📚 Research Papers & Blog Articles](#-research-papers--blog-articles)
* [🔍 OSINT & Intelligence](#-osint--intelligence)
* [💥 Exploits, CVEs & Vulnerabilities](#-exploits-cves--vulnerabilities)
* [📣 Vulnerability Disclosure Programs](#-vulnerability-disclosure-programs)
* [🎓 Training & Education](#-training--education)
* [🗣️ Communities](#-communities)
* [Additional Resources](#additional-resources)
* [⚖️ Legal Notice](#-legal-notice)

<!--lint enable awesome-list-item-->

## 🔬 Drone Hacking Labs, CTFs & Workshops

* [Damn Vulnerable Drone (DVD)](https://github.com/nicholasaleks/Damn-Vulnerable-Drone) ⭐ 773 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-08 - Docker-based virtual drone hacking simulator.
* [Hack Our Drone Workshop](https://dronewolf.darkwolf.io/workshop) - Dark Wolf Hack Our Drone Workshop.
* [Drone Wars, BloomCon](https://www.commonwealthu.edu/offices-directory/mathematics-computer-science-and-digital-forensics/drone-wars-competition) - Collegiate arena where teams hijack Wi‑Fi drones and race them through obstacles.
* [Hack The Drone](http://hackthedrone.org/eng/index.php) - International Drone Hacking Competition, Korea Drone Security Association.

## 🎤 Conference Talks & Videos

* [WTF WJI, UAV CTF?](https://ftp.fau.de/cdn.media.ccc.de/events/camp2023/h264-hd/camp2023-57063-eng-WTF_DJI_UAV_CTF_hd.mp4) - Felix Domke, cccamp23.
* [Debugging Microcontrollers](https://media.ccc.de/v/camp2023-57321-debugging_microcontrollers) - Niklas Hauser, ccamp23.
* [Demodulating 5GHz analog drone video](https://www.youtube.com/watch?app=desktop\&v=rl8ACNnjPFA) - Cemaxecuter, YouTube.
* [Game of Drones](https://www.slideshare.net/slideshow/def-con-25-2017-game-of-drones-brown-latimer-29july2017-slidespdf/250332791) - Bishopfox Dangerdrone.
* [Parrot Drones Hijacking](https://www.youtube.com/watch?v=66z-aXy_1Yo) - RSA2018 Video, Pedro Cabrera, March 2018 (Slides).
* [A Drone Tale, All your drones are belong to us](http://youtube.com/watch?v=aU4ULr3Lwt8) - Paolo Stagno, Hacktivity.
* [All your bebop drones still belong to us](https://www.youtube.com/watch?v=ra0nKHvaXnc) - Pedro Cabrera, Rooted CON, 2016.
* [Shelling out a "smart drone"](https://www.youtube.com/watch?v=IqCz-V6WMVg\&t=2875s) - Kevin Finisterre, Derbycon 2015.
* [Drones Hijacking - Multi dimensional attack vectors](https://www.youtube.com/watch?v=DFLofy789ko) - Aaron Luo, DEF CON 24, 2016.
* [Hacking a Professional Drone](https://www.youtube.com/watch?v=JRVb-xE1zTI\&t=470s) - Nils Rodday, Black Hat, 2016.
* [Avoiding CounterDrone Systems with NanoDrones](https://www.youtube.com/watch?v=pVmFxJPOu9I) - David Melendez Cano, DEF CON 26, 2018.
* [Game of Drones](https://www.youtube.com/watch?v=iG7hUE2BZZo) - Fran Brown & David Latimer, DEF CON 25, 2017.
* [Spread Spectrum techniques for anti drone evasion](https://www.youtube.com/watch?v=8Ng91UY3D2M) - David Melendez, Gabriela Garcia, DEF CON 31, 2023.
* [Knocking my neighbors kids cruddy drone offline](https://www.youtube.com/watch?v=5CzURm7OpAA) - Michael Robinson, DEF CON 23, 2015.
* [Practical Aerial Hacking & Surveillance](https://www.youtube.com/watch?v=knrvrR-B1ZI) - Glenn Wilkinson, DEF CON 22, 2015.
* [SkyJack - autonomous drone hacking](https://www.youtube.com/watch?v=EHKV01YQX_w) - Samy Kamkar, YouTube, 2013.
* [Icarus - Hacking and hijacking DSMx drones, RC devices](https://www.youtube.com/watch?v=abl6oOxLRXs) - Jonathan Andersson, PACSEC, 2016.

## 💿 Real-Time Operating Systems

### Fuzzing & Analysis Tools

* [American Fuzzy Lop plus plus](https://github.com/AFLplusplus/AFLplusplus) ⭐ 6,709 | 🐛 24 | 🌐 C | 📅 2026-08-13 - AFL with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn\_mode, and a lot more!
* [Avatar² Framework](https://github.com/avatartwo/avatar2) ⭐ 574 | 🐛 27 | 🌐 Python | 📅 2025-03-31 - Fuzzware is a project for automated, self-configuring fuzzing of firmware images.
* [Fuzzware](https://github.com/fuzzware-fuzzer/fuzzware) ⭐ 376 | 🐛 15 | 🌐 Python | 📅 2026-06-27 - The target orchestration framework with focus on dynamic analysis of embedded devices' firmware.

## Emulators

* [QEMU](https://www.qemu.org/) - A generic and open source machine emulator and virtualizer.
* [Renode](https://github.com/renode/renode) ⭐ 2,720 | 🐛 419 | 🌐 RobotFramework | 📅 2026-08-13 - Antmicro's open source simulation and virtual development framework for complex embedded systems. Supports many [STM32](https://github.com/renode/renode/blob/master/platforms/cpus/stm32f4.repl) ⭐ 2,720 | 🐛 419 | 🌐 RobotFramework | 📅 2026-08-13 series chips.

### Common RTOS

* [NuttX](https://nuttx.apache.org/) - NuttX RTOS, used by PX4.
* [ChibiOS](https://www.chibios.org/dokuwiki/doku.php) - ChibiOS RTOS, used by ArduPilot.

## 🔌 Flight Controller & Embedded Systems

### Embedding Hacking Tools

* [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - Detects and interacts with hardware debug ports like UART and JTAG.
* [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - Detects and interacts with hardware debug ports like UART and JTAG.
* [Tigard](https://www.crowdsupply.com/securinghw/tigard) - An open source FT2232H-based, multi-protocol, multi-voltage tool for hardware hacking.
* [JTAGULATOR](https://grandideastudio.com/portfolio/security/jtagulator/) - Detects JTAG Pinouts fast.
* [Saleae](https://www.saleae.com/) - Easy to use Logic Analyzer that support many protocols.
* [Ikalogic](https://www.ikalogic.com/sp209-logic-analyzer/) - Alternative to Saleae logic analyzers.
* [HydraBus](https://hydrabus.com/hydrabus-1-0-specifications/?v=0b3b97fa6688) - Open source multi-tool hardware similar to the BusPirate but with NFC capabilities.
* [ChipWhisperer](https://www.newae.com/chipwhisperer) - Detects Glitch/Side-channel attacks.
* [Glasgow](https://github.com/GlasgowEmbedded/Glasgow) ⭐ 2,191 | 🐛 80 | 🌐 Python | 📅 2026-08-12 - Tool for exploring and debugging different digital interfaces.
* [J-Link](https://www.segger.com/products/debug-probes/j-link/) - J-Link offers USB powered JTAG debug probes for multiple different CPU cores.

### Common Flight Controller & Embedded System Resources

* [STM32](https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html) - 32-bit Arm Cortex MCUs.
* [AT32](https://www.arterychip.com/en/product/AT32F425.jsp) - 32-bit Cortex-M4 microcontroller MUCs.
* [Pixhawk](https://pixhawk.org/) - Open source hardware flight controller.
* [Cube](https://www.cubepilot.com/#/home) - Modular flight controller hardware.
* [DJI A3](https://www.dji.com/ca/a3) - A commercial-grade flight controller offering triple-redundant IMUs and advanced fail-safes for industrial multirotors.
* [DJI N3](https://www.dji.com/ca/n3) - A flight controller designed for professional aerial cinematography, optimized for integration with the DJI Inspire 2 and Lightbridge 2.
* [CUAV X7 & V5+](https://ardupilot.org/copter/docs/common-cuav-x7-family-overview.html) - High-performance ArduPilot flight controllers with rich I/O and robust sensor redundancy.
* [Holybro Kakute F7/H7](https://holybro.com/products/kakute-h7-v2?srsltid=AfmBOorAjpi2nnbfkXOsFjFxvt8UiLFDPlo7vlpXIBhJMvUBZDkQ2fqW) - Compact Betaflight-compatible flight controllers popular in racing and freestyle drones.
* [PX4 Wiring Diagram](https://docs.px4.io/main/en/assembly/quick_start_pixhawk5x.html) - Official reference diagram for wiring Pixhawk 5X flight controllers running PX4.

## 📻 Radio & Telemetry

### Remote Identification Discovery & Spoofing Tools

* [RemoteID Spoofer](https://github.com/jjshoots/RemoteIDSpoofer) ⭐ 561 | 🐛 2 | 🌐 C | 📅 2025-09-26 - An ESP8266/NodeMCU tool that simulates up to 16 fake Remote ID–broadcasting drones around a GPS location via Wi‑Fi for Red Team testing.
* [DragonSync-iOS](https://github.com/Root-Down-Digital/DragonSync-iOS) ⭐ 272 | 🐛 0 | 🌐 Swift | 📅 2026-06-09 - Real-time Remote/Drone ID–compliant drone detection and monitoring on iOS/macOS.
* [WiFi RID capture](https://github.com/sxjack/unix_rid_capture) ⭐ 66 | 🐛 9 | 🌐 C | 📅 2023-04-20 - A Linux tool that listens for ASTM F3411 (Wi‑Fi/Bluetooth) Remote ID frames and logs real UAV positions in JSON for monitoring or analysis.
* [DJI DroneID Detection](https://www.crowdsupply.com/microphase-technology/antsdr-e200/updates/dji-droneid-detection) - FPGA-based software-defined radio based on the ZYNQ and AD936x chipsets.

### Telemetry Detection & Eavesdropping Tools

* [SiKW00F](https://github.com/nicholasaleks/sikw00f) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2025-08-03 - SiK Radio Detection & MAVLink Telemetry Eavesdropping Toolkit.
* [SiKening](https://github.com/MAVProxyUser/SiKening) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2015-09-28 - 3DR Radio SiKening PoC by Meatball Ninja - Brute force 3DR NetID and sync up with hopping sequence.

## Misc RF Tools

* [HackRF One](https://github.com/greatscottgadgets/hackrf) ⭐ 8,035 | 🐛 83 | 🌐 C | 📅 2026-08-12 - Software Defined Radio peripheral capable of transmission or reception of radio signals from 1 MHz to 6 GHz (half-duplex).
* [GNURadio](https://github.com/gnuradio/gnuradio) ⭐ 6,217 | 🐛 604 | 🌐 C++ | 📅 2026-07-09 - Free and Open Software Radio Ecosystem.
* [SDRangel](https://github.com/f4exb/sdrangel) ⭐ 3,907 | 🐛 93 | 🌐 C++ | 📅 2026-08-10 - Open-source Qt5 / OpenGL 3.0+ SDR and signal analyzer frontend to various hardware.
* [GQRX](https://github.com/gqrx-sdr/gqrx) ⭐ 3,654 | 🐛 263 | 🌐 C++ | 📅 2026-08-06 - Software defined radio receiver powered by GNU Radio and Qt.
* [SigDigger](https://github.com/BatchDrake/SigDigger) ⭐ 2,860 | 🐛 73 | 🌐 C++ | 📅 2026-02-11 - Free digital signal analyzer.
* [UberTooth One](https://github.com/greatscottgadgets/ubertooth) ⭐ 2,121 | 🐛 53 | 🌐 C | 📅 2026-03-19 - Open source 2.4 GHz wireless development platform suitable for Bluetooth experimentation.
* [Killerbee](https://github.com/riverloopsec/killerbee) ⭐ 845 | 🐛 31 | 🌐 C | 📅 2023-09-12 - Framework for Testing & Auditing ZigBee and IEEE 802.15.4 Networks.
* [zigdiggity](https://github.com/BishopFox/zigdiggity) ⭐ 298 | 🐛 7 | 🌐 Python | 📅 2021-09-13 - A ZigBee hacking toolkit by Bishop Fox.
* [SDR# (SDRSharp)](https://airspy.com/download/) - Airspy is a popular, affordable SDR (software defined radio.
* [Bluefruit LE Sniffer](https://www.adafruit.com/product/2269) - Easy to use Bluetooth Low Energy sniffer.
* [DragonOS](https://cemaxecuter.com/) - Ubuntu-based SDR distribution with preinstalled cellular tools.
* [RTL-SDR](https://www.rtl-sdr.com/buy-rtl-sdr-dvb-t-dongles/) - Cheapest SDR for beginners. It is a computer based radio scanner for receiving live radio signals frequencies from 500 kHz up to 1.75 GHz.
* [YardStick One](https://greatscottgadgets.com/yardstickone/) - Half-duplex sub-1 GHz wireless transceiver.
* [LimeSDR](https://www.crowdsupply.com/lime-micro/limesdr) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 100 KHz to 3.8 GHz (full-duplex).
* [BladeRF 2.0](https://www.nuand.com/bladerf-2-0-micro/) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 47 MHz to 6 GHz (full-duplex).
* [USRP B Series](https://www.ettus.com/product-categories/usrp-bus-series/) - Software Defined Radio peripheral capable of transmission or reception of radio signals from 70 MHz to 6 GHz (full-duplex).
* [ApiMote](https://apimote.com/) - ZigBee security research hardware for learning about and evaluating the security of IEEE 802.15.4/ZigBee systems. Killerbee compatible.

### Common Control & Telemetry Radios

* [RFD900X / RFD868X](https://files.rfdesign.com.au/Files/documents/RFD900x%20DataSheet%20V1.2.pdf) - Long-range radio data modem operating in the 902-928MHzor 865-870MHz frequency band.
* [3DR SiK Radio](https://store.3dr.com/3dr-sik-air-telemetry-radio-kit/) - SIK Air Telemetry Radio kit.
* [mRo SiK Radios](https://mrobotics.io/docs/mro-sik-telemetry-radio-v2/) - mRo SiK Telemetry Radio V2.
* [Holybro Sik Radios](https://holybro.com/products/sik-telemetry-radio-v3?srsltid=AfmBOorDhmwntjJAQDArI1vKzOLlMTaVHsFBltXve9pSeBN4d9LgGvDA) - SiK Telemetry Radio V3.
* [Microhard Telemetry Radios](https://docs.px4.io/main/en/telemetry/microhard_serial.html) - FHSS serial radios in 900 MHz/840 MHz/410–480 MHz bands; \~60 km range, mesh/point‑to‑point.
* [ExpressLRS](https://www.expresslrs.org/) - Open-source RC link that now supports bidirectional MAVLink passthrough with sub-10 ms latency—favoured by FPV pilots and DIY UAVs.
* [TBS Crossfire](https://www.team-blacksheep.com/products/prod:crossfire_tx?srsltid=AfmBOoqZ42ooZ6riBbs-Dec_6hXpMLN2u2njFGDQ5YWaFtzroDmUrZ0r) - Team Black Sheep Crossfire TX - Long Range R/C Transmitter.

## 📶 Wi-Fi Communications

### Wi-Fi Detection & Infiltration Tools

* [Bettercap](https://github.com/bettercap/bettercap) ⭐ 19,789 | 🐛 43 | 🌐 Go | 📅 2026-08-13 - MITM framework to hijack drone app traffic.
* [WifiPhisher](https://github.com/wifiphisher/wifiphisher) ⭐ 14,767 | 🐛 353 | 🌐 Python | 📅 2026-05-22 - Automated Evil Twin to phish Drone app creds.
* [Hack-a-drone](https://github.com/Ordina-JTech/hack-a-drone?tab=readme-ov-file) ⭐ 20 | 🐛 1 | 🌐 Java | 📅 2018-02-06 - A Java-based project allowing control of Wi‑Fi drones (e.g. Cheerson CX‑10) via app or keyboard, demonstrating remote command capabilities.
* [Aircrack-ng](https://aircrack-ng.org) - Deauth and WPA cracking toolkit.
* [DangerDrone](https://resources.bishopfox.com/resources/tools/drones-penetration-testers/attack-tools/) - A DIY penetration testing quadcopter platform announced at Black Hat 2016.
* [WASP](https://www.suasnews.com/2010/08/wi-fi-aerial-surveillance-platform-wasp/) - Wireless Aerial Surveillance Platform.

### Common Wi-Fi Protocols & Equipment

* [WFB-ng](https://github.com/svpcom/wfb-ng) ⭐ 1,506 | 🐛 22 | 🌐 Python | 📅 2026-08-12 - Low‑latency UDP Wi‑Fi broadcast for FPV drones.
* [OpenIPC](https://openipc.org/) - Open firmware turning IP cameras into low‑cost FPV links.
* [RubyFPV](https://rubyfpv.com/) - Cross‑platform digital FPV stack for Wi‑Fi dongles.
* [RunCam WifiLink](https://shop.runcam.com/runcam-wifilink-based-on-openipc/) - 5.8 GHz Wi‑Fi FPV adapter with open protocol docs.

## 📺 FPV & Payloads

### Video Detection & Eavesdropping

* [RX5808 Pro Diversity](https://github.com/sheaivey/rx5808-pro-diversity) ⭐ 744 | 🐛 42 | 🌐 C++ | 📅 2024-02-21 - DIY 5.8 GHz FPV video receiver station with antenna diversity.
* [TVSharp](https://github.com/linuxuser2064/TVSharper) ⚠️ Archived - An analog TV decoder for the RTL-SDR (but sharper).
* [FPV DETECTION](https://github.com/Payalo64/FPV_DETECTED_1.2_5.8GHZ) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2025-02-25 - Raspberry Pi Pico-based FPV Detection Tool with 1.6 km range.
* [Meshtastic Detection Node (Drone Detection)](https://www.tindie.com/products/thewolfblitz7/fpv-meshtastic-detection-node-drone-detection/) - Mesh nodes designed to detect, and alert presence of 5.8GHz FPV analog video transmissions. They alert via Meshtastic and Serial USB.

### Video Jamming, Spoofing & Tampering

* [HackTV](https://github.com/fsphil/hacktv) ⚠️ Archived - Analogue TV transmitter for the HackRF.

## 📡 BVLOS Communications

### Cellular Analysis & Tampering Tools

* [LTE Sniffer](https://github.com/SysSec-KAIST/LTESniffer) ⭐ 2,215 | 🐛 25 | 🌐 C++ | 📅 2024-10-23 - Open-source LTE downlink/uplink eavesdropper.
* [QCSuper](https://github.com/P1sec/QCSuper) ⭐ 1,637 | 🐛 121 | 🌐 Python | 📅 2026-07-23 - Capture 2G-4G traffic using Qualcomm phones.
* [gr-gsm](https://github.com/ptrkrysik/gr-gsm) ⭐ 1,492 | 🐛 163 | 🌐 C++ | 📅 2025-03-10 - GSM analysis with GNU Radio.
* [LTE-Cell-Scanner](https://github.com/Evrytania/LTE-Cell-Scanner) ⭐ 665 | 🐛 33 | 🌐 C++ | 📅 2019-02-26 - LTE cell detection and analysis.
* [FALCON LTE](https://github.com/falkenber9/falcon) ⭐ 356 | 🐛 16 | 🌐 C++ | 📅 2023-10-13 - Fast Analysis of LTE Control Channels for real-time analysis.
* [Kalibrate](https://github.com/scateu/kalibrate-hackrf) ⭐ 306 | 🐛 18 | 🌐 C++ | 📅 2022-03-21 - GSM base station scanner and frequency calibration tool.
* [5GBaseChecker](https://github.com/SyNSec-den/5GBaseChecker) ⭐ 116 | 🐛 3 | 🌐 C | 📅 2025-01-22 - Tool for detecting vulnerabilities in 5G baseband implementations (2024).
* [Modmobmap](https://github.com/Synacktiv-contrib/Modmobmap) ⭐ 111 | 🐛 4 | 🌐 Python | 📅 2023-03-24 - Mobile network mapping.
* [Modmobjam](https://github.com/Synacktiv-contrib/Modmobjam) ⭐ 104 | 🐛 3 | 🌐 Python | 📅 2020-05-30 - Mobile jamming research.
* [OsmocomBB](https://github.com/korczis/osmocom-bb) ⭐ 62 | 🐛 1 | 🌐 C | 📅 2026-08-08 - Free firmware for mobile phone baseband processors.

### Common BVLOS Equipment

* [CUAV SR 4/5G Link](https://doc.cuav.net/link/lte-link/en/) - LTE LINK series communication link is a UAV link, independently supported by CUAV.
* [Iridium RockBlock](https://docs.px4.io/main/en/advanced_features/satcom_roadblock.html) - Satellite Communications Module.
* [Cloud Walker](https://www.cloudwalkerfpv.com/) - Optical Fiber Digital Communication Module.
* [OpenBTS](https://github.com/PentHertz/OpenBTS) ⭐ 315 | 🐛 0 | 🌐 C++ | 📅 2026-07-29 - GSM+GPRS Radio Access Network Node reloaded for 2024-2025 for newest UHD drivers and supporting Ubuntu 22.04 & 24.04.
* [LimeNET CrowdCell](https://limemicro.com/) - Network in a box solution with integrated LimeSDR for small cell deployments.
* [Magma Core Network](https://github.com/magma) - Meta's distributed packet core now under Linux Foundation.

## 🤖 Protocols & Middleware Tools

* [MAVLink](https://github.com/mavlink/mavlink) ⭐ 2,392 | 🐛 140 | 🌐 Python | 📅 2026-08-13 - Marshalling / communication library for drones.
* [MAVROS](https://github.com/mavlink/mavros) ⭐ 1,207 | 🐛 410 | 🌐 C++ | 📅 2026-08-14 - MAVLink to ROS gateway with proxy for Ground Control Station.
* [MAVSDK](https://github.com/mavlink/MAVSDK) ⭐ 921 | 🐛 43 | 🌐 C++ | 📅 2026-08-12 - API and library for MAVLink compatible systems written in C++17.
* [MAVLink Router](https://github.com/mavlink-router/mavlink-router) ⭐ 610 | 🐛 79 | 🌐 C++ | 📅 2026-07-13 - Route mavlink packets between endpoints.
* [ROS](https://www.ros.org/) - Open Source Robot Operation System (ROS).

### Protocol Analysis & Tampering

* [aztarna](https://github.com/aliasrobotics/aztarna) ⚠️ Archived - ROS Footprinting Tool.
* [MAVSploit](https://github.com/Rud3m/MavSploit) ⭐ 9 | 🐛 1 | 🌐 Lua | 📅 2026-02-11 - Pentesting toolkit designed specifically for identifying and exploiting vulnerabilities within the MavLink communication protocol.
* [MAVLink Wireshark PLugin](https://mavlink.io/en/guide/wireshark.html) - Parsing MAVLink Messages in Wireshark.

## 💽 Autopilot Firmware

* [Betaflight](https://github.com/betaflight/betaflight) ⭐ 11,406 | 🐛 348 | 🌐 C | 📅 2026-08-13 - Open Source Flight Controller Firmware for FPV Drones.
* [iNav](https://github.com/iNavFlight/inav) ⭐ 4,182 | 🐛 433 | 🌐 C | 📅 2026-08-05 - Navigation-enabled flight control software.
* [ArduPilot](https://ardupilot.org/) - Trusted, versatile, and open source autopilot system supporting many vehicle types.
* [PX4](https://px4.io/) - Open Source Autopilot fro Drone Developers.

### Firmware Analysis

* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) ⭐ 72,347 | 🐛 1,905 | 🌐 Java | 📅 2026-08-13 - Software Reverse Engineering suite; handles arbitrary binaries, if you provide CPU architecture and endianness of the binary.
* [Radare2](https://github.com/radareorg/radare2) ⭐ 24,567 | 🐛 824 | 🌐 C | 📅 2026-08-13 - Software Reverse Engineering framework, also handles popular formats and arbitrary binaries, has an extensive command line toolset.
* [Binwalk](https://github.com/ReFirmLabs/binwalk) ⭐ 14,227 | 🐛 91 | 🌐 Rust | 📅 2026-08-11 - Searches a binary for "interesting" stuff, as well as extracts arbitrary files.
* [emba](https://github.com/e-m-b-a/emba) ⭐ 3,593 | 🐛 26 | 🌐 Shell | 📅 2026-08-11 - Analyze Linux-based firmware of embedded devices.
* [cwe\_checker](https://github.com/fkie-cad/cwe_checker) ⭐ 1,348 | 🐛 30 | 🌐 Rust | 📅 2026-07-24 - Finds vulnerable patterns in binary executables - ELF support for x86, ARM, and MIPS, experimental bare-metal support.
* [Firmwalker](https://github.com/craigz28/firmwalker) ⭐ 1,221 | 🐛 5 | 🌐 Shell | 📅 2023-08-29 - Searches extracted firmware images for interesting files and information.
* [JTAGenum](https://github.com/cyphunk/JTAGenum) ⭐ 799 | 🐛 13 | 🌐 C++ | 📅 2023-10-30 - Add JTAG capabilities to an Arduino.
* [Firmware Slap](https://github.com/ChrisTheCoolHut/Firmware_Slap) ⭐ 476 | 🐛 10 | 🌐 Python | 📅 2020-09-17 - Discovering vulnerabilities in firmware through concolic analysis and function clustering.
* [Trommel](https://github.com/CERTCC/trommel) ⚠️ Archived - Searches extracted firmware images for interesting files and information.
* Firmware Analysis Toolkit
* [OpenOCD](https://openocd.org/) - Free and Open On-Chip Debugging, In-System Programming and Boundary-Scan Testing.

### Firmware Extraction

* [DJI Firmware Tools](https://github.com/o-gs/dji-firmware-tools) ⭐ 2,171 | 🐛 276 | 🌐 C | 📅 2026-07-21 - Utilities to extract, modify, and rebuild DJI drone firmware modules—including calibration, parameter editing, and repackaging for analysis.
* [flashrom](https://github.com/flashrom/flashrom) ⭐ 1,158 | 🐛 79 | 🌐 C | 📅 2026-08-07 - Tool for detecting, reading, writing, verifying and erasing flash chips.
* [Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit) ⭐ 997 | 🐛 62 | 🌐 C | 📅 2026-02-17 - Extraction tools for several container formats.
* [Cotopaxi](https://github.com/Samsung/cotopaxi) ⭐ 362 | 🐛 1 | 🌐 Python | 📅 2024-05-31 - Set of tools for security testing of Internet of Things devices using specific network IoT protocols.
* [dumpflash](https://github.com/ohjeongwook/dumpflash) ⭐ 321 | 🐛 21 | 🌐 Python | 📅 2022-03-17 - Low-level NAND Flash dump and parsing utility.
* [Samsung Firmware Magic](https://github.com/chrivers/samsung-firmware-magic) ⭐ 237 | 🐛 8 | 🌐 Python | 📅 2021-04-11 - Decrypt Samsung SSD firmware updates.
* [FACT Extractor](https://github.com/fkie-cad/fact_extractor) ⭐ 90 | 🐛 44 | 🌐 Python | 📅 2026-07-31 - Detects container format automatically and executes the corresponding extraction tool.
* [The SRecord package](https://srecord.sourceforge.net/) - Collection of tools for manipulating EPROM files (can convert lots of binary formats).

### Firmware Modification

* [DJI FC Patcher](https://github.com/o-gs/DJI_FC_Patcher) ⭐ 82 | 🐛 14 | 🌐 Python | 📅 2020-01-26 - Custom FC Patcher and Flashing for various DJI drones.
* [WAF](https://github.com/ArduPilot/waf) ⭐ 18 | 🐛 2 | 🌐 Python | 📅 2024-10-10 - Python-based Ardupilot Firmware Compiler.

## 🧠 Companion Computers

### Companion Network Analysis

* [Wireshark](https://www.wireshark.org/) - Network traffic analyzer.
* [NMAP](https://nmap.org/) - Network Mapping Tool.

### Companion Web Application Attacking

* [BurpSuite](https://portswigger.net/) - Web application security testing tooling, provides automated testing & external plugins.

## 🛫 Ground Control Stations

* [QGround Control](https://github.com/mavlink/qgroundcontrol) ⭐ 4,842 | 🐛 983 | 🌐 C++ | 📅 2026-08-13 - Cross-platform ground control station for drones.
* [MAVProxy](https://github.com/ArduPilot/MAVProxy) ⭐ 590 | 🐛 273 | 🌐 Python | 📅 2026-08-14 - CLI-based GCS Software.
* [Mission Planner](https://ardupilot.org/planner/) - Windows-based GCS Software.

## 📱 Mobile GCS Apps

* [Apktool](https://github.com/iBotPeaches/Apktool) ⭐ 25,276 | 🐛 77 | 🌐 Java | 📅 2026-08-11 - A tool for reverse engineering Android apk files.
* [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) ⭐ 21,596 | 🐛 20 | 🌐 JavaScript | 📅 2026-08-10 - Automated, all in one mobile application hacking.
* [Dex2Jar](https://github.com/pxb1988/dex2jar) ⭐ 13,133 | 🐛 379 | 🌐 Java | 📅 2024-07-21 - Tools to work with android .dex and java .class files.
* [Androguard](https://github.com/androguard/androguard) ⭐ 6,195 | 🐛 46 | 🌐 Python | 📅 2026-08-13 - Reverse engineering and pentesting for Android applications.
* [ADB Toolkit](https://github.com/ASHWIN990/ADB-Toolkit) ⭐ 2,010 | 🐛 24 | 🌐 Shell | 📅 2024-08-18 - ADB-Toolkit V2 for easy ADB tricks with many perks in all one.
* [Enjarify](https://github.com/Storyyeller/enjarify) ⭐ 953 | 🐛 8 | 🌐 Python | 📅 2021-11-07 - Tool for translating Dalvik bytecode to equivalent Java bytecode. This allows Java analysis tools to analyze Android applications.

## 🧠 Artifical Intelligence Libraries

* [OpenCV](https://github.com/opencv/opencv) ⭐ 90,422 | 🐛 2,752 | 🌐 C++ | 📅 2026-08-13 - Open Source Computer Vision Library.

## 🏢 Vendor-Specific Research

### DJI

* [Drone-ID Receiver for DJI OcuSync 2.0](https://github.com/RUB-SysSec/DroneSecurity) ⭐ 1,303 | 🐛 21 | 🌐 Python | 📅 2023-03-10
* [DJI Drone ID](https://github.com/proto17/dji_droneid) ⭐ 535 | 🐛 35 | 🌐 MATLAB | 📅 2024-05-27 - An SDR-based decoder that demodulates proprietary DJI DroneID RF bursts and allows creation of arbitrary DroneID frames using MATLAB/Octave scripts.
* [deejaeye-Modder](https://github.com/Bin4ry/deejayeye-modder) ⭐ 396 | 🐛 42 | 🌐 Smali | 📅 2021-12-09 - DJI Drone Firmware Modding Tool.
* [DroneXtract](https://github.com/ANG13T/DroneXtract) ⭐ 363 | 🐛 6 | 🌐 Go | 📅 2023-07-19 - Digital forensics suite for DJI drones.
* [dji\_rev](https://github.com/fvantienen/dji_rev) ⭐ 317 | 🐛 7 | 🌐 C++ | 📅 2017-09-13 - DJI Reverse Engineering Toolkit.
* [DUMLdore](https://github.com/jezzab/DUMLdore) ⚠️ Archived - DJI Firmware Flashing Tool v3.20.
* [RedHerring](https://github.com/MAVProxyUser/P0VsRedHerring) ⭐ 116 | 🐛 5 | 🌐 Ruby | 📅 2017-09-13 - FTPD directory transversal 0day.
* [pyduml](https://github.com/hdnes/pyduml) ⭐ 59 | 🐛 6 | 🌐 Python | 📅 2019-08-31 - Python based DUML "DJI Universal Markup Language" Exploit & FW upgrade/downgrade tool.
* [DUMLrub](https://github.com/MAVProxyUser/DUMLrub) ⭐ 48 | 🐛 5 | 🌐 Ruby | 📅 2022-04-23 - Ruby port of PyDUML.
* [Drone Hacks](https://drone-hacks.com/) - DJI Drone Hacking Tool for purchase.
* [No Limit Drones](https://nolimitdronez.com/) - DJI Drone Hacking Tool for purchase.

### Parrot

* [SkyJack](https://github.com/samyk/skyjack) ⭐ 1,828 | 🐛 4 | 🌐 JavaScript | 📅 2017-11-21 - Drone source used to autonomously seek out, hack, and wirelessly take full control over any other Parrot or 3DR drones.
* [DroneJack](https://github.com/brospars/wic-ter-dronejack) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-09 - Dronejack is a node web-based application to take control of a Parrot drone.
* [Maldrone](https://www.youtube.com/watch?v=5SlWdl4ZuAI) - First Backdoor for Drones.

### Misc

* [DroneSploit](https://github.com/dronesploit/dronesploit) ⭐ 1,994 | 🐛 2 | 🌐 Python | 📅 2024-11-23 - Drone pentesting framework console.
* [Drone-Hacking-Tool](https://github.com/HKSSY/Drone-Hacking-Tool) ⚠️ Archived - Drone Hacking Tool is a GUI tool that works with a USB Wifi adapter and HackRF One for hacking drones.
* [Snoopy](https://github.com/sensepost/Snoopy) ⭐ 613 | 🐛 11 | 🌐 Python | 📅 2012-12-07 - A distributed tracking and data interception framework.
* [Drone Duel](https://github.com/marcnewlin/drone-duel) ⭐ 24 | 🐛 3 | 🌐 Python | 📅 2016-06-13 - Code used in the Great Drone Duel of 2016.

## 📚 Research Papers & Blog Articles

* [Vulnerability Analysis of the MAVLink Protocol for Command and Control of Unmanned Aircraft](https://apps.dtic.mil/sti/citations/ADA598977) - A DoD/AFIT technical report identifying confidentiality, integrity, and availability flaws in MAVLink C2 messages, enabling crafted attacks on UAV missions.
* [How to Set Up A Drone Vulnerability Testing Lab](https://medium.com/@swalters/how-to-set-up-a-drone-vulnerability-testing-lab-db8f7c762663) - A Medium guide detailing a <$100 home drone security lab using toy/hobby drones and RC systems, upgradable to advanced gear like DJI and Futaba.
* [GPS Jamming Techniques for UAVs using Low-Cost SDR Platforms](https://www.researchgate.net/publication/339824302_Effective_GPS_Jamming_Techniques_for_UAVs_Using_Low-Cost_SDR_Platforms) - A research paper showing BladeRF/GNU Radio SDR can generate effective GPS interference to disrupt UAV navigation.
* [Unmanned Aircraft Capture and Control via GPS Spoofing](https://rnl.ae.utexas.edu/images/stories/files/papers/unmannedCapture.pdf) - A seminal study demonstrating UAV takeover by injecting deceptive GPS signals under specific conditions.
* [Drone Detection and Tracking Using RF Identification Signals](https://www.mdpi.com/1424-8220/23/17/7650) - An MDPI study presenting a dev‑board RF system decoding Drone‑ID telemetry with detection ranges of up to \~3.7 km on various DJI models.

## 🔍 OSINT & Intelligence

* [DJI Hardware Schematics](https://github.com/o-gs/dji-hardware-schematics) ⭐ 243 | 🐛 4 | 📅 2021-05-08 - Community-shared KiCad schematics and PCBs for various DJI drone boards, though may contain errors and lack warranty.
* [DJI Packet Dumps](https://github.com/o-gs/dji-packet-dumps) ⭐ 38 | 🐛 3 | 📅 2018-01-05 - Collections of DJI hardware communication logs in PCAP format, useful for protocol analysis in Wireshark.
* [The Drone Database](https://drones.cnas.org/drones/) - Detailed information on drones from around the world. Perfect for research, analysis, and staying informed about global drone capabilities.

## 💥 Exploits, CVEs & Vulnerabilities

* [Exploit Database](https://www.exploit-db.com/) - A large, public, CVE‑compliant repo of exploits and proof‑of‑concept code for penetration testers and researchers.
* [Robot Vulnerability Database](https://github.com/aliasrobotics/RVD) ⭐ 241 | 🐛 227 | 🌐 Python | 📅 2026-07-14 - An open archive tracking robot/ROS vulnerabilities with RVSS scoring, curated by Alias Robotics.

## 📣 Vulnerability Disclosure Programs

* [PX4](https://github.com/PX4/PX4-Autopilot/blob/main/SECURITY.md) ⭐ 12,415 | 🐛 342 | 🌐 C++ | 📅 2026-08-14 - PX4 Security Policy.
* [QGround Control](https://github.com/mavlink/qgroundcontrol/security) ⭐ 4,842 | 🐛 983 | 🌐 C++ | 📅 2026-08-13 - QGround Control Vulnerability Disclosure.
* [ArduPilot](https://github.com/ArduPilot/MethodicConfigurator/security) ⭐ 147 | 🐛 21 | 🌐 Python | 📅 2026-08-13 - ArduPilot Vulnerability Disclosure.
* [DJI](https://security.dji.com) - Official DJI program offering $50–$30 k rewards.
* [Parrot](https://www.parrot.com/en/newsroom/parrot-launches-its-bug-bounty-partnership-yeswehack) - Parrot runs a phased YesWeHack bug bounty program.
* [Autel Robotics](https://www.autelrobotics.com/protocol/) - Autel Robotics Vulnerability Disclosure.
* [ROS](https://ros.org/reps/rep-2006.html) - ROS Vulnerability Disclosure Policy.
* [DroneDeploy](https://help.dronedeploy.com/hc/en-us/articles/1500004862001-Vulnerability-Reporting-Policy) - DroneDeploy Vulnerability Reporting Policy.
* [Zipline](https://www.zipline.com/zipline-vulnerability-disclosure-policy) - Zipline Vulnerability Disclosure Policy.
* [IRIS Automation / uAvioni](https://www.irisonboard.com/responsible-disclosure/) - IRIS Automation / uAvioni Vulnerability Disclosure.
* [Ameta](https://ametasmart.com/pages/ameta-vulnerability-disclosure-policy) - Ameta Vulnerability Disclosure Policy.
* [Ouster](https://ouster.com/responsible-disclosure-policy) - Ouster Responsible Disclosure Policy.

## 🎓 Training & Education

* [DSOC - DronSec Courses](https://training.dronesec.com/) - Master Offensive Operations & Adversary Tradecraft for Drones.
* [DarkWolf Drone Playbook](https://dronewolf.darkwolf.io/) - Drone Hacking Playbook Developed by Dark Wolf Solutions.

## 🗣️ Communities

* [Dronecode foundation](https://dronecode.org/) - Home for MavLink, QGroundcontrol and PX4, part of Linux foundation.
* [FPV Freedom Coalation](https://fpvfc.org/) - Keep drones hackabel and safe.
* \#DeejayeyeHackingClub

### Who to Follow

#### Medium

* [Sander Walters](https://medium.com/@swalters)

#### X/Tweeter

* [d0tslash](https://x.com/d0tslash)

## Additional Resources

* [Awesome-Flying-FPV](https://github.com/Matthias84/awesome-flying-fpv) ⭐ 686 | 🐛 5 | 📅 2026-03-06 - Awesome Flying FPV List.
* [Awesome-Drones](https://github.com/janesmae/awesome-drones) ⭐ 626 | 🐛 11 | 📅 2024-11-05 - A curated list of Awesome Drones resources.

## ⚖️ Legal Notice

This repository is for educational and research purposes only. Users are responsible for complying with all applicable laws and regulations. The maintainers do not endorse or encourage any illegal activities.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
