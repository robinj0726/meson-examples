meson setup builddir --backend=vs
mkdir subprojects
meson wrap install sdl2
open .sln in visual studio
