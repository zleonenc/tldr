# conda

> Gestión de paquetes, dependencias y entornos para cualquier lenguaje de programación.
> Algunos subcomandos, como `create`, tienen su propia documentación de uso.
> Más información: <https://docs.conda.io/projects/conda/en/latest/commands/index.html>.

- Crear un nuevo entorno e instalar en él los paquetes indicados:

`conda create {{[-n|--name]}} {{environment_name}} {{python=3.9 matplotlib}}`

- Listar todos los entornos:

`conda info {{[-e|--envs]}}`

- Activar un entorno:

`conda activate {{environment_name}}`

- Desactivar un entorno:

`conda deactivate`

- Eliminar un entorno (remover todos los paquetes):

`conda remove {{[-n|--name]}} {{environment_name}} --all`

- Instalar paquetes en el entorno actual:

`conda install {{python=3.4 numpy}}`

- Listar los paquetes instalados en el entorno actual:

`conda list`

- Eliminar paquetes no usados y cachés:

`conda clean {{[-a|--all]}}`
