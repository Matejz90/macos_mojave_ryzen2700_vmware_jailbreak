### My PC Configuration
- AMD Ryzen 2700
- 32GB RAM G.Skill B-Die
- 500 GB Samsung 970 EVO PLUS NVMe
- 1TB HDD
- Geforce 1080 TI 11GB
- Windows 10 PRO

### Tested phones
- Iphone X
- Iphone XR

### Installation
1.) Download VMware 15.1.0 build-13591040

2.) Download .iso image (macOS Mojave ISO by Geekrar.rar) [Link](https://drive.google.com/drive/folders/1qesyv6UIIVoUMrkjqplpP6dPm6MnDaMn?usp=sharing)

3.) Download unlock-master for add MacOS filds in VMware [Link](https://codeload.github.com/paolo-projects/unlocker/zip/master)

4.) Create new virtual machine with MacOS fields (Mojave 10.14)

4.) Go to: C:\Users\ ~~MatejZ90~~\Documents\Virtual Machines\macOS 10.14

6.) In MacOS 10.14.vmx file change <abbr title="">virtualHW.version</abbr> to:`virtualHW.version = "10"`

 7.) For <abbr title="">Ryzen 2700</abbr> add theese lines in file:
<pre> smc.version = "0"
      cpuid.0.eax = “0000:0000:0000:0000:0000:0000:0000:1011”
      cpuid.0.ebx = “0111:0101:0110:1110:0110:0101:0100:0111”
      cpuid.0.ecx = “0110:1100:0110:0101:0111:0100:0110:1110”
      cpuid.0.edx = “0100:1001:0110:0101:0110:1110:0110:1001”
      cpuid.1.eax = “0000:0000:0000:0001:0000:0110:0111:0001
      cpuid.1.ebx = “0000:0010:0000:0001:0000:1000:0000:0000”
      cpuid.1.ecx = “1000:0010:1001:1000:0010:0010:0000:0011”
      cpuid.1.edx = “0000:1111:1010:1011:1111:1011:1111:1111”
      featureCompat.enable = "FALSE"</pre>
	  
8.) Add <abbr title="">USB controller version 2.0</abbr> in VMware->Edit machine

9.) Start installing Mojave and select <abbr title="">Disk Utility</abbr> when are you prompted and reformat disk (42.xxGB). 

10.)Click red button after complete and start installing OS
11.) When OS is installed go to [Link](https://github.com/pixelomer/AltDeploy/releases/download/v1.1/AltDeploy.zip) and download file (AltDeploy v1.1)

12.) Open file and program will be terminated because of security options

13.) You need to edit <abbr title="">Security & Privacy</abbr> options in <abbr title="">System preferences</abbr> (in dock is icon)

14.) Open now <abbr title="">AltDeploy</abbr>

15.) You get warning because of mail program

16.) Go to <abbr title="">Mail</abbr> program, add you email account and click in top <abbr title="">Mail -> Preferences</abbr>

17.) Click Manage plugins at bottom of window and check field before AltDeploy plugin

18.) Go back to <abbr title="">AltDeploy v1.1</abbr> program and install your unc0ver stuff and don't forget to click <abbr title="">Trust</abbr> on iPhone


------------
<p align="center">
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/1.jpg?token=ALKOKBIQPH5QR3PNGDNEP5S6EMGIU" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/2.jpg?token=ALKOKBLFMDCLONAWNSY2OCC6EMGSQ" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/3.jpg?token=ALKOKBO2ARZBLR3LIKK4JN26EMGSW" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/4.jpg?token=ALKOKBLASLRVRYB5IRTGDK26EMGS6" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/5.jpg?token=ALKOKBOBGC6GSUB6QCMC3EK6EMGTG" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/5.jpg?token=ALKOKBOBGC6GSUB6QCMC3EK6EMGTG" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/6.jpg?token=ALKOKBKI34K2GX6ZONO2ZSK6EMGTK" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/7.jpg?token=ALKOKBMRM76H2K2DXQDV2QS6EMGTQ" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/8.jpg?token=ALKOKBKB6AMHYS6J2FK4PO26EMGUC" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/9.jpg?token=ALKOKBKG7BZ2PEHMQPW4VS26EMHGS" alt="1" width="400px"/>
<img src="https://raw.githubusercontent.com/Matejz90/macos_mojave_ryzen2700_vmware/master/10.jpg?token=ALKOKBLQZXTODSKAOGORNZS6EMHHO" alt="1" width="200px" height="400px"/>
</p>
