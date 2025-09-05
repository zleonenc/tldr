# conda doctor

> Muestra un informe de salud para tu entorno.
> More information: <https://docs.conda.io/projects/conda/en/latest/commands/doctor.html>.

- Muestra el informe del entorno actualmente activo:

`conda doctor`

- Especifica un entorno por nombre:

`conda doctor {{[-n|--name]}} {{environment_name}}`

- Especifica un entorno por su ruta:

`conda doctor {{[-p|--prefix]}} {{path/to/environment}}`

- Habilita salida detallada (Nota: la bandera `-v` puede repetirse para aumentar el nivel de detalle):

`conda doctor {{[-v|--verbose]}}`
