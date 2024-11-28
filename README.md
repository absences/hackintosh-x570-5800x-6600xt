# hackintosh-x570-5800x-6600xt
macOS Sonoma 15.1.1

OpenCore ver :0.9.8

Current hardware:

    procesador:AMD Ryzen 5800x

    mb: X570 AORUS PRO WIFI

    graphics card:NITRO+ AMD Radeon™ RX 6600 XT

    WiFI / Bt: intel ax200

how to Generate EFI?

    https://github.com/lzhoang2801/OpCore-Simplify

    On Windows, run OpCore-Simplify.bat

    Input 1 => E to Generate Report json file

    optional:Input 5,Custonmize SMBIOS Model

    Input 6 => Build OpenCore EFI

    USB Maping:
    
    https://github.com/USBToolBox/tool

    https://github.com/USBToolBox/tool/releases/download/0.2/Windows.exe

    Next:

    Input D Discover your Usb ports
    
        Use a Usb 3.0 Devices EVERY-PORT inserted once

        optional: usb2.0  that's also the case

        if type-c port , both sides need to be inserted once

        Input B : Back

    Input S => K to build usbmap.kext

    Next:

    https://github.com/corpnewt/ProperTree/archive/refs/heads/master.zip

    copy usbmap.kext to efi/oc/kexts folder

    run ProperTree.bat

    open config.plist

    pressing Ctrl+R ,select OC Folder

    Save the file


