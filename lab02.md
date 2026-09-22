# Informe de Laboratorio 02: Entorno RISC-V, QEMU y Llamadas al Sistema en xv6

**Estudiante:** Wuill Pillaca  
**Institución:** Universidad Nacional de San Cristóbal de Huamanga  
**Curso:** Sistemas Operativos  

---

## 1. Resumen de Actividades
En este laboratorio se instaló la cadena de herramientas (*toolchain*) para la arquitectura RISC-V y el emulador QEMU en un entorno Ubuntu (WSL2). Se clonó, compiló y ejecutó el sistema operativo **xv6-riscv**, realizando pruebas en su intérprete de comandos y analizando el código fuente de sus llamadas al sistema (*system calls*).

---

## 2. Comandos Ejecutados en el Shell de xv6 (Parte A y B)

Dentro de la simulación de QEMU (`make qemu`), se ejecutaron los siguientes comandos:

```bash
ls
echo Wuill Pillaca
mkdir practica
ls
cat README
echo prueba de sistema de archivos > archivo.txt
cat archivo.txt
wc archivo.txt
