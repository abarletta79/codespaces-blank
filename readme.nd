📚 Mi Biblioteca Personal
Sistema de gestión de biblioteca local con alta por ISBN usando Google Books API, exportación a CSV y registro de acciones.

🧩 Funcionalidades
- Alta de libros por ISBN (consulta automática de datos)
- Baja de libros
- Listado de biblioteca local
- Verificación de existencia por ISBN
- Exportación a archivo CSV (biblioteca.csv)
- Registro de actividad en logs/app.log

📦 Estructura del proyecto
mi_biblioteca/
├── main.py
├── requirements.txt
├── logs/
│   └── app.log
├── data/
│   ├── biblioteca.json
│   └── biblioteca.csv
├── biblioteca/
│   ├── __init__.py
│   ├── api_libros.py
│   ├── exportador.py
│   ├── gestor.py
│   └── utils.py



🐍 Instalación
1. Crear entorno virtual
python -m venv .venv


2. Activar entorno virtual
- Windows
.venv\Scripts\activate
- Linux/macOS
source .venv/bin/activate


3. Instalar dependencias
pip install -r requirements.txt



▶️ Ejecución
python main.py



📤 Exportar biblioteca
Desde el menú interactivo, opción 5 genera data/biblioteca.csv automáticamente.

🧾 Logs
Todas las acciones se registran en logs/app.log, incluyendo:
- Altas y bajas confirmadas
- ISBN duplicados o inexistentes
- Errores al consultar la API

🛰️ API utilizada
- Google Books API
Se usa para obtener datos por ISBN en tiempo real.
