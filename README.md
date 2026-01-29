CachyOS plymouth theme using the ACPI BGRT graphics as a background
---
![Plymouth Preview](preview.gif)

A clean and modern **Plymouth boot splash theme**, specifically designed for **CachyOS** linux.

---

## 📦 Installation

1. Copy theme directory to the Plymouth themes folder:

    ```bash
    sudo cp -r BGRT-cachyos /usr/share/plymouth/themes/
    ```

2. Set theme as default and rebuild the initramfs:

    ```bash
    sudo plymouth-set-default-theme -R BGRT-cachyos
    sudo mkinitcpio -P
    ```
    
---

## 🔗 Links

- **KDE Store:**  
  https://store.kde.org/p/2345142
