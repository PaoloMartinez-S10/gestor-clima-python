#  Gestor de Clima Mundial

Una aplicación de consola en Python que permite registrar, visualizar y analizar datos climáticos de diferentes ciudades. Los datos se guardan automáticamente en un archivo JSON local, asegurando que la información no se pierda al cerrar el programa.

## Características

* **Registro de Ciudades:** Guarda nombre, país, temperatura mínima y media.
* **Persistencia de Datos:** Uso de `json` para guardar y cargar la información automáticamente.
* **Búsqueda:** Filtra ciudades por nombre o país.
* **Estadísticas:** Calcula automáticamente la ciudad más calurosa, la más fría y el promedio global.
* **Validaciones:** Manejo de errores para evitar que el programa falle si se ingresan textos en lugar de números.

##  Cómo usarlo

1. Clona el repositorio o descarga el archivo `climas.py`.
2. Asegúrate de tener Python instalado.
3. Ejecuta el script en tu terminal:
   ```bash
   python climas.py
