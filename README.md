# hp-15-da0004tu-notbook-big-sur-efi
efi files to install macOS big sur using opencore


Start with BIOS reset to defaults and then disable all kind of security and TPM. System works well with Fastboot enabled, but for debugging and playing with your setup is better to disable Fast Boot. It's also recommended to disable Intel TXT technology and then disable Virtualization Technology for Directed I/O (VTd). OpenCore config disables this instead.


Use GENSMBIOS and generate a new keys to the plist and enjoy
