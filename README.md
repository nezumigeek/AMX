AMX NetLinx NI-Series Legacy Support
Revitalizing NI-2100, NI-3100, and NI-4100 Systems

🚀 Introduction
In the modern AV landscape, high-quality documentation for "legacy" hardware often disappears into broken forum links and lost PDFs. This repository is a dedicated resource for the AMX NI-Series (NI-2100, NI-3100, NI-4100).

Whether you are a hobbyist keeping a home system alive or a pro-integrator maintaining a commercial stack, this project provides the essential boilerplate code, firmware configuration steps, and troubleshooting guides needed to get these masters operational in a modern network environment.

📂 File List (v0.1)
/Boilerplate: Standard .axs templates for NI-series masters.

/Includes: Essential .axi files for common serial/IP communication.

/Docs: Markdown guides for Serial-to-Ethernet setup and DIP switch configurations.

LICENSE: The MIT license file ensuring author attribution.

NI_Series_Base_Program.axs: The core workspace file.

🛠 Setup & Compatibility
This code is designed for the NI-Series architecture.

Note: Ensure your NetLinx Studio version is updated to at least v4.x to handle modern compiler nuances, even when targeting older hardware.

NI-2100: 3 Configurable RS-232/422/485 ports, 4 IR, 4 I/O, 4 Relays.

NI-3100: 7 Configurable RS-232/422/485 ports, 8 IR, 8 I/O, 8 Relays.

NI-4100: Expanded card-slot architecture with 7 RS-232 ports + expansion.

📝 Change Log
[v0.1] - 2026-03-26 (The "Base" Release)
Initial Commit: Repository structure created.

Documentation: Added hardware pinout guide for NI-series DB9 ports.

Base Code: Uploaded a "Heartbeat" logic template to verify master-to-touchpanel communication.

[Upcoming v1.0] - Planned
Full implementation of a "Working Code Set."

Standardized IP communication module for modern TCP/UDP integration.

Auto-reconnect logic for peripheral devices.

⚖️ License
Distributed under the MIT License. This means you are free to use, modify, and distribute this code as long as the original copyright and license notice are included. Credit to the original contributors is required.

👋 Contributing
If you have a .axi file that has saved your life in the field, or a specific trick for getting an NI-4100 to behave on a modern VLAN, please submit a Pull Request!
