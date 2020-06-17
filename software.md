
* PCB Tester https://caniusevia.com/

To install Via on Arch Linux:

1/ Install `debtap`: yay debtab

2/ Download the .deb install for via

3/ Convert the .deb install for via to an arch package: `debtap via.deb`

4/ Run `sudo pacman -U <debtap-generated-package.`

_The generated arch package might have a filename .zst - just use this filname when installing using pacman._
