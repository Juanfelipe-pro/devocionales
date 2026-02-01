# Frontend Lista de Espera

## Estructura
```
waitlist-frontend/
├── index.html          # Landing
├── registro/
│   └── index.html      # Formulario
├── logo.png            # ← Agregar tu logo
└── hero.jpg            # ← Agregar tu imagen hero
```

## URLs
- `/` → Landing
- `/registro` → Formulario (sin .html)

## Configuración
En `registro/index.html` línea ~116:
```javascript
const API_URL = 'http://localhost:8000';
const API_KEY = 'tu-api-key';
```

## Uso
```bash
# Con Python
python -m http.server 5500

# Abre http://localhost:5500
```

**IMPORTANTE**: Agrega tus archivos `logo.png` y `hero.jpg` en la carpeta raíz.
