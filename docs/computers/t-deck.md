# [T-Deck](t-deck.md) by LILYGO

## Overview

--8<-- "t-deck.md"


## Description

If you're looking to play with LoRa and [Meshtastic](https://meshtastic.org/) ("an open source, off-grid, decentralized, mesh network" used to send short messages between devices), you'll be in good company with a T-Deck. You'll find many Meshtastic enthusiasts in the articles and videos below describing their setup with a T-Deck. As of the end of 2024, this is still not quite a consumer-grade device. The firmware options are in active development and rough around the edges, and you'll probably be spending time configuring beta releases and dealing with some known bugs. For some of us, that experience is part of the charm.

But if you're looking to put a general purpose computer in your pocket, this is not the one for you. The T-Deck and T-Deck Plus by LILYGO distinguish themselves from the other computers listed here by their processor: an [Espressif ESP32-S3](https://www.espressif.com/en/products/socs/esp32-s3) system on a chip (SoC). This is a low-power energy-efficient microcontroller, and the software running on your T-Deck must be a specialized firmware developed specifically for this chip. You can't install a Linux distribution on this device, like you would with a general purpose single-board computer (SBC) like a Raspberry Pi.

Beyond LoRa and Meshtastic, the T-Deck can also serve as a dev kit for folks writing software for an ESP32 with a keyboard and a screen. It's a great hardware form factor, and the ESP32 is a versatile platform for systems programming. Examples of projects targeting the T-Deck as a hardware platform include the [T-Deck uLisp Machine](http://www.ulisp.com/show?4JAO) and an [MS-DOS emulator](https://www.hackster.io/news/chen-liang-is-turning-a-lilygo-t-deck-into-the-world-s-cutest-ibm-compatible-complete-with-windows-dd937d6da5cc).


## Articles & Videos

### Launch Coverage

<div class="grid cards" markdown>

-   :fontawesome-regular-newspaper:{ .lg .middle } **CNX Software**, *30 August 2024*

    [LILYGO T-Deck Plus – A Blackberry-like ESP32-S3 devkit with QWERTY keyboard, trackball, LoRa, GPS, battery, and more](https://www.cnx-software.com/2024/08/30/lilygo-t-deck-plus-a-blackberry-like-esp32-s3-devkit-with-qwerty-keyboard-trackball-lora-gps-battery-and-more/)

-   :fontawesome-regular-newspaper:{ .lg .middle } **Liliputing**, *13 August 2024*

    [LILYGO T-Deck Plus is a $70 handheld with GPS, LoRa, and a BlackBerry keyboard](https://liliputing.com/lilygo-t-deck-plus-is-a-70-handheld-with-gps-lora-and-a-blackberry-keyboard/)

-   :fontawesome-regular-newspaper:{ .lg .middle } **Hackster.io**, *13 August 2024*

    [LILYGO Upgrades the T-Deck, Adds LoRa as Standard and a New GPS Receiver](https://www.hackster.io/news/lilygo-upgrades-the-t-deck-adds-lora-as-standard-and-a-new-gps-receiver-badd82a199e0)

-   :fontawesome-regular-newspaper:{ .lg .middle } **Liliputing**, *30 June 2023*

    [LILYGO T-Deck is a $50 BlackBerry-like device with WiFi, Bluetooth and optional LoRa support](https://liliputing.com/lilygo-t-deck-is-a-50-blackberry-like-device-with-wifi-bluetooth-and-optional-lora-support/)

-   :fontawesome-regular-newspaper:{ .lg .middle } **Hackster.io**, *30 June 2023*

    [LILYGO's T-Deck Is an Espressif ESP32-S3-Powered BlackBerry-Like Handheld Dev Board](https://www.hackster.io/news/lilygo-s-t-deck-is-an-espressif-esp32-s3-powered-blackberry-like-handheld-dev-board-f96abddac8ea)

-   :fontawesome-regular-newspaper:{ .lg .middle } **CNX Software**, *30 June 2023*

    [ESP32-S3 board features 2.8-inch display, Blackberry-like keyboard, and optional LoRaWAN connectivity](https://www.cnx-software.com/2023/06/30/esp32-s3-board-features-2-8-inch-display-blackberry-like-keyboard-lorawan/)

</div>


### Reviews

<div class="grid cards" markdown>

-   :fontawesome-brands-youtube:{ .lg .middle } **Patrick Puma**, *26 October 2024* (6m25s video)

    [LilyGO T-Deck Plus Unboxing & Quick Start Guide | Meshtastic | Delivery Failed Fix](https://www.youtube.com/watch?v=z02orSn3Z9M)

-   :fontawesome-brands-youtube:{ .lg .middle } **Level 2 Jeff [Geerling]**, *12 October 2024* (6m45s video)

    [This device makes Meshtastic the BEST off-grid tech](https://www.youtube.com/watch?v=2Ry-ck0fhfw)

-   :fontawesome-brands-youtube:{ .lg .middle } **That Project**, *2 October 2024* (8m45s video)

    [T-Deck/T-Deck Plus & T-Beam+iPhone with Meshtastic: Off-Grid LoRa Communication](https://www.youtube.com/watch?v=Uqe4jNwf_ZU)

-   :fontawesome-brands-youtube:{ .lg .middle } **Volos Projects**, *27 September 2024* (8m12s video)

    [I Am Finally Using LoRA! And I love IT!! LilyGO T-Deck Plus](https://www.youtube.com/watch?v=r359L7tbqdA)

-   :fontawesome-brands-youtube:{ .lg .middle } **ObviateIO**, *12 September 2024* (0m57s video)

    [First look at the LilyGo T-Deck Plus for Meshtastic](https://www.youtube.com/shorts/G08j1pzbCAI)

-   :fontawesome-brands-youtube:{ .lg .middle } **andy kirby**, *30 August 2024* (10m43s video)

    [Introducing the T-Deck Plus](https://www.youtube.com/watch?v=qshLuCqOn3I)

-   :fontawesome-brands-youtube:{ .lg .middle } **HackedExistence**, *11 March 2024* (12m23s video)

    [Lilygo TDeck Meshtastic Build - Battery, GPS, LoRa Antenna, 3D Printed Case](https://www.youtube.com/watch?v=2PB-nGgZSpQ)

-   :fontawesome-brands-youtube:{ .lg .middle } **Ravenwood Acres**, *22 December 2023* (9m55s video)

    [The Lilygo T-Deck a Game changer | Meshtastic](https://www.youtube.com/watch?v=L1hvsYEX7WE)

-   :fontawesome-brands-youtube:{ .lg .middle } **The Comms Channel**, *16 October 2023* (7m24s video)

    [Lilygo T-Deck and Meshtastic - Encrypted Comms](https://www.youtube.com/watch?v=1oaWRs2te68)

-   :fontawesome-brands-youtube:{ .lg .middle } **ShotokuTech**, *31 July 2023* (13m29s video)

    [Getting Started with the T-Deck from LilyGo](https://www.youtube.com/watch?v=W5E6ZDTYt-s)

</div>


### Alternative firmware

<div class="grid cards" markdown>

-   :fontawesome-brands-youtube:{ .lg .middle } **Katherine McNamara**, *25 November 2024* (11m13s video)

    [Installing the fancy UI Meshtastic image on the Lilygo T-Deck Plus](https://www.youtube.com/watch?v=f0zZfnctZQw)

-   :fontawesome-brands-youtube:{ .lg .middle } **TechAirSpace**, *9 November 2024* (3m25s video)

    [Easy Way To Build T-Deck Meshtastic Fancy UI!](https://www.youtube.com/watch?v=LBJVCYypIG0)

-   :fontawesome-brands-youtube:{ .lg .middle } **TechAirSpace**, *25 October 2024* (3m33s video)

    [Run Multiple Firmware On T-Deck!](https://www.youtube.com/watch?v=RazJejeO-EI)

-   :fontawesome-regular-newspaper:{ .lg .middle } **Jeff Geerling's Blog**, *11 October 2024*

    [Realizing Meshtastic's Promise with the T-Deck](https://www.jeffgeerling.com/blog/2024/realizing-meshtastics-promise-t-deck)

-   :fontawesome-brands-youtube:{ .lg .middle } **Matt Calhoun**, *7 October 2024* (8m37s video)

    [Setting up ChatterBox Firmware on T-Deck Plus for Secure Off-Grid Mesh Texting](https://www.youtube.com/watch?v=89AHWO5_BKM)

-   :fontawesome-brands-youtube:{ .lg .middle } **JuliansRandomProject**, *9 June 2024* (12m13s video)

    [Meshtastic Fancy New UI & V4V](https://www.youtube.com/watch?v=mtFwETD7nY4)

-   :fontawesome-regular-newspaper:{ .lg .middle } **Hackster.io**, *1 October 2023*

    [LILYGO T-Deck Support: The Ripple QWERTY firmware has been ported to the T-Deck!](https://www.hackster.io/scottpowell69/lilygo-t-deck-support-45e7ed)

</div>
