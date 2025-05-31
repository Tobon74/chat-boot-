# 🛠️ TechGadget Support Chatbot

Este es un chatbot interactivo creado en Python para brindar atención al cliente simulada, utilizando `ipywidgets` dentro de Jupyter Notebook. Diseñado como una interfaz de soporte para una tienda ficticia llamada **TechGadget**, responde preguntas comunes como envíos, devoluciones o fallas técnicas.

## 📦 Características

- Interfaz visual con botones e input interactivo.
- Respuestas basadas en coincidencias de palabras clave.
- Botones rápidos para preguntas frecuentes.
- Compatible con Jupyter Notebook y Google Colab.
- Ideal para proyectos educativos, demostraciones de prototipos o MVPs.

## 🎯 ¿Para qué sirve?

Este chatbot permite simular una atención básica al cliente sin conexión a una base de datos ni uso de inteligencia artificial avanzada. Puede ser base para:

- Prototipos de asistentes virtuales.
- Demostraciones de UI en notebooks.
- Prácticas de lógica conversacional simple.

## 🧩 Tecnologías utilizadas

- Python 3.x
- [ipywidgets](https://ipywidgets.readthedocs.io/)
- IPython Display

## 📸 Captura de pantalla

![chatbot_preview](ruta/a/tu/imagen.png) <!-- Puedes subir una captura al repo y actualizar la ruta -->

## 🚀 Instalación

Asegúrate de tener `ipywidgets` instalado:

```bash
pip install ipywidgets

✏️ Código principal
El bot se basa en un diccionario de palabras clave y respuestas. Por ejemplo:

python
Copiar
Editar
responses = {
    "hi": "Hello! Welcome to TechGadget Support...",
    "return policy": "You can return products within 30 days...",
    ...
}
🛠️ Posibles mejoras
Añadir procesamiento de lenguaje natural (NLTK, spaCy, Transformers).

Conexión a una API o base de datos real.

Exportar conversación.

Versiones web usando Streamlit o Gradio.

📄 Licencia
Este proyecto está bajo la Licencia MIT. Puedes usarlo, modificarlo y compartirlo libremente.
