# Portafolio

**Portafolio personal / Landing** 🎨

Este repositorio contiene mi portafolio personal (landing) construido con HTML y Tailwind CSS. Aquí encontrarás instrucciones para instalar dependencias, ejecutar el flujo de desarrollo de CSS con Tailwind CLI, y preparar los archivos para despliegue.

---

## 🛠️ Tecnologías

- HTML
- CSS
- Tailwind CSS (v4)
- pnpm (recomendado)
- Tailwind CLI

## 🚀 Empezar (rápido)

Requisitos: Node.js y pnpm instalados.

1. Instalar dependencias:

```bash
pnpm install
```

2. Desarrollo (reconstruye CSS automáticamente):

```bash
pnpm run dev:css
```

3. Construir CSS para producción:

```bash
pnpm run build:css
```

4. Previsualizar: abre `index.html` en tu navegador o usa un servidor estático, por ejemplo:

```bash
npx serve .
# o
python -m http.server 8080
```

## 🔧 Estructura del proyecto

- `index.html` — Página principal del portafolio
- `styles/` — Archivos de Tailwind: `input.css` (fuente) y `output.css` (generado/minificado)
- `assets/` — Imágenes y recursos
- `src/` — (opcional) código fuente si aplica

## 🧩 Desarrollo y notas

- Edita los estilos en `styles/input.css`. El script `dev:css` hace watch y regenera `styles/output.css` automáticamente.
- El proyecto está preparado como una página estática; para desplegar, construye el CSS y sube los archivos estáticos al hosting de tu preferencia (Netlify, GitHub Pages, Vercel, etc.).

## ✉️ Contacto

El formulario de contacto está configurado usando Formspree (revisar `index.html`).

## 🤝 Contribuciones

Si quieres contribuir, abre un issue o PR. Cualquier mejora en contenido, accesibilidad o rendimiento es bienvenida.

https://roadmap.sh/projects/portfolio-website


¡Gracias por visitar mi portafolio! 💡
