# Fresh Random Civ Picker
Launch Fresh Random Civ Picker.exe to start  
Enter 1 to receive a fresh random civ  
Enter 0 to reset  
Enter -1 to quit  

## Compiling
The program is a single C file with no dependencies beyond the standard library. On Windows it is built with GCC from [MinGW-w64](https://www.mingw-w64.org/).

1. Install MinGW-w64 and make sure its `bin` folder (e.g. `C:\mingw64\bin`) is on your `PATH`. Check with:
   ```
   gcc --version
   ```
2. From the repository root, run:
   ```
   gcc "Fresh Random Civ Picker/main.c" -o "Fresh Random Civ Picker.exe"
   ```
3. Start the program:
   ```
   & ".\Fresh Random Civ Picker.exe"
   ```
   (in cmd: `"Fresh Random Civ Picker.exe"`)
