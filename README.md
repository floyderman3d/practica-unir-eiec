# Repo para EIEC - DevOps - UNIR

Este repositorio nos servirÃ¡ para demostrar el uso de Git en la asignatura de EIEC y muchas cosas mas.

---

Los comandos del Makefile funcionarÃ¡n en Linux y MacOS. En caso de usar Windows, necesitarÃ¡s adaptarlos o ejecutarlos en una mÃ¡quina virtual Linux.

## EjecuciÃ³n

python3 main.py <filename> <dup>
  filename: **ruta** al fichero que contiene la lista de palabras, una por lÃ­nea
  dup: **yes|no**, yes para eliminar palabras duplicadas, no para mantener la lista

## EjecuciÃ³n con el Makefile
Para ejecutar en Docker:

	make run

Para ejecutar en local:

	make run-local
          
## Cambios

PMT: Nuevo fichero "palabras.txt", el cual serÃ¡utilizado en el script como fichero de entrada.
     Modificado Makefile para que se pase por parÃmetro el nuevo fichero de palabras.
