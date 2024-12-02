gcc -fPIC -shared -o bash_launcher_libretro.so libretro_bash_launcher.c -lm

move .so (shex-libretro.so) ~/.config/retroarch.core
