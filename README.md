# Port of ADuCM350 SDK for GCC ARM

This is a port of the ADuCM350 SDK (see http://www.analog.com/en/products/aducm350.html) to be used with the GCC tool chain.
The example project is set up to be used with GNU MCU Ecplise on Linux (Ubuntu in our case).

This is a fork of https://github.com/dioptre/ADuCM350 with adoptions to our working evironment. Please report any issues and submit pull requests to the original repository.
Please read README.orig.md for their notes and licensing info.

## Installation

Use the following steps to get a running development environment (tested on a fresh Ubuntu Desktop 18.04)

#### Install npm & xpm

* Details: https://www.npmjs.com/package/xpm
* sudo apt install npm
* sudo npm install --global xpm

#### Install gcc arm toolchain

* Details: https://gnu-mcu-eclipse.github.io/install/
* xpm install @gnu-mcu-eclipse/arm-none-eabi-gcc --global

#### Install JLink support

* Details: https://gnu-mcu-eclipse.github.io/debug/jlink/install/
* Download 64bit deb file from segger.com using Firefox
* sudo dpkg -i ~/Downloads/JLink_Linux_x86_64.deb

#### Install Java

* sudo apt-get install openjdk-11-jre

#### Install GNU MCU Eclipse

* Download Linux 64bit tgz from https://github.com/gnu-mcu-eclipse/org.eclipse.epp.packages/releases
* cd ~
* tar xvf Downloads/20180419-1818-gnumcueclipse-4.3.3-oxygen-3a-linux.gtk.x86_64.tar.gz

#### Install git

* sudo apt install git

#### Checkout repository

* cd ~
* mkdir repros
* git clone https://github.com/fablab-muenchen/ADuCM350.git


