# Mi Cuerpo, Mis Emociones - Web Version

Aplicación web educativa interactiva para niños sobre emociones, espacio personal y autocuidado.

🌐 **[Ver Demo en Vivo](#)** _(Actualiza este enlace después de publicar)_

## 🎯 Características

- 🎮 **Módulos Interactivos**: 5 módulos educativos progresivos
- 🚦 **Semáforo de Emociones**: Aprende a identificar y manejar emociones
- 😊 **Reconocimiento de Emociones**: Identifica cómo te sientes
- 🤗 **Espacio Personal**: Aprende sobre límites personales
- 👨‍👩‍👧 **Personas de Confianza**: Identifica adultos de confianza
- 🔊 **Audio Interactivo**: Síntesis de voz en español
- 📱 **Diseño Responsivo**: Funciona en PC, tablet y móvil

## 🚀 Despliegue en GitHub Pages

Esta aplicación está lista para ser publicada en GitHub Pages. Sigue estos pasos:

### 1. Crear Repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Haz clic en el botón **"New"** (nuevo repositorio)
3. Nombre sugerido: `mi-cuerpo-mis-emociones`
4. Marca como **público**
5. **NO** inicialices con README (ya tienes uno)
6. Haz clic en **"Create repository"**

### 2. Subir el Código

Copia y pega estos comandos en tu terminal (PowerShell):

```powershell
git init
git add .
git commit -m "Initial commit: Mi Cuerpo, Mis Emociones web app"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/mi-cuerpo-mis-emociones.git
git push -u origin main
```

> **Nota**: Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub

### 3. Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Haz clic en **Settings** (Configuración)
3. En el menú lateral, haz clic en **Pages**
4. En **Source**, selecciona **main** branch
5. Haz clic en **Save**
6. Espera 1-2 minutos y tu sitio estará en: `https://TU_USUARIO.github.io/mi-cuerpo-mis-emociones/`

## 💻 Desarrollo Local

Si quieres probar la aplicación localmente antes de publicarla:

### Opción 1: Python (Recomendado)

```powershell
python -m http.server 8000
```

Luego abre: `http://localhost:8000`

### Opción 2: Node.js

```powershell
npx http-server -p 8000
```

Luego abre: `http://localhost:8000`

> **⚠️ Importante**: No abras el archivo `index.html` directamente. El audio solo funciona cuando se sirve a través de HTTP.

## 🛠️ Tecnologías

- HTML5
- CSS3 (con media queries para responsive design)
- JavaScript Vanilla
- Web Speech API (síntesis de voz)
- Web Audio API (efectos de sonido)

## 📂 Estructura del Proyecto

```
web-version_micmir/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos y responsive design
├── js/
│   ├── app.js         # Inicialización de la aplicación
│   ├── audio.js       # Gestión de audio
│   ├── modules.js     # Lógica de módulos educativos
│   └── navigation.js  # Sistema de navegación
├── assets/
│   └── images/        # Recursos multimedia
└── README.md          # Este archivo
```

## 📱 Compatibilidad

- ✅ Chrome/Edge (Recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Dispositivos móviles (iOS/Android)

## 📄 Licencia

MIT License - Siéntete libre de usar y modificar este proyecto.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o pull request.

---

Hecho con ❤️ para la educación infantil

