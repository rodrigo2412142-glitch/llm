# Proyecto 8: LLM
Escribe aquí una breve descripción de tu proyecto
El proyecto propone el desarrollo de un chatbot avanzado de atención al cliente utilizando la API de OpenAI, con el objetivo de automatizar la resolución de consultas y mejorar la experiencia del usuario. Este sistema es capaz de comprender el lenguaje natural, responder preguntas frecuentes, ofrecer recomendaciones de productos y ayudar en la solución de problemas comunes sin intervención humana. Su implementación permitiría a las empresas optimizar sus recursos, reducir tiempos de respuesta y brindar atención continua las 24 horas. Además, al integrarse con bases de datos y sistemas internos, el chatbot puede ofrecer respuestas más personalizadas y precisas. En conjunto, este tipo de solución representa una herramienta clave para modernizar el servicio al cliente, combinando eficiencia operativa con una interacción más fluida y satisfactoria para los usuarios.

Escribe un instructivo de cómo podemos utilizar tu software (incluye instrucciones para crear entorno virtual)

## Instructivo de uso del chatbot de atención al cliente

Este software permite interactuar con un chatbot que responde consultas, recomienda productos y brinda soporte automatizado.

---

## 1. Requisitos previos

* Tener instalado **Python 3.10 o superior**
* Tener acceso a internet
* Contar con una clave de API de OpenAI

---

## 2. Crear entorno virtual

Abre tu terminal y ejecuta:

```bash
python3 -m venv venv
```

---

## 3. Activar entorno virtual

### En Linux / Mac:

```bash
source venv/bin/activate
```

### En Windows:

```bash
venv\Scripts\activate
```

---

## 4. Instalar dependencias

```bash
pip install openai selenium webdriver-manager pandas
```

(el archivo `requirements.txt`):

```bash
pip install -r requirements.txt
```

---

## 🔑 5. Configurar API Key

En Linux/Mac:

```bash
export OPENAI_API_KEY="tu_api_key"
```

En Windows:

```bash
setx OPENAI_API_KEY "tu_api_key"
```

---

## 🚀 6. Ejecutar el chatbot

Ubícate en la carpeta del proyecto y ejecuta:

```bash
python main.py
```

---

## 💬 7. Uso del chatbot

Una vez iniciado:

* Escribe tu consulta en la terminal
* El chatbot responderá automáticamente

Ejemplos:

* “¿Cuál es el clima hoy?”
* “Precio de acciones de Tesla”
* “Recomiéndame un producto”

