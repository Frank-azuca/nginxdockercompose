# Práctica: servidor web nginx con Docker Compose

Servidor nginx que corre localmente con Docker Compose y sirve un "Hola Mundo" desde el directorio `src`.

## Estructura

```
.
├── docker-compose.yml
└── src/
    └── index.html
```

El directorio `src` se monta como volumen en `/usr/share/nginx/html` dentro del contenedor.

## Uso

```bash
docker compose up -d
```

Abrir http://localhost:8080 en el navegador.

Para detenerlo:

```bash
docker compose down
```
