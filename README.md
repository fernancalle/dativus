# Datívus - Consultoría de Datos e IA

Website para Datívus, una consultora de datos e inteligencia artificial enfocada en el mercado dominicano.

## Descripción

Datívus ofrece servicios de consultoría, desarrollo e integración de soluciones de datos e IA para empresas dominicanas. "Transformamos datos en decisiones."

## Estructura del Proyecto

```
dativus-website/
├── index.html          # Página de inicio
├── servicios.html      # Página de servicios
├── nosotros.html       # Página sobre nosotros
├── contacto.html       # Página de contacto
├── css/
│   └── styles.css      # Estilos personalizados
├── js/
│   └── main.js         # JavaScript funcional
├── assets/
│   ├── images/         # Imágenes del sitio
│   └── icons/          # Iconos SVG
└── README.md           # Este archivo
```

## Tecnologías

- **HTML5** - Estructura semántica y accesible
- **Tailwind CSS** (CDN) - Framework de utilidades CSS
- **Vanilla JavaScript** - Sin dependencias de frameworks
- **Google Fonts** - Tipografía Inter

## Características

- Diseño responsive (mobile-first)
- Navegación fija con menú móvil
- Animaciones sutiles al hacer scroll
- Acordeón para FAQs
- Integración con WhatsApp para contacto
- Optimizado para GitHub Pages

## Colores de Marca

| Color | Hex | Uso |
|-------|-----|-----|
| Navy | `#0f172a` | Color primario, fondos oscuros |
| Cyan | `#06b6d4` | Color de acento, CTAs |
| Slate | `#1e293b` | Texto principal |
| Light | `#f8fafc` | Fondos claros |
| White | `#ffffff` | Fondos, texto sobre oscuro |

## Despliegue en GitHub Pages

1. Crea un repositorio en GitHub (ej: `dativus-website`)

2. Inicializa git y sube el código:
   ```bash
   cd dativus-website
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/dativus-website.git
   git push -u origin main
   ```

3. Configura GitHub Pages:
   - Ve a Settings > Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Guarda los cambios

4. Tu sitio estará disponible en: `https://TU_USUARIO.github.io/dativus-website/`

## Dominio Personalizado (Opcional)

Para usar un dominio personalizado (ej: `dativus.com`):

1. Agrega un archivo `CNAME` en la raíz con tu dominio:
   ```
   dativus.com
   ```

2. Configura los DNS de tu dominio:
   - Tipo A: Apunta a las IPs de GitHub Pages
   - Tipo CNAME: `www` apunta a `TU_USUARIO.github.io`

## Desarrollo Local

Para ver el sitio localmente, puedes usar cualquier servidor HTTP simple:

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (npx)
npx serve
```

Luego abre `http://localhost:8000` en tu navegador.

## Personalización

### Cambiar información de contacto

Busca y reemplaza en todos los archivos HTML:
- WhatsApp: `https://wa.me/18091234567` → Tu número
- Email: `info@dativus.com` → Tu email
- LinkedIn: `https://linkedin.com/company/dativus` → Tu perfil

### Modificar colores

Los colores están definidos en:
1. Tailwind config (inline en cada HTML)
2. CSS custom properties en `css/styles.css`

### Agregar páginas

1. Copia la estructura de cualquier página existente
2. Actualiza el contenido
3. Agrega el link en la navegación de todas las páginas

## Licencia

© 2025 Datívus. Todos los derechos reservados.
