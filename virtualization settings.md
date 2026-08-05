# Virtualization Settings

**Host OS: Windows 10**

**Guest OS: Lubuntu 26.04**

**Virtualization App: VirtualBox**

Something that I noticed when I was virtualizing Lubuntu for the first time is how sensitive Linux is to wrong configurations

Forgetting to check✅ UEFI in VM settings = fatal error before even getting to the live session

Forgetting to choose Lubuntu instead of Ubuntu in VM settings (VirtualBox chose Ubuntu automatically) = kernel panic

And make sure to give it enough VRAM because that gave me a fatal error too (my hardware had a dedicated GPU, so I was able to give the VM the whole integrated GPU)

## Unlike Debian (headless)

It doesn't bother UEFI being unchecked

And it's a base distro (not based on another), so either the user or VirtualBox can't mess up choosing which OS this is in VM settings