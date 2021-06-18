Python setup from source with Tcl/Tk support

sudo apt update \
sudo apt install tk8.6 tk8.6-dev


./configure --enable-optimizations \
--with-tcltk-includes='-I/usr/include/tcl8.6' \
--with-tcltk-libs='/usr/lib/aarch64-linux-gnu/libtcl8.6.so /usr/lib/aarch64-linux-gnu/libtk8.6.so'
