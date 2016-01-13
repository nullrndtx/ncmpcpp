ncmpcpp 0.7_pre
---------------

### Dependencies
* libboost-all-dev
* fftw2 
* fftw-dev
* libfftw3-dev
* libfftw3-3
* libreadline-dev
* curl
* libcurl4-gnutls-dev
* libcurl3-nss
* libncursesw5-dev 
* libtaglib-cil-dev
* libncurses5-dev
* g++
* make
* automake
* autoconf
* mpd
* mpc
* libasund2-dev
* libasound2-plugin-equal
* libmpd1
* libmpd-dev
* libmpdclient2
* libmpdclient-dev

### How To Compile
Generate configure scripts

> ./autogen.sh

Building

> ./configure --enable-outputs --enable-visualizer> --enable-clock --enable-unicode --with-curl --with-fftw

Then install

> make && sudo make install
