# MSys2 package installations
## From the MinGW Prompt run these commands
```
pacman -S --needed "${MINGW_PACKAGE_PREFIX}-cc"
pacman -S --needed "${MINGW_PACKAGE_PREFIX}-make"
```
# Code::Blocks settings
## Menu: Settings -> Compiler
## Select Global Compiler Settings in left pane
## Select correct GCC compiler to change
### Toolchain Executable
#### Compiler installation Directory
##### Below example for MINGW64 GCC compiler
```
C:\msys64\mingw64
```
#### Make program [SETTING NOT TESTED]
```
mingw32-make.exe SHELL=CMD.exe
```
#### Additional Paths
```
$(TARGET_COMPILER_DIR)../usr/bin
```
