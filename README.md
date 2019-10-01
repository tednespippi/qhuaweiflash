# qhuaweiflash
![image](https://user-images.githubusercontent.com/36906814/65954875-7c5a9e00-e479-11e9-8890-e6124fed56a5.png)

Graphical utility for flashing HUAWEI modems and routers and editing firmware files

This utility is intended for:

   - Firmwares of huawei modems, supporting the firmware protocol, similar to those used in modems on Balong V7. Including the full-fledged work implemented with the digital signatures of the firmware.
   - Editing the firmware images. You can view, add, delete, edit individual sections, edit section headers. Implemented editing of partition images in HEX code and, partially, in formatted mode (if the section has a meaningful format).
   - Start the usbloader of the modem loaders using patches.

The utility is built on the Qt graphics package and a Windows version of the balong_flash, balong-usbload utilities, as well as the firmware editor.

Dependencies:

    apt-get install qt5-qmake qtbase5-dev zlib1g-dev

To assemble this utility, use the commands:

    qmake 
    make qhuaweiflash 
    qmake 
    make 
