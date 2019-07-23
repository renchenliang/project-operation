1.download cmake and mingw tools
2.install them
3.add their '\bin' directories to environment variables
4.change mingw\bin **-make.exe to make.exe

tips:
mkdir build
cd build
if it is 'vs', you should cmake.exe -G"Unix Makefiles" ../" an the frist time,or it will be error.
