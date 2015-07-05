Built in Elementary OS Freya

### Simple Build Instructions
* `valac --pkg gtk+-3.0 hello-world.vala`
* `./hello-world`

## To Build
* inside of the hello-world directory
* `mkdir build && cd build/`
* `cmake -DCMAKE_INSTALL_PREFIX=/usr ../`
* `make`
* `sudo make install`

_WARNING: DO NOT PUSH BUILD DIRECTORY. THAT'S LOCAL TO YOUR MACHINE_