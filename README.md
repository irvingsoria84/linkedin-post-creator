# LinkedIn Post Creator — Agente de IA para tus publicaciones diarias

Un agente de inteligencia artificial que transforma tus ideas desestructuradas en publicaciones de LinkedIn genuinas, humanas y con tu propio estilo de escritura. Completamente automatizado.

---

## ¿Qué hace este agente?

- Aprende cómo escribes tú, no cómo escribe la IA.
- Convierte ideas dictadas o escritas a la rápida en posts listos para publicar.
- Si no tienes idea de qué publicar, te sugiere 5 opciones basadas en tus temas de autoridad.
- Recuerda lo que ya publicaste para no repetirse.
- No usa emojis. No usa guiones largos. No suena a robot.

---

## Requisitos

- [Claude Code](https://claude.ai/code) instalado en tu máquina, **o** acceso a [Antigravity IDE](https://antigravity.dev) (o cualquier entorno que soporte archivos `CLAUDE.md`).
- Una cuenta de Claude con acceso a Claude Sonnet o superior.
- Git instalado (para clonar el repositorio).

---

## Instalación

### Paso 1 — Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/linkedin-post-creator.git
cd linkedin-post-creator
```

### Paso 2 — Abrir en tu entorno agéntico

**Opción A: Claude Code**

```bash
claude
```

**Opción B: Antigravity IDE**

Abre la carpeta del proyecto desde Antigravity como harías con cualquier proyecto de código.

### Paso 3 — Eso es todo

La primera vez que envíes un mensaje, el agente detectará que el proyecto no está configurado y te guiará paso a paso a través de una breve entrevista inicial. Responde las preguntas y el agente se encargará de todo lo demás de manera automática.

---

## Cómo usarlo en el día a día

Una vez configurado, el agente funciona en dos modos:

### Tengo una idea para publicar hoy

Escríbela o dicta lo que quieres decir, sin importar si está ordenada o no:

> "Hoy me pasó algo con un cliente que me hizo pensar en cómo manejamos las expectativas desde el principio..."

El agente la estructurará en un post listo para copiar y pegar, con tu voz y tu estilo.

### No sé qué publicar hoy

Dile al agente:

> "No sé qué publicar hoy, dame ideas."

El agente leerá tus rubros de autoridad y tu historial de posts, y te sugerirá 5 ideas concretas y frescas para elegir.

---

## Estructura del Proyecto

```
linkedin-post-creator/
├── CLAUDE.md                  # Instrucciones del agente (el cerebro del sistema)
├── banco_temas.md             # Tus rubros de autoridad e historial de publicaciones
├── biblioteca_estilo.md       # Tu análisis de estilo y textos de ejemplo
├── ejemplo_publicacion.md     # Referencia de calidad para el agente
└── README.md                  # Esta guía
```

> Los archivos `banco_temas.md` y `biblioteca_estilo.md` son gestionados automáticamente por el agente. No necesitas editarlos manualmente.

---

## Personalización avanzada

Si en algún momento quieres actualizar tus preferencias (cambiar tono, agregar nuevos rubros, actualizar tus textos de ejemplo), simplemente díselo al agente con lenguaje natural:

> "Quiero agregar 'productividad personal' a mis temas."
> "Cambia mi tono a más casual."
> "Agrega este texto como nuevo ejemplo de estilo: [tu texto]"

El agente actualizará los archivos correspondientes de forma automática.

---

## Frecuencia recomendada

- Puedes usarlo todos los días, 3 veces por semana, o cuando quieras.
- Si usas Claude Code, puedes configurar una tarea programada en tu sistema operativo para que el agente te recuerde publicar cada mañana.

---

## Licencia

MIT — Úsalo, adáptalo y compártelo libremente.
