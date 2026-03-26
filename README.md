AMX NetLinx NI-Series Legacy Support
Revitalizing NI-2100, NI-3100, and NI-4100 Systems

🚀 Introduction
In the modern AV landscape, high-quality documentation for "legacy" hardware often disappears into broken forum links and lost PDFs. This repository is a dedicated resource for the AMX NI-Series (NI-2100, NI-3100, NI-4100).

There is a massive lack of accessible, clear information for these workhorse masters. This project exists to provide a central "brain trust" for passionate automation folks to get these systems back online, fully functional, and integrated into modern environments.

💻 Software Requirements
To use the files in this repository, you will need:

NetLinx Studio (v4.x Recommended): The primary IDE for compiling and transferring code.

NSH (NetLinx Shell): For terminal-based diagnostics.

Firmware Transfer Tool: To utilize the included .kit files.

📂 File List (v0.1)
Master_Files/: Contains the main .axs source files for system logic.

Device_Files/: Includes specific device drivers and communication modules (.axi).

Firmware/: Includes the vital .kit files for NI-Series master firmware updates and card-slot expansion fixes.

Workspaces/: Pre-configured .apw files to get your environment set up instantly.

Docs/: Manuals and DIP switch charts for the 2100, 3100, and 4100.

🛠 Hardware Compatibility
NI-2100: 3 Configurable RS-232/422/485 ports, 4 IR, 4 I/O, 4 Relays.

NI-3100: 7 Configurable RS-232/422/485 ports, 8 IR, 8 I/O, 8 Relays.

NI-4100: The flagship card-slot architecture with 7 RS-232 ports + expansion slots.

📝 Change Log
[v0.1] - 2026-03-26 (The "Base" Release)
Initial Commit: Repository structure established.

Assets: Added baseline .kit firmware files for NI-series stability.

Workspace: Uploaded initial Master and Device file templates.

Software Guide: Added prerequisites for NetLinx Studio versioning.

[Upcoming v1.0] - Planned
The "Initial Working Set": A fully compiled, error-free baseline program.

IP Communication: Standardized modules for modern TCP/UDP control.

Troubleshooting: A "Common Faults" wiki for NI-series hardware.

⚖️ License
Distributed under the MIT License.

Important: This license requires that you keep the original copyright notice and give credit to the authors. If this code helps you finish a project or save a legacy system, please keep the attribution intact!

👋 Contributing
Help us fill the information gap! If you have stable modules, unique .kit files, or specific NI-4100 configuration tips, please submit a Pull Request.
