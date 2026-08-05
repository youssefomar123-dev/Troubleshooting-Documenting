# VirtualBox Extention Pack Clash

**Host OS: Windows 10**

**Guest OS: Debian 13**

**Problem: VM not booting up**

**Error Message:** Driver name clash. Another driver with the same name as the one being registered exists. (VERR_PDM_USB_NAME_CLASH)

---

The issue was that the VirtualBox Extention Pack of an older version existed and that the newer version was trying to use it

So the solution was to simply delete it