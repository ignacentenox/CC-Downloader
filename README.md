# PyQt Downloader

Este proyecto es una aplicación de escritorio desarrollada en Python utilizando PyQt6, diseñada para permitir a los usuarios descargar música y videos en la máxima calidad posible a partir de enlaces de listas de reproducción.

## Estructura del Proyecto

```
pyqt-downloader
├── src
│   ├── main.py               # Punto de entrada de la aplicación
│   ├── ui
│   │   └── main_window.ui    # Diseño de la interfaz de usuario
│   ├── downloader.py         # Lógica de descarga de música y videos
│   └── utils.py              # Funciones auxiliares
├── requirements.txt          # Dependencias del proyecto
├── README.md                 # Documentación del proyecto
└── .gitignore                # Archivos y directorios ignorados por Git
```

## Instalación

1. Clona el repositorio:
   ```
   git clone <URL_DEL_REPOSITORIO>
   cd pyqt-downloader
   ```

2. Instala las dependencias:
   ```
   pip install -r requirements.txt
   ```

## Uso

1. Ejecuta la aplicación:
   ```
   python src/main.py
   ```

2. En la ventana principal, pega el enlace de la lista de reproducción que deseas descargar.

3. Selecciona el formato de descarga (audio o video) y haz clic en el botón de descarga.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, por favor abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT.