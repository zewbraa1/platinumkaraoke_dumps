# Platinum-Karaoke-Dumps
This Repo contains firmware dumps (SPI Flash/EEPROM) for Sunplus SPHE82xx based Platinum Karaoke systems (Platinum X-10+/KS-10 Junior 2) for repair and archival purposes and not intended to facilitate the infringement of any copyrights or participate in any illegal activities.


## KS-10 Junior 2
- **SoC:** Sunplus SPHE8203R
- **Flash Chip:** Eon EN25Q32B (4MB)
- **RAM Chip:** ESMT M12L64164A-6T6 4Mb (8MB)
- **Dump Method:** CH341B (3.3V) via SOP8 Clip (In Circuit Serial Programming)

## X-10/T-40 Plus
- **SoC:** ESS DMP™3 ES6430FAA 
- **Flash Chip:** Macronix MX29LV320EBI-70G (32Mb/4MB)
- **SDRAM Chip:** Samsung K422816320-LC60 166MHz (128Mbit/16MB)
- **Dump Method:** CH341B (3.3V) via SOP8 Clip (In Circuit Serial Programming)

 ## Programmer
- Ch341B Black (3.3v version)
- Make sure you are using  the 3.3v version and NOT the 5v version or you might get errors while reading/writing!
  
---

## Disclaimer & Legal Notice
This repository is intended for **educational, archival, and repair purposes only**. 

- **No Copyright Infringement Intended:** These dumps are provided to assist technicians in restoring bricked hardware.
- **No Song Data:** This repository does NOT contain proprietary karaoke song databases, lyrics, or copyrighted music files.
- **Right to Repair:** This project supports the maintenance of user-owned hardware, specifically for devices that are out of warranty. It aims to provide owners with the tools needed to restore their own equipment from firmware-related failures.

It is not intended to facilitate the infringement of any copyrights or participate in any illegal activities.


UPDATE 8:33PM GMT+8 April 15, 2026: I just dumped the EEPROM on my Platinum X-10+ most of the data weren't really useful, but i'll include the dump anyways.
You could try this with an X-10+ or basically any T/X/BMB models i guess? but please make sure you have a dump of the old EEPROM IC before proceeding.
You could also try a new EEPROM Chip without anything on it, basically empty. 


## Comments
 The EEPROM dump that i included for the X-10/T-40 Plus dosent include the DVD firmware, it only stores configuration like songs incase the player cut power, it can store the unplayed songs.


