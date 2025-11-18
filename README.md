# 🛸 Alien Message Decoding & Encryption System
A Python project to decode mysterious alien messages using string length mapping, dictionaries, and alphabetical sorting.

### 📌 Project Overview
This project simulates communication between scientists on Earth and an alien civilization.
Aliens send encrypted messages based on the length of strings, which correspond to alphabet positions.
Scientists decode the messages using a custom dictionary and also send encrypted replies back using the same logic.
The project also handles gibberish message reconstruction, where letters are scrambled due to cosmic interference.

### 🚀 Features
✔️ 1. Create Custom Alien Dictionary
Key: number (0–26)
Value: alphabets (a–z) and space " "

✔️ 2. Decode Alien Message Using String Lengths
Each alien word is represented by a random string.
The length of each string maps to the dictionary to reveal the actual message.

✔️ 3. Reverse Lookup in Dictionary
Find dictionary keys by searching through values.

✔️ 4. Encode a Human Message for Aliens
Scientists encode "why" using dictionary indexing.

✔️ 5. Generate Encrypted Alien-Readable Messages
Using only "a" repeated N times depending on the dictionary index.

✔️ 6. Decode Gibberish Word (Problem 7)
A cosmic anomaly scrambles letters.
Scientists receive multiple jumbled variations and must:

Sort letters of each jumbled string alphabetically
Combine reconstructed data to infer the original structure

✔️ 7. Full Python Implementation

All steps implemented in the script dictionary_ailen_project.py.
