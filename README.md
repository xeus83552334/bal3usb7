#bal3usb7

Experimental USB-assisted iOS boot-chain research

bal3usb7 — експериментальний проєкт, заснований на дослідженні B34ST / USBLiter8. Його мета — перевірити можливість використання USB-пристрою для запуску низькорівневого коду та подальшого дослідження завантажувального ланцюга iOS.

Target device

* Device: iPhone 13 Pro Max
* SoC: Apple A15 Bionic (T8110)
* iOS: 26.5.2
* Project name: bal3usb7
* Base: B34ST / USBLiter8
* Execution method: USB-assisted, exact implementation to be documented
* Test status: Device testing reported by the author; individual stages require documented verification.

Compatibility status

A15 / iOS 26.5.2 is the intended target configuration. Compatibility with the complete exploit and jailbreak chain must be established independently for this exact device and OS build.

Successful USB communication, DFU detection, or entry into a modified DFU state does not by itself establish a working jailbreak.

Verification goals

1. Confirm the exact device model and SoC.
2. Record the iOS version and build number.
3. Verify USB device detection and capture diagnostic output.
4. Determine whether the USB exploit stage completes.
5. Verify whether the boot chain proceeds beyond DFU.
6. Establish whether kernel-level privileges and the intended post-exploitation functionality are actually available.

Limitations

No unverified claims of permanent jailbreak, kernel read/write, tweak injection, package-manager support, or persistence are made.

Project status

Experimental. Compatibility claims will be updated as reproducible test evidence becomes available.
