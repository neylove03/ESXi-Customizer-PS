## Welcome to the ESXi-Customizer-PS GitHub Pages

Full documentation is currently available at the [V-Front.de web site](https://esxi-customizer-ps.v-front.de) and will be gradually migrated to this location.
How to make your own virtual machine server with VMware ESXi
===========
1. Install VMware.PowerCLI
 Install-Module -Name VMware.PowerCLI
 Set-ExecutionPolicy Unrestricted
2. Download ESXi-Customizer-PS.ps1
 https://github.com/VFrontDe/ESXi-Cust...
3. Creating custom ESXi Image
3.1 .\ESXi-Customizer-PS.ps1 -help
3.2 .\ESXi-Customizer-PS.ps1 -v60 -vft -load sata-xahci,net55-r8168 -nsc
4. Create a bootable VMware ESXi installer USB flash drive
5. Install ESXi
