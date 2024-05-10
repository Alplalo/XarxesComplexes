# XAXES COMPLEXES

## Makefile

El Makefile incluido automatiza varias tareas relacionadas con la compilación y ejecución de los programas. Aquí hay una descripción de los comandos más importantes:



### <span style="color:purple;">make xfor</span>

Este comando ejecuta `python3 retocar.py` en el archivo `Gowalla_edges.txt`, luego compila `xarxes_for.f90` con gfortran y ejecuta el archivo resultante en `Gowalla_edges_new.txt`.



### <span style="color:purple;">make xpy</span>

Este comando ejecuta `python3 retocar.py` en el archivo `Gowalla_edges.txt` y luego `python3 xarxes.py` en `Gowalla_edges_new.txt`.



### <span style="color:purple;">make cleanw</span>

Este comando elimina el archivo ejecutable y `Gowalla_edges_new.txt` en `Windows`.



### <span style="color:purple;">make clean</span>

Este comando elimina el archivo ejecutable y `Gowalla_edges_new.txt` en `Linux`.



### <span style="color:purple;">make help</span>

Este comando muestra la descripción de los comandos del Makefile.
