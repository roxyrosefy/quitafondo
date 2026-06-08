# QuitaFondo AI

Removedor de fondos preciso con IA que funciona 100% en el navegador (client-side).

## Características

- **Preciso como PhotoRoom**: Usa el modelo de segmentación de @imgly/background-removal (basado en ONNX + WebAssembly)
- **Privacidad total**: Tu imagen nunca sale de tu dispositivo
- **Sin límites ni registro**
- **Múltiples formatos de descarga**: PNG transparente, JPG con fondo blanco/negro o color personalizado
- **Diseño moderno oscuro** optimizado para creadores de contenido

## Cómo usarlo

### Opción 1: Abrir localmente (prueba rápida)
1. Abre el archivo `index.html` directamente en Chrome, Edge o Firefox.
2. ¡Listo!

### Opción 2: Desplegar en GitHub Pages (recomendado)
1. Ve a Settings → Pages
2. Source: Deploy from a branch → Branch: `main` / Root
3. Tu herramienta estará disponible en:
   `https://roxyrosefy.github.io/quitafondo`

### Opción 3: Desplegar en Vercel (gratis y rápido)
1. Importa este repo en Vercel
2. Despliegue automático en segundos

## Notas técnicas

- La primera vez que uses la herramienta, se descargará el modelo de IA (~35-50 MB). Queda en caché del navegador.
- Funciona mejor en Chrome / Edge (mejor soporte WebGPU y WebAssembly).
- Para imágenes muy grandes (> 4000px) puede tardar más o necesitar más memoria.

## Personalización futura (posibles mejoras)

- Procesamiento por lotes (varias imágenes a la vez)
- Ajuste fino de bordes / refinamiento
- Integración con tu flujo de Roxyrose (botón "Quitar fondo" en el generador)
- Soporte para video / frames
- Opción de recorte automático + sombras como PhotoRoom

¿Quieres que añada alguna de estas funciones o que integre esta herramienta en tu sitio de Roxyrose?

Creado para Jose Andres • 2026