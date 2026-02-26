# Template Academia Clientes - [Asesoría X]

Este proyecto contiene las plantillas HTML, CSS y JS de la "Academia de Clientes" para una asesoría (Autónomos y PYMEs), ofreciendo un diseño web premium, moderno, y responsivo enfocado en la conversión (captura de leads) y la entrega de valor mediante guías y modelos tributarios.

## 🚀 Características Principales

*   **Diseño SaaS Premium:** Interfaz limpia con efectos "Glassmorphism", luces de fondo desenfocadas (Glows), tarjetas flotantes y un aspecto muy pulido que genera una alta confianza y credibilidad.
*   **Aesthetics "Dark Immersive":** Uso inteligente de bloques oscuros inmersivos (ej. sección de asesoramiento) para destacar formularios interactivos (`Floating Labels`).
*   **UI/UX Reactivo:** Animaciones sutiles (micro-interacciones) implementadas en todos los botones, íconos y tarjetas al interactuar con el mouse (`:hover` state).
*   **Totalmente Responsivo (Mobile-First adaptativo):** Todos los Grid layouts colapsan perfectamente en pantallas móviles para garantizar una lectura cómoda sin desbordamiento.
*   **Dependencias Ligeras:** Solamente usa Google Fonts (`Inter`, `Outfit`) y FontAwesome (Version 6+) para íconos. Todo el CSS y JS están construidos en **Vanilla**.

## 📂 Estructura del Proyecto

El proyecto está diseñado pensando en escalabilidad y modularidad a través de diferentes pantallas o "screens".

```text
Template-academia_clientes/
│
├── index.html                 # Pantalla principal o Dashboard (Gateway)
├── style.css                  # Estilos globales y compartidos 
│
└── screens/
    ├── template-guia/         # Plantilla dedicada a Guías de Gestión (Altas, IVA, etc)
    │   ├── index.html
    │   ├── style.css          # Estilos específicos de este template (incluye el de Asesoramiento)
    │   └── script.js
    │
    └── template-modelos/      # Plantilla dedicada a Modelos de AEAT (Renta, 303, 130, etc)
        ├── index.html
        ├── style.css          # Enlazado estilísticamente con los módulos de diseño previos.
        └── script.js
```

## 🎨 Guía de Estilos (Design System en CSS Variables)

La paleta de colores y componentes comunes están configurados en la raíz superior del documento para un control unificado:

*   **Pimary Color (Blanco principal/Acento suave):** `#3b82f6` (Variaciones oscuras para `hover` `#1d4ed8`)
*   **Light Primary:** `rgba(59, 130, 246, 0.1)` 
*   **Secondary/Accent Color:** `#2563eb` y `#0ea5e9` 
*   **Background Base:** `#f8fafc` (Gris Pizarra clarísimo, da aire "SaaS")
*   **Typography:** Principal: `Inter` (cuerpo de texto), Títulos (destacados/números): `Outfit`.

## 🛠️ Cómo Utilizar

1. Es un proyecto de sitios estáticos (`Static Site`). Se puede abrir localmente haciendo doble clic sobre el archivo `index.html` en el navegador de preferencia.
2. Todo el Copy text interno está envuelto con viñetas neutras **`[Asesoría X]`** listas para ser modificadas y buscar-reemplazar por el nombre del negocio final.

## 📢 Componentes Destacados

*   **Floating Labels:** Presente en los campos del formulario (`custom-advice-section`). Al escribir o dar clic, el placeholder del *input* sube estilísticamente. Implementado 100% con CSS `:placeholder-shown` y `:focus`.
*   **Layout Grid Split:** Una distribución asimétrica moderna de dos columnas, en la cual información a la izquierda capta atención, mientras un panel de acción a la derecha permite rellenar datos.
*   **Glow Orbs Backgrounds:** Burbujas difuminadas flotando por detrás del layout en la cabecera (sección "Hero") dando profundidad de ambiente a la página en HTML puro.
