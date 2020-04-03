# grub-conf

Configuration for grub with black/green theme and Shutdown/Reboot/UEFI setup buttons.

## Installation
```
# cp -vf grub /etc/default/
# cp -vf 40_custom /etc/grub.d/
# cp theme/ /boot/grub/themes/
# grub-mkconfig -o /boot/grub/grub.cfg
```
