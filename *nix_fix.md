### Помилка ACPI

Відкриваємо `/etc/default/grub` з правами root в будь якому тектовому редакторі
Приклад команди `sudo gedit /etc/default/grub` вносимо наступні дані

`#Видаляємо помилки під час завантаження операційної сиситеми (стосується проблем зі старим біосом) після збереження змін виконати наступну команду sudo update-grub
GRUB_CMDLINE_LINUX_DEFAULT='quiet splash loglevel=3'`

Збережіть зміни та виконийте в терміналі команду `sudo update-grub`


### Встановлення VMWARE 17 на nix

`chmod +x VMware-Workstation-Full-17.0.0-20800274.x86_64.bundle`
`sh VMware-Workstation-Full-17.0.0-20800274.x86_64.bundle`
