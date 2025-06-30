https://gbdev.io/pandocs/

Required for Windows:

Install MSYS2: https://www.msys2.org/

Open and run: 
1) pacman -S mingw-w64-ucrt-x86_64-gcc
2) pacman -S cmake
3) pacman -S mingw64/mingw-w64-x86_64-SDL2 mingw64/mingw-w64-x86_64-SDL2_mixer mingw64/mingw-w64-x86_64-SDL2_image mingw64/mingw-w64-x86_64-SDL2_ttf mingw64/mingw-w64-x86_64-SDL2_net 
4) pacman -S mingw-w64-x86_64-check 

Then cd into build folder and run something along the lines of: "gbemu/gbemu ../../game_roms/[file name]"
- You must add your own rom files. The only included rom file is Legend of Zelda - Link's Awakening, which can be run by "gbemu/gbemu ../../game_roms/LoZ_LinkAwakening.gb"