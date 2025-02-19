# O1234 Backend API

Backend API para el sistema de documentación O1234, construido con FastAPI y OpenAI.

## Tecnologías

- FastAPI
- OpenAI GPT-3.5
- Python 3.12
- Docker

## Desarrollo Local

1. Instalar dependencias:
```bash
pip install -r requirements.txt
```

2. Configurar variable de entorno:
```bash
export OPENAI_API_KEY="tu-api-key"
```

3. Iniciar servidor:
```bash
uvicorn main:app --reload --port 8080
```

## Endpoints

- `POST /api/ask`: Endpoint principal para preguntas sobre O1234

## Despliegue

La API está configurada para desplegarse en fly.io
