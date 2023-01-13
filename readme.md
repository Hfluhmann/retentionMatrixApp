
## Requisitos:
- Python 3.11 o posterior
- Si pandas no se encuentra instalado, instalarlo con el siguiente comando en la terminal/consola.

```sh
- pip install pandas
```

## Funcionamiento:
- Tener en la misma carpeta archivos con nombre "BD Solicitudes 2022-presente" y "data.xlsm"
- Nombres distintos romperan el programa
- No tener ninguno de los archivos xlsm (excel) abiertos al ejecutar el programa
- Al ejecutarse el programa se crearan 2 archivos: "Carga (Fecha_actual) TSF.xlsx" y "Carga para subir (Fecha_actual) TSF.xlsx"
- El primer archivo cuenta con la carga del día actual. El segundo archivo, además, tiene eliminadas las columnas "Nombre Completo" y "Embudo"
- Si los archivos creados ya existían, se remplazarán

## Ejecutivos.txt
- En este archivo van todos los ejecutivos activos
- Si un nombre no está en este archivo, NO se le agregaran casos
- Debe ir un nombre por línea, sin caracteres extra
- El nombre del ejecutivo debe estar escrito exactamente igual que en el archivo BD solicitudes
- Para agregar un nombre, apretar ENTER y encribir el nombre en la siguiente línea.
- El programa automaticamente le dara prioridad a asignar casos al ejecutivo con menos casos asignados (a no ser que no se encuentre en el archivo), por lo que si hay cantidades distintas, estas se equipararán.

## Ejecución:
- Iniciar retention.exe