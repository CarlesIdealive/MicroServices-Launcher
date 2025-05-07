
## Dev
1. Clonar el repositorio
2. Ejecutar un .env basado en .env.template
3. Ejecutar el comando `git submodule update --init --recursive` para reconstruir los submodulos
4. Ejecutar el comando `docker compose up --build`

## Launcher - Ubicacion de Submodules

1. Añadir el submodule, donde repository_url es la url del repositorio y directory_name es el nombre de la carpeta donde quieres que se guarde el sub-módulo (no debe de existir en el proyecto) 
    `git submodule add <repository_url> <directory_name>`

2. Para actualizar las referencias de los sub-módulos (sino se ve reflejado en el Launcher un cambio es un submodulo)
    `git submodule update --remote`

