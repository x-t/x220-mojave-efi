# x220-mojave-efi
EFI configuration that successfully boots Mojave 10.14.6 on the X220!

If you're interested in this, you may be interested in [Catalina on the X220!](https://github.com/x-t/x220-catalina-efi) 

## A note on upgrading 10.14.5->10.14.6 via System Preferences
After upgrade, it might not boot, this isn't a Clover issue, it's rather a patch issue.  
Re-run dosdude1's patches from a 10.14.6 installer.

## A note on alternative audio kexts
For my install, I replace the `AppleHDA_20672.kext` with the two in the zip file.  
This doesn't seem to work on the installer, so don't replace it there.  
On instructions, replace it in your EFI, replace it somewhere in /System or /Library, I don't remember anymore, and use Kext Utility.  
Why would you want to do this? Personally audio levels get buggy for me when switching from headphones to speakers and vice versa, and these ones are more stable.

## My hardware
* Intel® Core™ i5-2520M Processor
* DW1510 for Wi-Fi
* No webcam
* A standard 1366x768 panel

### This isn't a tutorial, if you need one, see [b-ggs/x220-hackintosh](https://github.com/b-ggs/x220-hackintosh)
