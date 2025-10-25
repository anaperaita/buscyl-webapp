# Pases de bus

Aplicación web progresiva (PWA) para guardar y acceder fácilmente a tus pases de bus sin necesidad de conexión a internet.

## ¿Qué es esta app?

Una aplicación web simple para guardar tus pases de bus en tu dispositivo. Proyecto personal creado para facilitar el acceso rápido a pases digitales sin depender de conexión a internet.

## Características

- 📱 **Instalable**: Se puede instalar en tu teléfono como una app nativa
- 🔒 **100% Local**: Tus imágenes se guardan solo en tu dispositivo
- 🌐 **Funciona offline**: Una vez instalada, no necesita conexión a internet
- 🎫 **Múltiples pases**: Guarda pases para varias personas (familia, amigos)
- ✏️ **Gestión fácil**: Añade, elimina y reordena tus pases
- 🎨 **Diseño limpio**: Interfaz simple y funcional

## Cómo usar

### Instalación en móvil

1. Abre la aplicación en Chrome desde tu móvil
2. Toca el menú de opciones (⋮)
3. Selecciona "Añadir a pantalla de inicio" o "Instalar aplicación"
4. ¡Listo! Ya tienes la app instalada

### Uso

1. **Primera vez**: Al abrir la app, toca el botón para añadir tu primer pase
2. **Añade tus pases**: Escribe el nombre de la persona y selecciona la imagen del pase
3. **Acceso rápido**: Tus pases estarán siempre disponibles en la pantalla principal
4. **Modo edición**: Abre el menú (☰) y activa "Editar pases" para:
   - Añadir nuevos pases
   - Eliminar pases existentes
   - Reordenar tus pases

## Privacidad y Seguridad

- ✅ Todas las imágenes se guardan **localmente en tu dispositivo**
- ✅ **Nunca se envían** a servidores externos ni a internet
- ✅ No hay seguimiento, cookies ni analíticas
- ✅ Funciona completamente **offline**
- ✅ Tus datos están **solo en tu teléfono**

## Tecnología

- HTML5
- CSS3
- JavaScript (Vanilla, sin frameworks)
- Service Worker para funcionalidad offline
- LocalStorage para almacenamiento local
- PWA (Progressive Web App)

## Desarrollo local

Para ejecutar la aplicación localmente:

```bash
# Clona el repositorio
git clone https://github.com/anaperaita/pases-bus.git

# Entra al directorio
cd pases-bus

# Inicia un servidor local (puedes usar cualquier servidor HTTP)
python3 -m http.server 8000

# Abre en tu navegador
# http://localhost:8000
```

## Estructura del proyecto

```
pases-bus/
├── index.html           # Aplicación principal
├── manifest.json        # Configuración PWA
├── service-worker.js    # Service Worker para offline
├── logo.svg            # Logo de la aplicación
└── README.md           # Este archivo
```

## Contribuir

Si encuentras bugs o tienes sugerencias, siéntete libre de abrir un issue o pull request.

## Licencia

Este proyecto se comparte bajo licencia MIT. Es un proyecto personal sin ánimo de lucro.

## Autora

**Ana Peraita**

- GitHub: [@anaperaita](https://github.com/anaperaita)
- LinkedIn: [Ana Peraita](https://www.linkedin.com/in/aperaita)

---

Hecho con ❤️ para facilitar el acceso a pases de bus digitales
