-----Documentación del proyecto-----

Para comenzar con el código utilizamos imports que nos permiten usar todas las funciones necesarias para el desarrollo del gestor de recetas. En este caso, trabajamos con las librerías JSON, CVS, OS, requests y matplotlib, cada una con un propósito específico dentro del proyecto.

Creamos un espacio llamado "recetas", donde se almacenan y gestionan los comandos para añadir nuevas recetas. Para evitar futuros errores causados por espacios innecesarios en los datos ingresados, utilizamos strip(),que nos ayuda a eliminar espacios no deseados.

En la opción de listar recetas, el programa recorre el espacio donde están almacenadas y muestra cada receta junto con a sus ingredientes. Esta opción funciona solo si existe al menos una receta registrada; de lo contrario el sistema regresara al menú principal.

Posteriormente, implementamos las funciones de importación y exportación de datos, utilizando los formatos CSV, JSON y TXT. Esto permite guardar la información del gestor o cargarla desde archivos externos.

En cuanto a la API, el programa realizara una solicitud a un servicio web mediante una petición "request" para obtener información. Nuevamente, es importante usar el strip() a los datos ingresados por el usuario para evitar posibles errores. Una vez obtenida la información desde la API, esta se guarda en un archivo JSON. De esta manera, cuando se vuelve a la opción de listar recetas, se puede observar que la nueva información esta junto a las demás recetas.

Finalmente, utilizamos matplotlib para generar dos gráficas que permiten visualizar mejor la información del gestor de recetas. La primera muestra cada receta junto con su número de ingredientes, mientras que la segunda representa el total de ingredientes registrados en el sistema. Estas representaciones  facilitan el análisis de los datos y hacen que la información sea más comprensible.

Disfrute del gestor de recetas. :)


-----Presentacion-----

Jose: 
1 Presentar
2 Hablar del proyecto gestor de recetas, 
3 listar
4 Api

Kini:
1 añadir recetas
2 import/export
3 estadisticas (matplotlib)
4 despedida

