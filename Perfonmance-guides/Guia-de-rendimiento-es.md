<p align="center">
  <img src="https://github.com/user-attachments/assets/dfac0ec2-0f9f-498a-a842-3760fc16422d" alt="">
</p>


<h1 align="center">Rener's Golden Minecraft - ⚡ Guía de Rendimiento ⚡</h1>  

<h2 align="center">Esta guía intentará ofrecer varias opciones para mejorar el rendimiento. Si bien el ModPack ya está bien optimizado, estas opciones me han dado muy buenos resultados y, en general, no son tan complicadas de ejecutar como otros métodos.</h2>

## Asignar Más RAM

Para garantizar una experiencia fluida, Rener's Golden Minecraft requiere un mínimo de 7 GB de RAM asignados a Minecraft (incluso puede ejecutarse con menos con esta guía). A continuación, se muestran los valores recomendados según la RAM disponible en su sistema:

8 GB de RAM: Asignar 7 GB (si es posible, cerrar las aplicaciones en segundo plano para liberar memoria).

16 GB de RAM: Asignar de 8 GB a 10 GB. (Yo solía buscar 8 GB)

32 GB de RAM o más: Asigne 12 GB o más (si es necesario, pero evite asignar demasiado; 8-10 GB son suficientes).

## Cómo asignar más RAM

Dependiendo del lanzador que use, siga estas guías para asignar la RAM correctamente:

[ATLauncher](https://youtu.be/UYYwjqBcQMQ?t=31)

[Aplicación CurseForge](https://youtu.be/GFFRJ9RcrG8?t=31)

<h2 align="center">Optimización de argumentos de Java</h2>

Usar argumentos de Java optimizados puede mejorar significativamente el rendimiento y la estabilidad. En mi experiencia, esto es una buena mejora. A continuación, se muestran los argumentos recomendados para este paquete de modificaciones:

### ``-Xmx8G -Xms8G -XX:+UseG1GC -XX:+UnlockExperimentalVMOptions -XX:MaxGCPauseMillis=100 -XX:+DisableExplicitGC -XX:TargetSurvivorRatio=90 -XX:G1NewSizePercent=40 -XX:G1MaxNewSizePercent=50 -XX:G1ReservePercent=15 -XX:InitiatingHeapOccupancyPercent=30 -XX:G1HeapRegionSize=32M -XX:+UseStringDeduplication -XX:+ParallelRefProcEnabled``

## Ajuste de los valores de RAM en los argumentos

Reemplace los valores de **``8G``** con el número apropiado según la **RAM disponible**:

### 8 GB de RAM: ``-Xmx7G -Xms7G``

### 16 GB de RAM: ``-Xmx8G -Xms8G``

### 32 GB de RAM: ``-Xmx12G -Xms12G``

## Cómo aplicar argumentos de Java

Al menos en [CurseForgeApp](https://www.curseforge.com/download/app) es muy sencillo y otros lanzadores tienen sus propias reglas, como por ejemplo la oficial.
![image](https://github.com/user-attachments/assets/81ad0a67-6177-4f7d-a86e-d70efece224c)
Pulsa el icono del engranaje. ![image](https://github.com/user-attachments/assets/4b2f36f3-6caf-40da-ab45-a2b21fc25412)
Luego, selecciona Minecraft.
![image](https://github.com/user-attachments/assets/a51437a0-9582-4a3d-b696-eaf055ff65ef)
Finalmente, pega los argumentos de Java, asegurándote de modificar la sección **``8G``** según tu sistema. Puedes presionar "X" o simplemente volver a la configuración anterior; la próxima vez que inicies el paquete de modificaciones, se aplicarán los argumentos.

<h2 align="center">Optimizaciones de Windows</h2>

## Establecer la prioridad del proceso de Java (si realmente lo necesitas)
Es posible asignar alta prioridad al proceso principal de Java, haciendo que Windows lo priorice sobre el resto de los procesos. Esto puede mejorar significativamente el rendimiento, pero solo lo recomiendo si tu PC tiene problemas para procesar Java.
Aumentar la prioridad de los procesos de Java puede mejorar ligeramente el rendimiento:

1. Abre el Administrador de tareas (`Ctrl + Mayús + Esc`).

2. Ve a la pestaña Detalles.

3. Busca `javaw.exe` o `java.exe` (al ejecutar Minecraft).

4. Haz clic derecho y establece la prioridad en Alta (**¡No en tiempo real!**).

<h2 align="center">Configuración de rendimiento de Windows</h2>

Ajusta la configuración de Windows para priorizar el rendimiento sobre la calidad visual:

1. Abre Propiedades del sistema (`Win + R`, luego escribe `sysdm.cpl`).

2. Ve a la pestaña Avanzadas.

3. En Rendimiento, haz clic en Configuración.

4. Selecciona Ajustar para obtener el mejor rendimiento (opcional: activa "Suavizar bordes de las fuentes de pantalla" para obtener mejores efectos visuales, bueno, solo para las fuentes atractivas).

Para obtener una guía detallada sobre esto (no es demasiado complicado, para ser sincero), [sigue esto](https://gigperformer.com/docs/ultimate-guide-to-optimize-windows-for-stage/optimizevisualeffects.html).
