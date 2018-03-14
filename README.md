# sdl-testing
- C++ example programs for various SDL functions
- These example programs were written by Lazy Foo' Productions as a part of his SDL tutorial series.
- See http://lazyfoo.net/tutorials/SDL/index.php for more info.

### Makefile
When compiling, just edit the Makefile to reflect which .cpp you are compiling along with the desired output .exe location

SDL Libraries used (i686-w64-mingw32 architecture):
- SDL2-2.0.8
- SDL2_image-2.0.3
- SDL2_mixer-2.0.2
- SDL2_ttf-2.0.14

This means we use the following linker flags to specify the libraries we need:
`-lmingw32 -lSDL2main -lSDL2 -lSDL2_image -lSDL2_ttf -lSDL2_mixer`

The Makefile assumes these file path locations (modify to reflect your setup): 
- Include path to the SDL include folder (header files) is C:\mingw_dev_lib\include\SDL2 
- Library path to the SDL lib folder is C:\mingw_dev_lib\lib

