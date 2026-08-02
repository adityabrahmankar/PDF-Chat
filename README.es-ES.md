

# PDF Chatbot

El Chatbot de PDF es una aplicación basada en la web que permite a los usuarios cargar archivos PDF y hacer preguntas sobre el contenido de dichos archivos. El chatbot utiliza OpenAI GPT y Pinecone para proporcionar respuestas precisas y relevantes basadas en los PDF cargados.

## Tabla de contenido

- [Instalación](#installation)
- [Uso](#usage)
- [Contribuir](#contributing)
- [Licencia](#license)

## Instalación

Para configurar el proyecto PDF Chatbot en su máquina local, siga estos pasos:

1. Clone el repositorio: 
git clone https://github.com/adityabrahmankar/PDF-Chat.git


2. Instale los paquetes de Python necesarios:
pip install -r requirements.txt


3. Configure las variables de entorno:
export OPENAI_API_KEY="your_openai_api_key"
export PINECONE_API_KEY="your_pinecone_api_key"
export PINECONE_API_ENV="your_pinecone_api_environment"
export OPENAI_PROMPT="your_openai_prompt"

Reemplace los valores de marcador de posición por sus claves de API reales y otra información requerida.

4. Ejecute la aplicación Flask:
python app.py

La aplicación estará accesible en `http://0.0.0.0:8080`.

## Uso

Para utilizar el Chatbot de PDF, siga estos pasos:

1. Acceda a la aplicación en `http://0.0.0.0:8080`.

2. Cargue uno o más archivos PDF haciendo clic en "Choose Files" y seleccionando los archivos desde su máquina local. Luego, haga clic en "Upload PDFs" para enviar los archivos al chatbot.

3. Una vez que los archivos PDF estén cargados, podrá comenzar a hacer preguntas sobre el contenido de los archivos subidos. Escriba su pregunta en el cuadro de entrada y haga clic en el icono del avión de papel para enviar su pregunta.

4. El chatbot analizará el contenido de los PDF cargados y proporcionará una respuesta basada en los documentos.

## Contribuir

¡Bienvenidas las contribuciones al proyecto PDF Chatbot! Aquí tiene instrucciones sobre cómo puede colaborar:

1. Realice un fork del repositorio.

2. Cree una nueva rama para su funcionalidad o corrección de errores:
git checkout -b my-feature

3. Realice cambios en el código y confirme (commit) sus cambios:
git add .
git commit -m "Add my feature"

4. Envíe (push) sus cambios a su fork:

5. Cree una solicitud de extracción (pull request) en el repositorio original para fusionar sus cambios.

Asegúrese de que su código siga las directrices de estilo del proyecto y esté bien documentado.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE). Consulte el archivo [LICENSE](LICENSE) para obtener más información.
