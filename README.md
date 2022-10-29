# XBOX2PC

This is a project that allows you to RUN Xbox One OS (CodeName:Durango) on a computer!

## Usage instructions
1. Download the install.wim file
2. Copy the file install.wim at (Windows 10 installation Usb drive)\Sources and replace all files
3. Boot at the pendrive
4. Wait Xbox OS Load
5. Connect an usb controller
6. Complete the setup

## Theory that it will work
"A LinkedIn page from a Microsoft intern contains a reference to something called "Windows OneCore" which could be a rebranding of the company's plans to develop one kernel that will be used for all of Microsoft's operating systems, including Windows, Windows Phone and Xbox."

So if it uses the same kernel for all devices, in _*theory*_ this will work
[I got this info Here!](https://www.windowscentral.com/windows-onecore-shows-some-microsoft-linkedin-pages#:~:text=A%20LinkedIn%20page%20from%20a%20Microsoft%20intern%20contains,operating%20systems%2C%20including%20Windows%2C%20Windows%20Phone%20and%20Xbox.)

## Problems that might be serious
1. Drivers: These drivers are designed for AMD "Jargon", when this is done i will thest W10 drivers.
2. Boot the system: Xbox One might use a UEFI Bootloader, Legacy users might have problems booting the system

## Requeriments
1. 8GB Ram (Minimum)
2. AMD Motherboard (Recommended)

## State
- [X] Write the needed information
- [X] Get the right parameters to extract
- [ ] Get the key for the file
- [ ] Extract the files
- [ ] Capture into a WIM file

## Warnings
I DON'T recommend to install this on a REAL COMPUTER, use a vm instead.

Im not responsable by ANY damage you get on your computer.

## Credits
* [XvdTool](https://github.com/emoose/xvdtool), if was not it, i would spend money on a Xbox
* [DurangoKeyExtractor](https://github.com/emoose/xvdtool/tree/master/DurangoKeyExtractor), By the same guy, this extracted the key from the system.xvd
* [Microsoft](Microsoft.com), made the OS
