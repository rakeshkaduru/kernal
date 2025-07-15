# WHAT IS BOOTLOADER?

a **bootloder** is a small program that:

Runs **before the operating system starts**

Loads the **OS kernel** into memory 

Gives control to the **CPU** start the os

 ---


#  BOOTLOADER ARCHITECTURE?
```text

[Power ON]
     ↓
[First Stage Bootloader]
     ↓
[Second Stage Bootloader]
     ↓
[Kernel Loading]
     ↓
[Init Process / User-space]
     ↓
[Login screen / GUI / Terminal]
```

# Full Linux Boot Process Explained

---
## 1.POWER ON

When you press the power button
~ Eletricity flows to motherboard,CPU,RAM,etc.
~ CPU starts running from a fixed 
