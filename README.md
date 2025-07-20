# E.V.A - Backend

Este es el backend en Flask para la IA compañera E.V.A. Permite conectarse con la API de OpenAI (GPT-4) y responder desde el frontend.

## Cómo usar

1. Instala las dependencias:
```bash
pip install -r requirements.txt
```

2. Crea un archivo `.env` con tu API key:
```
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

3. Ejecuta localmente:
```bash
python app.py
```

## Para Render

- Usa `gunicorn app:app` como comando de inicio.
- Agrega la variable de entorno `OPENAI_API_KEY`.

Este backend está listo para ser conectado al frontend de E.V.A.
