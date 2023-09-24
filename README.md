**OpenCore EFI made for Asus X505Za**

This EFI is especially made for ASUS X505ZA, working with macOS Ventura+.

**Working :**

- _Graphics_ (brightness, GPU Acceleration),
- _Trackpad_ (APPLE Gestures,etc),
- _WiFI, Ethernet_,
- _Audio_ (Playing Music, Microphone stuff works as well),
- _Keyboard_ (FN Keys for Audio),
- _Bluetooth_ (pairing, playing | Bluetooth Microphone is not working yet, so make sure to use the inbuilt microphone from Settings),
- _USB Ports_ (remaped to use the full speed and the type C connector works as well),
- Apple ID, iCloud, AppStore.

**Not Working :**

- _Sleep_ (Still a WIP)
- _Some Electron apps may not work due to AMD._

**Steps to install :**

  Format an 4GB+ USB drive to FAT-32, create a new folder named EFI and copy the BOOT and OC Folders into it.
  Download the recovery image and place it in the root of your USB, using dortania's guide.
  Make sure to include the HeliPort package as well for wifi to work after installation. 
  I'd suggest you to download the entire OS in the recovery using ethernet.
  After Installation, don'e foret to mount your EFI and copy and paste the provided EFI folder from the USB.
  If OpenCore DMG doesnt appear while booting into USB, press Control + ALT + SPACE and it should show up.
  Enjoy.
  
