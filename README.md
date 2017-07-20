![Redux - Header](img/repo-header.png)

## JSON Server para Redux-TLP-2017

Este repositorio contiene un JSON-Server basico el cual es utilizado en la rama redux-api-request del repositorio redux-tlp-2017.

## Recursos necesarios

Para poder ejecutar el servidor, necesitas:

- Gestor de versiones [Git](https://git-scm.com/)
- [NodeJS](https://nodejs.org/es/download/current/)
- Instalar JSON-Server como paquete global de node:
```
npm install -g json-server
```

## Clonar y ejecutar el proyecto

**1. Clonar el repositorio:**

```
git clone https://github.com/ivanbtrujillo/redux-tlp-2017-server.git

```

**2. Instalar dependencias:**
```
cd redux-tlp-2017-server && npm install 
```

**3. Ejecutar el servidor en el puerto 4000 (en una ventana de consola diferente a la del front):**
```
json server --watch db.json --port 4000
```
