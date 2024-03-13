# Comandos empleados en CMD

Aquí van algunos comandos empleados en la terminal de Linux:

## cd
Empleado para cambiar de directorio y desplazarnos por todo el sistema de carpetas.

Ejemplo:
```
cd /workspaces/exercise-terminal-challenge/thecmdchallenge
```
Para ir al inicio:
```
cd
```
Para subir un nivel:
```
cd ..
```
Para volver al directorio anterior:
```
cd -
```

## ls
Empleado para listar los archivos y subdirectorios ubicados en el directorio.

Ejemplo para devolver listado **incluyendo** archivos ocultos:
```
ls -a
```

## pwd
Empleado para mostrar el directorio actual.

## cp
Empleado para copiar un archivo o directorio y renombrar la copia.

Ejemplo:
```
cp info.txt more_info.txt
```
También se puede copiar directorios enteros utilizando la flag recursiva (-r):

```
cp -r boringfolder/ moreboringfolder/
```

## rm
Empleado para eliminar un archivo o directorio.

Ejemplo:
```
rm more_info.txt
```
También se puede eliminar directorios (**vacíos**) utilizando la flag recursiva (-r):

```
rm -r moreboringfolder/
```

Para eliminar directorios que contengan archivos o subdirectorios, habrá que añadir el flag de *force* (-f):
```
rm -rf moreboringfolder/
```
## mv
Empleado para mover un archivo o directorio.

Ejemplo:
```
mv command_list.txt commands/
```

También se puede emplear para renombrar archivos y mantenerlos en el mismo directorio:
```
mv command_list.txt more_command_list.txt
```

Ampliable.

## REFERENCIAS:
https://kinsta.com/es/blog/linux-comandos/