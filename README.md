# UNOFICIAL wiringPi
Modification of the original wiringPi library to work with 64bit operation systems.
Only tested on RPi3b, but in theory will work with any RPi that support the original wiringPi. 

**PLEASE** don't send bugs to the original author!

To not use root user to acces to gpio, I recommend to use the kernel of [sakaki](https://github.com/sakaki-/bcmrpi3-kernel)

## Installation
There are two possibilities, to install using the source code or using the precompiled binary:

Source code:
```bash
git clone https://github.com/TheNextLVL/wiringPi.git
cd wiringPi
./build
```

Precompiled binary:
```bash
wget https://github.com/TheNextLVL/wiringPi/releases/download/2.46/wiringpi-2.46.deb
apt install ./wiringpi-2.46.deb
```

Check if working:
```bash
gpio -v
```

Original Description
--------------------

wiringPi README
===============

Please note that the official way to get wiringPi is via git from
git.drogon.net and not GitHub.

ie.

  git clone git://git.drogon.net/wiringPi

The version of wiringPi held on GitHub by "Gadgetoid" is used to build the
wiringPython, Ruby, Perl, etc. wrappers for these other languages. This
version may lag the official Drogon release.  Pull requests may not be
accepted to Github....

Please see

  http://wiringpi.com/

for the official documentation, etc. and the best way to submit bug reports, etc.
is by sending an email to projects@drogon.net

Thanks!

  -Gordon
