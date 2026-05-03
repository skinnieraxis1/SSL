# SSL
Repositorio para Sintaxis y Semántica | UTN | 2026

## Instalaciones

Instalaremos el gestor de paquetes **msys2** a través de https://www.msys2.org </br>

*Todas las instalaciones las hice dentro de la terminal de msys2*

```
pacman -Syu
pacman -Su
```
> Actualizamos los paquetes

```
pacman -S mingw-w64-ucrt-x86_64-gcc
```
> Instalamos el gcc, ya con esto vamos a poder usar el C23 (aunque todavía se usan flags del c2x)

```
pacman -S make
```
> Por último instalamos make

## Comandos
```
gcc -std=c2x hello.c -o hello.exe
./hello.exe
```
> Generar y ejecutar hello.exe a través del c23/c2x

```
./hello.exe > output.txt
cat output.txt
```
> Imprimit el output de hello.c en output.txt y leerlo con el cat

```
make
make run
```
> Una ves que terminé el archivo make lo ejecuté (Quedó un output.txt afuera y uno adentro porque después pense que iba a quedar mejor todo dentro de una carpeta)

