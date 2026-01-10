📶 Wireless Encryption Documentation: Protect Your Wi-Fi! 🔒
This guide covers securing wireless networks, focusing on encryption standards like WPA, WPA2, and WPA3, along with authentication methods and security considerations. Wireless networks transmit data via radio signals, making encryption essential to protect confidentiality and integrity.

Securing a Wireless Network
Wireless networks often handle sensitive information, requiring robust security measures.

----Access control: Authenticate users before granting access using methods like username/password or multi-factor authentication (MFA).
---Confidentiality: Encrypt all wireless communications to prevent eavesdropping.
---Integrity verification: Use message integrity checks (MIC) to ensure received data matches the original sent data.

WPA (Wi-Fi Protected Access)
WPA addressed critical flaws in the older WEP standard.
----Introduction: Released in 2002 as a replacement for WEP (Wired Equivalent Privacy), which had serious cryptographic weaknesses. Avoid using WEP entirely.
----Purpose: Served as a short-term solution to run on existing hardware while bridging to future standards.

Wireless Encryption
Wireless devices act as radio transmitters and receivers, making them vulnerable to interception.
-----Encryption solution: Encrypt data using shared keys so only authorized users can transmit and receive.
------Standards: WPA2 and WPA3 provide strong encryption for secure wireless communication.

WPA2 and CCMP
WPA2 is a widely adopted standard with advanced encryption.
--------Wi-Fi Protected Access II (WPA2): Certification began in 2004.
--------CCMP (Counter Mode with Cipher Block Chaining Message Authentication Code Protocol): A block cipher mode that enhances security.
--Security services--->>>>
*Data confidentiality via AES encryption.
*Message Integrity Check (MIC) using CBC-MAC.

WPA3 and GCMP
WPA3 offers improved security over WPA2.
--Wi-Fi Protected Access 3 (WPA3): Introduced in 2018.
--GCMP (Galois/Counter Mode Protocol): A stronger encryption mode compared to WPA2.
--Security services--->>>
*Data confidentiality with AES.
*Message Integrity Check (MIC) using Galois Message Authentication Code (GMAC).

The WPA2 PSK Problem---WPA2 has vulnerabilities related to pre-shared keys (PSK).
---Brute-force attacks: Attackers can capture the four-way handshake or derive the PSK hash to brute-force the key.
----Ease of exploitation: Weak PSKs are easier to crack, especially with improved technology like GPU processing and cloud-based cracking.
----Impact: Obtaining the PSK gives access to the entire wireless network key.

SAE (Simultaneous Authentication of Equals)
WPA3 introduces a more secure authentication process.
---Improvements: Eliminates the four-way handshake, hashes, and brute-force vulnerabilities by using mutual authentication and creating shared session keys without transmitting them over the network.
---Technical details: A Diffie-Hellman derived key exchange with authentication; each session uses a unique key even with the same PSK.
---Standard: Known as the IEEE dragonfly handshake.

Wireless Security Modes
Configure authentication on wireless access points or routers.
----Open System: No password required; offers no security.
---WPA/2/3-Personal / WPA/2/3-PSK: Uses WPA2 or WPA3 with a pre-shared key (256-bit); all users share the same key.
---WPA/2/3-Enterprise / WPA/2/3-802.1X: Authenticates users individually via an authentication server (e.g., RADIUS), providing per-user access control.
