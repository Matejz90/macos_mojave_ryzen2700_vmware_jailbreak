1.) Download VMware 15.1.0 build-13591040
2.) Download .iso image (macOS Mojave ISO by Geekrar.rar): https://drive.google.com/drive/folders/1qesyv6UIIVoUMrkjqplpP6dPm6MnDaMn?usp=sharing
3.) Download unlock-master for add MacOS filds in VMware: https://codeload.github.com/paolo-projects/unlocker/zip/master
4.) Create new virtual machine with MacOS fields (Mojave 10.14)
4.) Go to: C:\Users\MatejZ90\Documents\Virtual Machines\macOS 10.14
6.) Edit MacOS 10.14.vmx file like:
    *****************************************
      virtualHW.version = "10"
    *****************************************
 7.) For Ryzen 2700 add theese lines in file:
    *****************************************
      smc.version = "0"
      cpuid.0.eax = “0000:0000:0000:0000:0000:0000:0000:1011”
      cpuid.0.ebx = “0111:0101:0110:1110:0110:0101:0100:0111”
      cpuid.0.ecx = “0110:1100:0110:0101:0111:0100:0110:1110”
      cpuid.0.edx = “0100:1001:0110:0101:0110:1110:0110:1001”
      cpuid.1.eax = “0000:0000:0000:0001:0000:0110:0111:0001”
      cpuid.1.ebx = “0000:0010:0000:0001:0000:1000:0000:0000”
      cpuid.1.ecx = “1000:0010:1001:1000:0010:0010:0000:0011”
      cpuid.1.edx = “0000:1111:1010:1011:1111:1011:1111:1111”
      featureCompat.enable = "FALSE"
     *****************************************
8.) Add USB controller v. 3.0 in VMware->Edit machine
8.) Start installing Mojave and select Disk Utility in install and reformat disk (42.xxGB). Click red button after complete and start installing OS
