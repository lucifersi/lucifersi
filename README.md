🖐️ HEY I AM LUCIFER 👽
🕳️ HOW ARE YOU 🕳️
--------------------------
🖥️ THISE PAGE  USE FOR EDUCATION PURPOSE ONLY 🖥️
    ---> ANDROID 📱 HACKING CODES AVAILABLE IN THISE PAGE 📃 <---
    ---> WINDOWS 🖥️ CRESHING CODES AVAILABLE IN THISE PAGE 📃 <---
    
 😶‍🌫️ HEY TERMUX USERS & KALI LINUX USER'S 👾 

          THISE CODES FOR YOU 
          ---------------------
  
   CiLocks - Android LockScreen Bypass
----------------------------------------
Features
Brute Pin 4 Digit
Brute Pin 6 Digit
Brute LockScreen Using Wordlist
Bypass LockScreen {Antiguard} Not Support All OS Version
Root Android {Supersu} Not Support All OS Version
Steal File
Reset Data
-----------------------------------------------------------------------------------------------------------------------------------—
Required

- Adb {Android SDK}
- Cable Usb
- Android Emulator {NetHunter/Termux} Root
- Or Computer
_____________________________________________________
Compatible

- Linux
- Windows
- Mac
_____________________________________________________
Tested On

- Kali Linux
_____________________________________________________
How To Run

- git clone https://github.com/tegal1337/CiLocks
- cd CiLocks
- chmod +x cilocks
- bash cilocks
_____________________________________________________
For Android Emulator

- Install Busybox
- Root

If brute doesn't work then uncomment this code

`# adb shell input keyevent 26`
if 5x the wrong password will automatically delay 30 seconds
---------------------------------------------------------------------------------------------------------------------------—
🖥️ Cpufetch - Simplistic Yet Fancy CPU Architecture Fetching Tool 🖥️

Support
cpufetch currently supports x86_64 CPUs (both Intel and AMD) and ARM.

Platform	x86_64	ARM	Notes
Linux	
✔️
✔️
Prefered platform.
Experimental ARM support
Windows	
✔️
❌
Some information may be missing.
Colors will be used if supported
Android	
❗
✔️
Experimental ARM support
macOS	
✔️
❌
Some information may be missing
Emoji	Meaning
✔️
Supported
❌
Not supported
❗
Not tested

2. Installation

2.1 Building from source
Just clone the repo and use make to compile it

git clone https://github.com/Dr-Noob/cpufetch
cd cpufetch
make
./cpufetch
The Makefile is designed to work on Linux, Windows and macOS.


2.2 Linux
There is a cpufetch package available in Arch Linux (cpufetch-git). If you are in another distribution, you can build cpufetch from source.


2.2 Windows
In the releases section you will find some cpufetch executables compiled for Windows. Just download and run it from Windows CMD. You can also build cpufetch from source.


2.3 macOS
You need to build cpufetch from source.


2.4 Android
Install termux app (terminal emulator)
Run pkg install -y git make clang inside termux.
Build from source normally:
git clone https://github.com/Dr-Noob/cpufetch
cd cpufetch
make
./cpufetch
. Examples
Here are more examples of how cpufetch looks on different CPUs.


3.1 x86_64 CPUs






3.2 ARM CPUs
 






4. Colors and style
By default, cpufetch will print the CPU art with the system colorscheme. However, you can always set a custom color scheme, either specifying Intel or AMD, or specifying the colors in RGB format:

./cpufetch --color intel (default color for Intel)
./cpufetch --color amd (default color for AND)
./cpufetch --color 239,90,45:210,200,200:100,200,45:0,200,200 (example)
In the case of setting the colors using RGB, 4 colors must be given in with the format: [R,G,B:R,G,B:R,G,B:R,G,B]. These colors correspond to CPU art color (2 colors) and for the text colors (following 2). Thus, you can customize all the colors.


5. Implementation
See cpufetch programming documentation.


6. Bugs or improvements
There are many open issues in github (see issues). Feel free to open a new one report an issue or propose any improvement in cpufetch

I would like to thank Gonzalocl and OdnetninI for their help, running cpufetch in many different CPUs they have access to, which makes it easier to debug and check the correctness of cpufetch.


