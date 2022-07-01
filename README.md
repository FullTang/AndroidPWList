# AndroidPWList
---
A small (>1GB) password list optimized for use against Android device passwords.

<i> I do not condone, encourage, or support those who would use this information for malicious or illegal means.</i>

---

## Version 3
The following optimizations and improvements were made on top of Verson 2:

* Changed the length of the passwords to be between 4 - 16 characters to support passcodes on all Android devices rather than just Samsung devices. 
* Used Crunch (https://www.kali.org/tools/crunch/) to generate alphanumeric passcodes that were between 4 and 5 characters in length.

Use the following Google Drive link to download the list. <br />
https://drive.google.com/file/d/1A0DpSPFsYTsdHis14cfJrLhLn-DnQsr7/view?usp=sharing

Name: Android_Passwords_v3.0.7z <br />
Size: 391139232 bytes (373 MiB) <br />
SHA1: 99A44FD153672375273956D3E19B7141B6BA0649 <br />
SHA256: F27E60D34F48F3DFCE40267A1F5970EF71BE5184B05684F3C499CB246D1F6392 <br />


---

## Version 2
The following optimizations and improvements were made on top of Verson 1:

* Added `real_english.dic` from Weakpass.
* Added several smaller wordlists that contain commonly used passwords
* Better sorting of passwords by popularity with more common passwords at the top
* Converted characters that escaped HTML back to their ASCII equivalents (Thanks to @tycho for pointing this out.)
* Better deduplication / line endings normalization (Thanks to @tycho and @hops for pointers with this.)

Name: Android_Passwords_v2.0.7z <br />
Size: 382442921 bytes (364 MiB) <br />
SHA1: 5515760218E0D5C257B5F6C213407F67C9460A4D <br />
SHA256: 34B6EA85C2C47AA261952A2381338795DA6E5FEE157EC0F70196E4C92DBDBE80 <br />

---

## Version 1
This list is just under 1GB in size and combines the following Weekpass (https://weakpass.com/wordlist/medium) wordlists:
`hk_hlm_founds.txt`
`ignis-10M.txt`
`kaonashi14M.txt`
`passwords.txt`
`real-pass_login.txt`
`rockyou.txt`
`SkullSecurityComp`
`Top29Million-probable-v2.txt`

The following optimizations were done to the list:

* Removed non-ASCII characters
* Combined / Deduplicated
* Length between 6 - 16 characters
* Alphanumeric/symbol passwords only (PIN codes / numerical only passwords removed)

Name: Android Passwords.7z <br />
Size: 394497443 bytes (376 MiB) <br />
SHA1: B34D44F1A388F07A8FC419B3BDD246CE25406753 <br />
SHA256: 1BE24FC839132099201CD64FF4E63FAB668E16D5D9197F0A9F8C722092227D1E <br />
