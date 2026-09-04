# Portafolio | Juan Sebastián Domínguez 💼

Portafolio profesional que presenta mi experiencia, proyectos y habilidades como desarrollador. Diseñado con un enfoque moderno, animado y totalmente responsive.

🔗 **Demo en vivo:** https://jsebased-png.github.io/Portafolio_JuanDominguez/

## ✨ Características

- Hero con efecto typewriter animado.
- Fondo interactivo con partículas y gradientes animados en Canvas/CSS.
- Sección "Sobre mí" con foto de perfil y datos clave.
- Tarjetas de proyectos con efecto flip 3D (frente/reverso) al pasar el mouse.
- Sección de skills con efecto tilt 3D.
- Formulario de contacto funcional (envío vía `mailto`).
- Animaciones de scroll reveal al desplazarse por la página.
- Menú responsive con botón hamburguesa para móvil.
- Micro-interacciones tipo "magnetic" en botones y enlaces.

## 🛠️ Tecnologías

- HTML5
- CSS3 (animaciones, gradientes, `backdrop-filter`, diseño responsive)
- JavaScript (Vanilla — Canvas API, Intersection Observer)
- Google Fonts (Poppins)

## 📁 Estructura del proyecto

```
Portafolio_JuanDominguez/
├── index.html      # Estructura principal: hero, sobre mí, proyectos, skills, contacto
├── script.js       # Typewriter, partículas, scroll reveal, tilt 3D, formulario
├── styles.css      # Estilos, animaciones y diseño responsive
├── photos/         # Imágenes de perfil y previews de proyectos
├── TODO.md         # Pendientes y mejoras planeadas
└── README.md
```

## 📂 Proyectos incluidos

| Proyecto | Descripción | Enlace |
|---|---|---|
| **Pokédex App (PokéDomin)** | Exploración de Pokémon consumiendo la PokeAPI, con búsqueda y estadísticas | [Ver proyecto](https://jsebased-png.github.io/pokedomin/) |
| **Shopping Cart** | Carrito de compras con manejo de estado y totales dinámicos | GitHub |
| **DeliveryBot (Sofía)** | Bot conversacional en n8n + Telegram para gestión de pedidos | [Ver repositorio](https://github.com/jsebased-png/Proyecto_DeliveryBot_JuanDominguez) |

## 🚀 Cómo montarlo (instalación local)

Proyecto 100% estático, sin dependencias ni build.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/jsebased-png/Portafolio_JuanDominguez.git
   cd Portafolio_JuanDominguez
   ```
2. Ábrelo directamente en el navegador, o sirve la carpeta con un servidor local:
   ```bash
   python3 -m http.server 5500
   ```
3. Visita `http://localhost:5500`.

## 🌐 Despliegue (GitHub Pages)

1. Ve a **Settings → Pages** en el repositorio.
2. Selecciona el branch `main` y la carpeta `/root`.
3. Guarda: el sitio quedará publicado en `https://jsebased-png.github.io/Portafolio_JuanDominguez/`.

## 📝 Convención de commits

Este proyecto sigue **Conventional Commits**:

| Tipo | Uso |
|------|-----|
| `feat` | Nueva funcionalidad o sección |
| `fix` | Corrección de un bug o error visual |
| `style` | Cambios de estilos/formato (CSS) |
| `refactor` | Cambios de código sin alterar funcionalidad |
| `docs` | Cambios en documentación (README, TODO) |
| `chore` | Mantenimiento general |

**Ejemplos:**
```
feat: agregar proyecto DeliveryBot al portafolio
fix: corregir enlace roto en tarjeta de proyecto
style: ajustar espaciado del grid de skills
docs: actualizar README con nuevos proyectos
```

## 📬 Contacto

- GitHub: [@jsebased-png](https://github.com/jsebased-png)
- LinkedIn: agrega aquí tu enlace
- Correo: agrega aquí tu correo de contacto

## 📄 Licencia

Proyecto de uso personal/portafolio.
