##step 1

En el archivo main.js de la carpeta cliente en la línea 34 en el HTTP.post estan escribiendo directamente en el codigo una contraseña, por seguridad las contraseñas deven ir en archivos de configuración y no directamente en el código.

También se recomienda por mantenibilidad que las urls se definan en archivos de configuración, estos valores sean asignados a variables y sean estan las que se ocupen en el código.
