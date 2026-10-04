# Many-Time Pad (OTP Reuse) Attack

This repository contains a Python implementation designed to exploit the One-Time Pad (OTP) key reuse vulnerability (Many-Time Pad attack). 

## Key Features
- Byte-Aligned 1:1 XOR: Eliminates padding and bit-shift errors during hex-to-byte manipulation.
- Space Dragging Heuristic: Identifies likely key bytes by leveraging the mathematical property of XOR operations with ASCII spaces (`0x20`).
- Statistical Fallback Scoring: Resolves missing keystream bytes using English character frequency and printable ASCII ranges.
