AMX NetLinx NI-Series Legacy Support
Revitalizing NI-2100, NI-3100, and NI-4100 Systems

🚀 Introduction
There is a massive lack of accessible, clear information for these workhorse masters. This project provides a central "brain trust" and a structured path to get these systems operational.

Note on Numbering: Files prepended with a number (e.g., 1_...) are mandatory. You must complete or possess these files in order to have a functioning system. Unnumbered files are optional resources.

📂 Project Structure & Dependencies
Follow these files in numerical order to ensure a successful deployment:

1_Software.txt * Mandatory. Details on acquiring and installing NetLinx Studio and the necessary compiler versions.

2_Firmware.kit * Mandatory. The specific firmware kit required to bring the NI-Series Master up to a stable, modern communication standard.

3_Device_Software.txt * Mandatory. Guidance on defining and mapping the Device IDs (D:P:S) for the NI-2100/3100/4100 onboard ports.

Master_Files/ * Mandatory. The .axs source code that acts as the brain of your system.

Device_Files/ * Optional. Supplemental modules (.axi) for specific 3rd party equipment.

Docs/ * Reference manuals, DIP switch charts, and wiring pinouts.

🛠 Hardware Compatibility
NI-2100: 3 RS-232/422/485 ports, 4 IR, 4 I/O, 4 Relays.

NI-3100: 7 RS-232/422/485 ports, 8 IR, 8 I/O, 8 Relays.

NI-4100: Card-slot architecture with 7 onboard RS-232 ports + expansion capabilities.

📝 Change Log
[v0.1] - 2026-03-26 (The "Base" Release)
Structure: Implemented the numbered mandatory file system.

Initial Setup: Added 1_Software.txt and placeholders for 2_Firmware.kit.

Base Logic: Established the 3_Device_Software.txt framework for port mapping.

[Upcoming v1.0] - Planned
The "Initial Working Set": A fully compiled, error-free baseline program.

Auto-Config: Scripts to automate the initial Master connection via USB/Serial.

⚖️ License
Distributed under the MIT License.

Attribution Required: You are free to use and modify this, but you must retain the original copyright notice and give credit to this repository.
