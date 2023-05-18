# Aplicación Web de Recordatorio de Actividades

Esta es una aplicación web simple de Recordatorio de Actividades construida utilizando Flask y MongoDB. La aplicación te permite agregar tareas, ver tareas, actualizar tareas y eliminar tareas. La aplicación utiliza las siguientes bibliotecas:

* Flask
* pymongo
* bson

## Cómo usar

1. Instala Flask y MongoDB.
2. Clona el repositorio en tu máquina local.
3. Abre una terminal y navega hasta el directorio del proyecto.
4. Inicia el servidor de MongoDB con el siguiente comando:
```
mongod
```
5. En una nueva terminal, inicia el servidor de Flask con el siguiente comando:
```
python app.py
```
6. Abre tu navegador y ve a la siguiente URL:
```
http://localhost:5000/
```
7. Ahora puedes usar la aplicación para agregar, ver, actualizar y eliminar tareas.

## Funciones

* Ver todas las tareas
* Ver tareas no completadas
* Ver tareas completadas
* Marcar tareas como completadas o no completadas
* Agregar nuevas tareas
* Actualizar tareas existentes
* Eliminar tareas
* Buscar tareas por palabra clave o referencia
