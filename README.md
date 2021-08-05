Python setup from source with Tcl/Tk support

sudo apt update \
sudo apt install tk8.6 tk8.6-dev \
sudo apt install lzma lzma-dev liblzma-dev \
sudo apt install libncurses-dev libgdbm-dev libz-dev tk-dev libsqlite3-dev libreadline-dev liblzma-dev libffi-dev libssl-dev


./configure --enable-optimizations \
--with-tcltk-includes='-I/usr/include/tcl8.6' \
--with-tcltk-libs='/usr/lib/aarch64-linux-gnu/libtcl8.6.so /usr/lib/aarch64-linux-gnu/libtk8.6.so'
