# gb-hello-world
 A hello world for the game boy made with gbdk

# Build instructions 
* Clone this repository
* Create a make.bat file in project root folder
* Paste this code replacing the elements in brackets suiting your own
```
REM Automatically generated from Makefile
[Path to gbdk lcc] -Wa-l -Wl-m -Wl-j -o [rom name].gb [main c file].c
```