# Programación Concurrente

Un **programa** es una secuencia de instrucciones escrita para ealizar una tarea especifica en una computadora. Es un elemento estático. Un  **proceso** es un programa en ejecución que tiene asignado cierto procesamiento y recursos.

Existen 4 modelos de programación:

- **Modelo Secuencial**: Hay un unico procesador y los procesos se corren de forma intermitente utilizando a un scheduler. Hay varias formas de implementar al scheduler, puede ser first-come first-server, intercalar procesos, round robbin, etc.
- **Modelo Concurrente**: Se separa a la logica en diferentes threads y estos corren en paralelo, aunque comparten al mismo proceso. Para ejecutar distintos threads en un programa de Java se tiene que usar la interfaz `ExecutorService`.