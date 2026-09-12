---

## 📚 Troubleshooting Topics

### 1. Root Password Troubleshooting

Covers the process of recovering a forgotten root password,
including:

- GRUB boot menu
- Editing the Linux boot parameters
- Switching the root filesystem to read-write mode
- Resetting the root password
- SELinux relabeling
- Rebooting into the normal system

### 2. GRUB Boot Troubleshooting

Covers troubleshooting a system that fails to boot correctly
or stops at the GRUB prompt.

Topics include:

- GRUB configuration
- Rescue environment
- CentOS Stream troubleshooting
- `chroot`
- GRUB installation
- GRUB configuration regeneration

### 3. Kernel & initramfs Troubleshooting

Covers recovery when the initramfs file is removed or damaged.

Topics include:

- Kernel and initramfs
- Boot failure troubleshooting
- Rescue environment
- `chroot`
- Regenerating initramfs
- `dracut`
- System recovery

---

## 🛠️ Skills Practiced

- Linux Troubleshooting
- GRUB Troubleshooting
- Root Password Recovery
- Kernel Troubleshooting
- initramfs Recovery
- Rescue Environment
- System Recovery
- Boot Troubleshooting
- SELinux Relabeling

---

## 💻 Commands Used

```text
mount
passwd
touch
chroot
grub2-install
grub2-mkconfig
dracut
exit
