# Dieta Juli

App personal de seguimiento del plan alimentario — diseñado para funcionar como una PWA instalable en iPhone.

---

## ¿Qué es esto?

Una aplicación web progresiva (PWA) creada a medida para consultar mi plan de alimentación semanal de forma rápida y sin fricciones. El plan viene de mi nutricionista **David Gracia** y está adaptado a mi estilo de vida: trabajo desde casa, cocino solo ciertos días y priorizo la preparación anticipada.

Este proyecto forma parte de un sistema más amplio de organización personal que cubro en cinco áreas: **finanças, nutrição, treinos, estudos e empreendedorismo (Lumo)**.

---

## Funcionalidades

- **Menú semanal** — 7 días con todas las comidas, raciones y gramos exactos
- **Navegación por días** — desliza entre días con flechas
- **Badges por día** — identifica de un vistazo si cocinas hoy o es día pre-preparado
- **Avisos activos** — alertas para confirmar con el nutricionista (bebida de avena, langostinos)
- **Organización** — rutina semanal real: cuándo cocinar, cómo preparar en batch, trucos de pesado
- **Lista de compra** — con checkboxes interactivos, por categoría, ajustada a Mercadona y Gadis Arteixo
- **Funciona offline** — instalable en iPhone desde Safari

---

## Cómo instalar en iPhone

1. Abre **Safari** y ve a: `https://jsazevedoja.github.io/dieta-juli/dieta-juli.html`
2. Toca el icono de compartir (cuadrado con flecha ↑)
3. Selecciona **"Añadir a pantalla de inicio"**
4. Confirma — aparece como app en tu pantalla

---

## Cómo actualizar el contenido

Cuando cambie el plan alimentario o haya ajustes:

1. Ve al repositorio en GitHub: `github.com/jsazevedoja/dieta-juli`
2. Abre el archivo `dieta-juli.html`
3. Haz clic en el **lápiz** para editar
4. Reemplaza el contenido con la nueva versión
5. Haz clic en **"Commit changes"**
6. Espera **1–2 minutos** y el app se actualiza automáticamente

Para ver los cambios en el iPhone: cierra el app completamente (desliza hacia arriba) y vuelve a abrirlo.

---

## Cómo añadir el favicon

1. Crea una imagen **512×512px** (PNG)
2. Súbela al repositorio con el nombre `favicon.png`
3. En el `<head>` del HTML, añade antes de `<title>`:
```html
<link rel="icon" type="image/png" href="favicon.png">
<link rel="apple-touch-icon" href="favicon.png">
```
4. Commit y listo

---

## Estructura del proyecto

```
dieta-juli/
├── dieta-juli.html   # App completa (HTML + CSS + JS en un solo archivo)
├── favicon.png       # Icono del app (pendiente)
└── README.md         # Este archivo
```

---

## Contexto personal

Soy brasileña viviendo en Arteixo, Galicia. Trabajo a tiempo completo de lunes a viernes desde casa. Tengo nutricionista y personal trainer — los planes detallados vienen de ellos, yo me encargo de la ejecución y la organización.

Mi rutina de cocina: **lunes, miércoles y viernes** cocino para mí y para Jesús (comidas). Las cenas las hago yo sola. Los martes, jueves, sábados y domingos como lo preparado con antelación.

Este repositorio es parte de un proyecto más grande llamado **Lumo** — una empresa en construcción con productos digitales SaaS para pequeños negocios, donde los estudios de programación que estoy haciendo desde cero alimentan directamente el desarrollo.

---

## Tecnología

HTML · CSS · JavaScript vanilla — sin frameworks, sin dependencias externas. Un solo archivo que funciona en cualquier navegador y se instala como app nativa en iOS.

---

*Última actualización del plan: julio 2026 — David Gracia (nutricionista)*
