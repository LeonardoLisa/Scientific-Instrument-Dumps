<!--
Filename: README.md
Version: 1.1.0
Date: 2026-08-27
Author: Leonardo Lisa
Description: Main repository documentation for scientific instrument dumps, PCB images, and calibration data.
-->

# Scientific Instrument Archive

A centralized repository for preserving firmware dumps, ROM images, EEPROM calibration data, and high-resolution internal PCB photography of scientific and laboratory test equipment. 

This repository aims to assist electronics engineers, metrology enthusiast, and researchers in repairing, maintaining, and reverse-engineering measurement instruments.

## Repository Structure

The repository is flattened and organized strictly by `Brand_Model` for immediate access. Follow a treemap example.

```text
.
├── Advantest_TQ8325/
│   ├── Firmware/          # Binaries, hex files, EEPROM dumps
│   ├── Calibration/       # Factory calibration constants
│   ├── PCB_Photos/        # High-res teardown images
│   └── Notes.md
└──  Wiltron-Anritsu_37269B/
```

## Disclaimer

**USE AT YOUR OWN RISK.** 
Flashing firmware or writing EEPROM data to scientific equipment carries a significant risk of bricking the device, erasing factory calibration constants, or destroying front-end analog hardware. 

All trademarks, logos, and brand names are the property of their respective owners. The inclusion of OEM firmware dumps does not imply endorsement by or affiliation with these manufacturers. The repository maintainers assume zero liability for damaged equipment, voided warranties, or corrupted calibration data resulting from the use of these files.

## License

*   **Repository Structure & Custom Scripts:** [GNU GPLv3](LICENSE-GPLv3)
*   **Original Documentation & PCB Photography:** [CC BY-SA 4.0](LICENSE-CC)
*   **Firmware/ROM Dumps:** Provided "as-is" under Fair Use exemptions for the express purposes of repair, maintenance, and interoperability.
