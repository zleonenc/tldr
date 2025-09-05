# conda create

> Crear nuevos entornos de conda.
> Más información: <https://docs.conda.io/projects/conda/en/latest/commands/create.html>.

- Crear un nuevo entorno llamado `py39`, e instalar Python 3.9 y NumPy v1.11 o superior:

`conda create {{[-y|--yes]}} {{[-n|--name]}} {{py39}} python={{3.9}} "{{numpy>=1.11}}"`

- Hacer una copia exacta de un entorno:

`conda create --clone {{py39}} {{[-n|--name]}} {{py39-copy}}`

- Crear un nuevo entorno con un nombre específico e instalar un paquete dado:

`conda create {{[-n|--name]}} {{env_name}} {{package}}`
