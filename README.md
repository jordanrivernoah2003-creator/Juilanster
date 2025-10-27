# Juilanster
 An experimental emulator for the Juilanster That Is Fork From VFrown

 ![VFrown Logo](images/icon.png)

**NOTE: this emulator is still a work in progress.**

## Building and Running
Create a folder in the same location as Juilanster named `bios` and insert a copy of your BIOS called `sysrom.bin`. While this step isn't required by Juilanster, not all games can run properly (or at all) without a Bios Rom image.


Run the following commands:
```
cd <path/to/project>
Make platform=<platform> build=<build>
./Juilanster <path/to/game>
```
Replace `<platform>` with `windows`, `macos` or `linux` depending on your platform,
and replace `<build>` with `debug` or `release`. Without these, it will default to building a linux debug build.


## Controls
```
Arrow keys: directional movement
Space: Enter/OK
A: Help
S: Exit
D: Learning Zone
Z: Red
X: Yellow
C: Blue
V: Green
```

## Examples
![VTech Logo](images/Logo1.png)
![VSmile Logo](images/Logo2.png)
![Alphabet Park Adventure](images/AlphabetPark1.png)
![Scooby-Doo! Funland Frenzy](images/ScoobyDoo1.png)

## TODO / Roadmap
Currently...
- Improve Sound (Top priority)
- Improve accuracy and get more games booting (Top priority)

Later on...
- Add support for more controllers
- Add Remappable buttons
- Add a TAS interface
- Memory viewer, editor, and cheat manager
- ...and more...
