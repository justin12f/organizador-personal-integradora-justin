# Organizador Personal

## Objetivo

Preparar la estructura inicial de una aplicación que, en el futuro, podría
administrar tareas y notas personales. El foco de esta práctica es el flujo de
trabajo (Visual Studio Code, entorno virtual, dependencias, Git y GitHub), no la
programación.

## Tecnologías utilizadas

- Python 3.14
- Entorno virtual `venv`
- Git y GitHub
- Visual Studio Code
- Bibliotecas: `requests`, `python-dotenv`

## Pasos de instalación

1. Clonar el repositorio:
   ```
   git clone https://github.com/justin12f/organizador-personal-integradora-justin.git
   cd organizador-personal-integradora-justin
   ```
2. Crear y activar el entorno virtual:
   ```
   python -m venv .venv
   .venv\Scripts\activate      # Windows
   source .venv/bin/activate    # Linux / macOS
   ```
3. Instalar las dependencias:
   ```
   pip install -r requirements.txt
   ```
4. Ejecutar el proyecto:
   ```
   python src/main.py
   ```

## Dependencias

Registradas en `requirements.txt` (generado con `pip freeze`):

- `requests` — peticiones HTTP.
- `python-dotenv` — carga de variables de entorno desde un archivo `.env`.

## Autor

Justin Emiliano Rodríguez Franco (`justin12f`)
