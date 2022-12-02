# Arquitectura de Computadoras
- [Programas y Binarios](01 - Introduccion.md#Programas y Binarios)
	- [Compilación y Linkedición en C](01 - Introduccion.md##Compilación y Linkedición en C)
	- [Ejecución de un programa](01 - Introduccion.md##Ejecución de un programa)
	- [Programa en Memoria](01 - Introduccion.md##Programa en Memoria)
	- [Introducción al Sistema Operativo](01 - Introduccion.md##Introducción al Sistema Operativo)
		- [System Calls](01 - Introduccion.md###System Calls)
- [Procesadores y Lenguaje ASM](02 - Procesador y Lenguaje ASM.md#Procesadores y Lenguaje ASM)
	- [Arquitectura de 80386](02 - Procesador y Lenguaje ASM.md##Arquitectura de 80386)
- [Assembly](03 - Assembly.md#Assembly)
	- [Compilacion y Linkedicion](03 - Assembly.md##Compilacion y Linkedicion)
	- [Secciones](03 - Assembly.md##Secciones)
		- [Instrucciones para Reservar Memoria](03 - Assembly.md###Instrucciones para Reservar Memoria)
	- [Modos de Direccionamiento](03 - Assembly.md##Modos de Direccionamiento)
	- [Escritura y Lectura de Memoria](03 - Assembly.md##Escritura y Lectura de Memoria)
	- [Punto de Entrada](03 - Assembly.md##Punto de Entrada)
		- [Argumentos de Linea de Comando](03 - Assembly.md###Argumentos de Linea de Comando)
	- [Stack](03 - Assembly.md##Stack)
	- [System Calls](03 - Assembly.md##System Calls)
- [Assembly y C](04 - Assembly y C.md#Assembly y C)
	- [Compilacion y Linkedicion](04 - Assembly y C.md##Compilacion y Linkedicion)
	- [Punto de Entrada](04 - Assembly y C.md##Punto de Entrada)
	- [Pasaje de Argumentos](04 - Assembly y C.md##Pasaje de Argumentos)
		- [Pasaje de Argumentos por Registro](04 - Assembly y C.md###Pasaje de Argumentos por Registro)
		- [Pasaje de Argumentos por Stack](04 - Assembly y C.md###Pasaje de Argumentos por Stack)
		- [Retorno de Datos](04 - Assembly y C.md###Retorno de Datos)
	- [Manejo del Stack](04 - Assembly y C.md##Manejo del Stack)
		- [StackFrame](04 - Assembly y C.md###StackFrame)
		- [Alinemiento a Palabra](04 - Assembly y C.md###Alinemiento a Palabra)
	- [Interoperabilidad entre C y Assembly (`32-bits`)](04 - Assembly y C.md##Interoperabilidad entre C y Assembly (`32-bits`))
		- [Variables](04 - Assembly y C.md###Variables)
		- [Llamada de funciones de C en Assembly](04 - Assembly y C.md###Llamada de funciones de C en Assembly)
		- [Llamada de funciones de Assembly en C](04 - Assembly y C.md###Llamada de funciones de Assembly en C)
	- [Interoperabilidad entre C y Assembly (`64-bits`)](04 - Assembly y C.md##Interoperabilidad entre C y Assembly (`64-bits`))
- [Transmisión](05 - Arquitectura.md#Transmisión)
	- [Codificación](05 - Arquitectura.md##Codificación)
		- [Codificación Unipolar](05 - Arquitectura.md###Codificación Unipolar)
		- [Codificación de línea](05 - Arquitectura.md###Codificación de línea)
- [Arquitecturas](05 - Arquitectura.md#Arquitecturas)
	- [Von Neumann](05 - Arquitectura.md##Von Neumann)
	- [Harvard](05 - Arquitectura.md##Harvard)
- [Memoria](05 - Arquitectura.md#Memoria)
	- [Estructura](05 - Arquitectura.md##Estructura)
		- [Mapa de memoria](05 - Arquitectura.md###Mapa de memoria)
	- [Clasificación de Memorias](05 - Arquitectura.md##Clasificación de Memorias)
		- [Memoria ROM](05 - Arquitectura.md###Memoria ROM)
		- [Memoria RAM](05 - Arquitectura.md###Memoria RAM)
	- [Tiempo de Acceso](05 - Arquitectura.md##Tiempo de Acceso)
- [Sistemas](05 - Arquitectura.md#Sistemas)
	- [Ejemplos](05 - Arquitectura.md##Ejemplos)
- [Interrupciones](06 - Interrupciones.md#Interrupciones)
	- [PIC](06 - Interrupciones.md##PIC)
	- [Interrupciones en Modo Protegido](06 - Interrupciones.md##Interrupciones en Modo Protegido)
		- [Excepciones](06 - Interrupciones.md###Excepciones)
	- [Interrupciones en Multi-Core](06 - Interrupciones.md##Interrupciones en Multi-Core)
- [Integrados](08 - Integrados.md#Integrados)
	- [Clock](08 - Integrados.md##Clock)
- [Periféricos](09 - Perisfericos.md#Periféricos)
	- [Timer Programable](09 - Perisfericos.md##Timer Programable)
	- [Real Time Clock](09 - Perisfericos.md##Real Time Clock)
- [Modo  Protegido](10 - Modo Protegido.md#Modo  Protegido)
	- [Conmutación de Tareas](10 - Modo Protegido.md##Conmutación de Tareas)
	- [Memory Management Unit (MMU)](10 - Modo Protegido.md##Memory Management Unit (MMU))
		- [Descriptores](10 - Modo Protegido.md###Descriptores)
	- [Privilegios E/S](10 - Modo Protegido.md##Privilegios E/S)
- [Memoria Virtual](11 - Memoria Virtual.md#Memoria Virtual)
	- [Paginación](11 - Memoria Virtual.md##Paginación)
		- [Protección Combinada](11 - Memoria Virtual.md###Protección Combinada)
		- [Modelo FLAT](11 - Memoria Virtual.md###Modelo FLAT)
	- [Swapping](11 - Memoria Virtual.md##Swapping)
		- [Ejemplo](11 - Memoria Virtual.md###Ejemplo)
- [Memoria Cache](12 - Memoria Cache.md#Memoria Cache)
	- [Comunicación con la memoria RAM](12 - Memoria Cache.md##Comunicación con la memoria RAM)
		- [Ejemplo](12 - Memoria Cache.md###Ejemplo)
	- [Mapeos](12 - Memoria Cache.md##Mapeos)
	- [Política de Sustitución](12 - Memoria Cache.md##Política de Sustitución)
	- [Actualizacion de RAM](12 - Memoria Cache.md##Actualizacion de RAM)
- [Procesadores de 64 bits](13 - Procesadores de 64 bits.md#Procesadores de 64 bits)
	- [Diferenciación de los Procesadores](13 - Procesadores de 64 bits.md##Diferenciación de los Procesadores)
	- [Caso Pentium](13 - Procesadores de 64 bits.md##Caso Pentium)
	- [Caso Pentium Pro](13 - Procesadores de 64 bits.md##Caso Pentium Pro)
	- [Physical Address Extension](13 - Procesadores de 64 bits.md##Physical Address Extension)
	- [Intel 64 / EM64T](13 - Procesadores de 64 bits.md##Intel 64 / EM64T)
- [ARM](14 - ARM.md#ARM)
