🎓 U-Tutor: tu asistente universitario

U-Tutor es un chatbot interactivo desarrollado con Python, Streamlit y LangChain, potenciado por la API de OpenAI. Su objetivo es brindar a estudiantes universitarios un tutor virtual empático y profesional, capaz de responder dudas académicas de manera clara y cercana.

✨ Características

🤖 Asistente virtual que responde en tiempo real con lenguaje natural.

🎨 Interfaz simple e intuitiva usando Streamlit.

📚 Enfoque académico para apoyar a estudiantes en sus cursos.

🧠 Mantiene historial de chat mientras dura la sesión.

🔒 Uso seguro de la API key de OpenAI mediante .env.

⚠️ Importante sobre la API Key

Por seguridad, la API key de OpenAI NO se comparte en este repositorio. Cada usuario que quiera usar este proyecto debe crear su propia API key en OpenAI y colocarla en un archivo .env.

Cómo crear el archivo .env:

En la raíz del proyecto, crea un archivo llamado .env.

Agrega la siguiente línea, reemplazando TU_API_KEY con tu propia key:

OPENAI_API_KEY=TU_API_KEY

Asegúrate de que .env esté listado en .gitignore para que no se suba a GitHub.

🛠️ Instalación y ejecución

Clonar el repositorio:

git clone https://github.com/andresfgh/U-Tutor.git cd U-Tutor

Crear y activar el entorno virtual:

Crear entorno virtual
python -m venv venv

Activar entorno virtual
Linux / Mac
source venv/bin/activate

Windows
venv\Scripts\activate

Instalar dependencias:

pip install -r requirements.txt

Ejecutar la aplicación:

streamlit run chatbotV1.py

📌 Notas adicionales

No subir tu API key a GitHub.

Este proyecto es educativo y puede ampliarse con:

Base de datos para historial de usuarios.

Integración con otros modelos de IA.

Panel de administración para docentes.