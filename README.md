# Dead Drive

A 2D digital-forensics (DFIR) puzzle game. You work a night shift in a forensic lab: acquire evidence correctly, carve files, catch timestomping, autopsy the registry, analyze memory, and reconstruct a defensible incident report. Six escalating cases: chain of custody, file carving/magic bytes, timeline & timestomp ($SI vs $FN + Prefetch), registry forensics (Run keys, USBSTOR, AmCache), memory forensics (Volatility-style pslist/netscan/malfind), and reconstruct & report.

Single self-contained `index.html`. No build, no dependencies. Open it in a browser or serve the folder.

Walk a 2D top-down hub and work six escalating cases; ~60–90 minutes. Progress, score (hints cost points), and a session timer persist in `localStorage`. Keyboard (`WASD`/arrows, `E`/`Enter`) and on-screen touch controls both supported. MITRE ATT&CK / technique references cited per case.

Pure defensive security content — identify, analyze, contain, report.
