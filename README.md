# LinuxBoot (linuxboot)
LinuxBoot is a Linux Foundation firmware project that uses a Linux kernel and initramfs as a bootloader, replacing specific firmware functionality such as UEFI DXE. It provides faster, more reliable, and more secure boot processes by leveraging the well-tested Linux kernel for hardware initialization. Core components include u-root (the ramfs builder), the LinuxBoot build system, and the NERF (Non-Extensible Reduced Firmware) heritage from Google.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/linuxboot/refs/heads/main/apis.yml)

## Scope
- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:
 - Boot, Firmware, Hardware, Linux Foundation, u-root, UEFI

## Timestamps
- **Created:** 2026-03-16
- **Modified:** 2026-04-28

## APIs

### LinuxBoot Build System
The LinuxBoot project's build system and tooling for replacing UEFI DXE with a Linux kernel-based boot environment. Includes integrations with coreboot/LinuxBoot and UEFI PEI/LinuxBoot configurations.

**Human URL:** [https://www.linuxboot.org/](https://www.linuxboot.org/)

#### Tags:
 - Boot, Firmware, Build

#### Properties
- [Documentation](https://book.linuxboot.org)
- [Source Code](https://github.com/linuxboot/linuxboot)

### u-root
u-root is a Go-based universal root filesystem and ramfs builder used by LinuxBoot to assemble a minimal initramfs containing the userspace tools needed for booting.

**Human URL:** [https://u-root.org/](https://u-root.org/)

#### Tags:
 - Initramfs, Go, Userspace

#### Properties
- [Documentation](https://u-root.org/)
- [Source Code](https://github.com/u-root/u-root)

## Common Properties
- [LinuxBoot Book](https://book.linuxboot.org)
- [GitHub Organization](https://github.com/linuxboot)
- [Website](https://www.linuxboot.org/)

## Maintainers
**FN:** Kin Lane
**Email:** info@apievangelist.com
