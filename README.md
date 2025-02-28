# generador-imagenes-flux
Este es un proyecto en Python que utiliza la API de Flux Pro v1.1 para generar imágenes a partir de un prompt.

## Requisitos
- Python 3.x
- Librerías: `requests`, `python-dotenv`

## Configuración
1. Crea un archivo `.env` con las siguientes variables:
   ```env
   API_KEY="tu_api_key_aqui"
   BASE_URL="https://api.us1.bfl.ai"
   OUTPUT_DIR="ia_imagenes"
