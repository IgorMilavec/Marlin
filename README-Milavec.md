# Setting up the build environment

1. Install VSCode
2. Clone the repository
```
git clone https://github.com/IgorMilavec/Marlin.git
cd Marlin
git remote add upstream https://github.com/MarlinFirmware/Marlin.git
git fetch upstream
git switch -c lts-2.1.2 upstream/lts-2.1.2
git checkout lts-2.1.2-Milavec-Tevo-Tarantula
```
3. Allow VSCode to install automatically detected extensions
   - PlatformIO
   - Auto Build Marlin
