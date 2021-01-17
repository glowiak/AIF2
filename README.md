# AIF2 - Arch Linux Installer

# First download https://github.com/glowiak/AIF2/releases/download/2.0.0-bios/setup-pre, and type following commands:
  - chmod +x setup-pre
  - ./setup-pre
Follow the instructions. After setup-pre will complete installation type:
  - arch-chroot /mnt
  - curl -L -o setup-postchroot https://github.com/glowiak/AIF2/releases/download/2.0.0-bios/setup-postchroot
  - chmod +x setup-postchroot
  - ./setup-postchroot
Again follow the instructions; when installation will finish type following commands:
  - exit
  - umount -a
  - reboot
# UEFI
  - curl -L -o setup-pre https://github.com/glowiak/AIF2/releases/download/2.0.0-efi/setup-pre && chmod +x setup-pre
  - ./setup-pre
  - Follow the instructions and when done type:
  - arch-chroot /mnt
  - curl -L -o setup-postchroot https://github.com/glowiak/AIF2/releases/download/2.0.0-efi/setup-postchroot && chmod +x setup-postchroot
  - ./setup-postchroot
  - Again follow the instructions, and when it finish type:
  - exit
  - umount -a
  - reboot
