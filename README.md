# NTAG424-TEST-TOOL

NTAG424 TEST TOOL — managing NTAG424 DNA tags does not have to be complicated. **NFCTEC NTAG424 TOOL** provides a clean, intuitive interface for common tag operations on Windows and Android.

Simply tap your phone to an NTAG424 DNA tag, or connect a desktop reader, and the app identifies the card type and displays its UID. From there you can authenticate with EV2 keys, read and write file data, and adjust file access permissions with dropdown menus. A built-in APDU log shows every command and response in real time.

For NDEF and SDM (Secure Dynamic Messaging) configuration, the app offers URL template presets, key selection, and encrypted plaintext entry in one panel. A dedicated NDEF verify mode lets you check write results immediately.

Activation is handled through a license server: enter your email, receive a code, and activate with one click. Trial mode lets you explore reading, get settings, NDEF verification, and EV2 authentication before activation.

Download: `NFCTEC-NTAG424-Tool-Setup-v1.0.0.zip`

## Screenshots

### EV2 authentication

Authenticate with an application key (KEY 0–4), view session status (App / TI / Key), then change keys after KEY 0 is authenticated. APDU traces appear in the log at the bottom.

![EV2 Auth](1.png)

### Files, permissions, NDEF and SDM

Switch File 01 / 02 / 03, set communication mode and access rights (Read / Write / R/W / Change / FileRead), enable SDM, and write NDEF URL templates such as `https://www.nfctec.com/ntag?id={uid}&ctr={ctr}&cmac={cmac}`. Use **Write NDEF + SDM**, **Read NDEF & Verify**, and ASCII/Hex data blocks for file contents.

![Files NDEF SDM](2.png)

## About [nfctec.com](https://nfctec.com)

[NFCTEC](https://nfctec.com) is a full-stack NFC and smart card company. We co-develop software, design hardware, and connect cloud backends — from first prototype to certified mass production.

**What we cover**

- **Software** — mobile wallet SDKs, issuance and reading software for ePassports, bank cards (EMV), NTAG 424 DNA, DESFire, MIFARE, FeliCa, JavaCard and more
- **Hardware** — USB / Serial / USB CCID readers, embedded modules, NFC field detector cards, antennas and blank cards
- **Cloud** — issuance and verification APIs, HSM-backed keys and SaaS consoles
- **Industry solutions** — payment, transit, identity, access control and IoT

**Focus areas include** banking & payment, transit & ticketing, government & ID, access control, healthcare, IoT, brand protection, retail & loyalty, automotive, mobile wallet, and security / crypto wallets.

This NTAG424 DNA Tool is part of that stack: a practical desktop (and Android) app for authenticating NTAG 424 DNA, managing file permissions, and configuring SDM / NDEF URLs used with NFCTEC cloud verification.

Learn more, request samples, or talk to the engineering team: **[https://nfctec.com](https://nfctec.com)**
