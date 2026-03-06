# ghibli-in

Capa de infraestructura local del proyecto Studio Ghibli
Orquesta los servicios de frontend y backend usando Docker Compose.

## Tecnologías
- Docker
- Docker Compose

## Variables de entorno
```env
GHIBLI_API_URL=https://ghibliapi.vercel.app
```

## Cómo correrlo
Requiere tener Docker Desktop instalado.
```bash
docker-compose up --build
```

- Frontend: http://localhost:3000
- Backend: http://localhost:3001
