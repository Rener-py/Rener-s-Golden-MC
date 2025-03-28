<h1 align="center">Rener's Golden Minecraft - ⚡ Perfomance Guide ⚡</h1>

<h2 align="center">This guide will try to provide various options to improve perfomance even though the ModPack is already well optimized, this options have given me very good results and that are generally not as complicated to perform as other methods.</h2>

## Allocate More RAM


To ensure a smooth experience, Rener's Golden Minecraft requires a minimum of 7GB of RAM allocated to Minecraft (it can even run with less with this guide). Below are the recommended values based on your system's available RAM:

8GB RAM: Allocate 7GB (if possible, close background applications to free memory).

16GB RAM: Allocate 8GB-10GB. (I personally used to locate 8GB)

32GB RAM or more: Allocate 12GB+ (if necessary, but avoid excessive allocation, 8-10GB it's way enough tho).

## How to Allocate More RAM

Depending on the launcher you use, follow these guides to properly allocate RAM:

[ATLauncher](https://youtu.be/UYYwjqBcQMQ?si=KGmMrAs3A_nM3SRS)

[CurseForge App](https://youtu.be/GFFRJ9RcrG8?si=kQff7QNh8oOwAA-V)

<h2 align="center">Java Arguments Optimization</h2>

Using optimized Java arguments can significantly improve performance and stability. In my experience this is a good boost. Below are the recommended arguments for this modpack:

### ``-Xmx8G -Xms8G -XX:+UseG1GC -XX:+UnlockExperimentalVMOptions -XX:MaxGCPauseMillis=100 -XX:+DisableExplicitGC -XX:TargetSurvivorRatio=90 -XX:G1NewSizePercent=40 -XX:G1MaxNewSizePercent=50 -XX:G1ReservePercent=15 -XX:InitiatingHeapOccupancyPercent=30 -XX:G1HeapRegionSize=32M -XX:+UseStringDeduplication -XX:+ParallelRefProcEnabled``

## Adjusting RAM Values in the Arguments

Replace the **``8G``** values with the appropriate number based on your **available RAM**:

### 8GB RAM: ``-Xmx7G -Xms7G``

### 16GB RAM: ``-Xmx8G -Xms8G``

### 32GB RAM: ``-Xmx12G -Xms12G``

## How to Apply Java Arguments

At least in [CurseForgeApp](https://www.curseforge.com/download/app) it's very simple and other launcher have their way, for example official one.
![image](https://github.com/user-attachments/assets/81ad0a67-6177-4f7d-a86e-d70efece224c)
Press the gear icon.
![image](https://github.com/user-attachments/assets/4b2f36f3-6caf-40da-ab45-a2b21fc25412)
Then select Minecraft.
![image](https://github.com/user-attachments/assets/a51437a0-9582-4a3d-b696-eaf055ff65ef)
Finally, paste the Java arguments there, making sure to modify the **``8G``** section according to your system. You can then press "X" or simply revert back; the next time you launch the modpack, the arguments will be applied.

<h2 align="center">Windows Optimizations</h2>

## Set Java process priority (if you really need to)
It is possible to assign high priority to the main Java process, making Windows put it above the rest of the processes. This can significantly improve performance, but I only recommend it if your PC really has trouble handling Java.
ncreasing Java's process priority can slightly improve performance:

1. Open Task Manager (`Ctrl + Shift + Esc`).

2. Go to the Details tab.

3. Find `javaw.exe` or `java.exe` (running Minecraft).

4. Right-click it and set priority to High (**Not Real-Time!**).

<h2 align="center">Windows Performance Settings</h2>

Adjust Windows settings to prioritize performance over good visuals:

1. Open System Properties (`Win + R`, then type `sysdm.cpl`).

2. Go to the Advanced tab.

3. Under Performance, click Settings.

4. Select Adjust for best performance (optional: enable "Smooth edges of screen fonts" for better visuals, well just for the cute fonts).

For a detailed guide about that (not too complicated tbh), [follow this](https://gigperformer.com/docs/ultimate-guide-to-optimize-windows-for-stage/optimizevisualeffects.html).
