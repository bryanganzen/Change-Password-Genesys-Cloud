# Change-Password-Genesys-Cloud
Este desarrollo cambia la contraseña de forma masiva para usuarios de Genesys Cloud

# Password Changer para Genesys Cloud

## Descripción

Esta aplicación web permite a los usuarios cargar un archivo Excel con nombres de usuarios y cambiar sus contraseñas en Genesys Cloud. La aplicación facilita la carga de archivos, la selección de la organización correspondiente y la actualización de las contraseñas de forma masiva.

### Características principales

- **Carga de Archivo Excel**: Permite cargar un archivo Excel con los nombres de usuario para los cuales se desea cambiar la contraseña.
- **Selección de Organización**: Los usuarios pueden seleccionar la organización correspondiente para actualizar las contraseñas de los usuarios.
- **Actualización Masiva de Contraseñas**: Cambia las contraseñas de los usuarios seleccionados en la organización correspondiente.
- **Interfaz Intuitiva**: Proporciona una interfaz amigable y fácil de usar para la gestión de contraseñas.

## Requisitos

- Python 3.x
- Librerías necesarias (ver `requirements.txt`):
  - `Flask`
  - `pandas`
  - `openpyxl`
  - `PureCloudPlatformClientV2`
- Credenciales y permisos necesarios para cambiar contraseñas en Genesys Cloud.

## Uso

- Inicia la aplicación Flask: `python app.py`
- Abre `http://localhost:5000` en tu navegador.
- En la página principal `index.html`:
  - Carga un archivo Excel con los nombres de usuario para los cuales deseas cambiar la contraseña.
  - Selecciona la organización correspondiente.
  - Haz clic en "Cargar" para procesar el archivo.
- En la página de resultados `results.html`:
  - Selecciona los usuarios para los cuales deseas cambiar la contraseña.
  - Introduce la nueva contraseña en el campo correspondiente.
  - Haz clic en "Cambiar Contraseña" para realizar la actualización.
- Recibirás una confirmación de los cambios realizados.

## Estructura del Proyecto

- `app.py`: Script principal que maneja la lógica de la aplicación Flask y la integración con Genesys Cloud.
- `index.html`: Página principal donde se carga el archivo Excel y se selecciona la organización.
- `results.html`: Página de resultados donde se muestran los usuarios y se permite cambiar las contraseñas.
- `requirements.txt`: Archivo de dependencias necesarias para el proyecto.

## Personalización

- Puedes personalizar el estilo de la aplicación modificando los archivos CSS dentro de los archivos `index.html` y `results.html`.
- Asegúrate de actualizar las credenciales y la configuración de la API en app.py para conectarte al entorno adecuado de Genesys Cloud.

## Contacto

Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto.

- Bryan Ganzen
- 55 75 45 65 81
