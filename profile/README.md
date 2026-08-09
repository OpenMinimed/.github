# OpenMinimed

A project to reverse-engineer Medtronic Minimed insulin pumps and CGM sensors.

Please check out or repositories for more information or join our Discord [server](https://discord.gg/tb4egy8VYh).

Repos:

- Documentation: documentation of the protocols, hardware, ...
- PythonPumpConnector: python PC code that can connect and talk with a pump
- FridaScripts: old script collection used to play wit the MiniMed Mobile android app
- InlineHook: fork of an armv7 hooking library (for NativeSakeTests)
- NativeSakeTests: C code compiled to an android phone that can load and call into the original SAKE library
- SakeLibraryRE: Ghidra project to completely reverse engineer the SAKE library
- JavaPumpConnector: experimental port of PythonPumpConnector; only does connection and handshake, nothing more
- PythonSake: drag & drop python library that handles all of the SAKE protocol
- JavaSake: Java port of PythonSake (used in JavaPumpConnector)
- JadxProjects: reverse engineering projects using the JADX decompiler
