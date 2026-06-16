# LinkedIn Post Creator — Agente de IA para tus publicaciones diarias

Un agente de inteligencia artificial que transforma tus ideas desestructuradas en publicaciones de LinkedIn genuinas, humanas y con tu propio estilo de escritura. Sin emojis. Sin guiones. Sin sonar a robot.

---

## ¿Qué hace este agente?

- Aprende cómo escribes tú, no cómo escribe la IA.
- Convierte ideas dictadas o escritas a la rápida en posts listos para publicar.
- Si no tienes idea de qué publicar, te sugiere 5 opciones basadas en tus temas de autoridad.
- Recuerda lo que ya publicaste para no repetirse.
- Guarda todo automáticamente en los archivos del proyecto. No necesitas tocar nada.

---

## Cómo funciona

Este agente **no es una aplicación web ni un dashboard**. Funciona directamente dentro de un chat de IA, igual que si le estuvieras escribiendo a un asistente.

Una vez que abres el repositorio en tu entorno, simplemente escribes en el chat y el agente responde. Todo ocurre en esa conversación. El agente tiene acceso únicamente a los archivos dentro de la carpeta del repositorio, nada más de tu computadora.

---

## Requisitos

- [Claude Code](https://claude.ai/code) instalado en tu máquina, **o** acceso a [Antigravity IDE](https://antigravity.dev) (o cualquier entorno compatible con `CLAUDE.md`).
- Una cuenta de Claude con acceso a Claude Sonnet o superior.
- Git instalado en tu computadora.

---

## Instalación

### Paso 1 — Clonar el repositorio

Abre tu terminal y ejecuta:

```bash
git clone https://github.com/irvingsoria84/linkedin-post-creator.git
cd linkedin-post-creator
```

Esto crea una carpeta llamada `linkedin-post-creator` con todos los archivos del agente.

### Paso 2 — Abrir en tu entorno

**Opción A: Claude Code (en terminal)**

Dentro de la carpeta del proyecto, ejecuta:

```bash
claude
```

Esto abre el chat de Claude Code directamente en tu terminal. Verás un prompt donde puedes escribirle al agente. Escribe tu primer mensaje para comenzar.

> Si ves los archivos listados antes de escribir, eso es normal. El agente entra en acción en cuanto envías tu primer mensaje.

**Opción B: Antigravity IDE**

1. Abre Antigravity IDE.
2. Ve a "Abrir carpeta" y selecciona la carpeta `linkedin-post-creator` que clonaste.
3. Escribe tu primer mensaje en el chat de Antigravity.

El agente leerá el archivo `CLAUDE.md` automáticamente y tomará el control desde ahí.

**Opción C: Claude Projects (Claude.ai)**

1. Entra a [claude.ai](https://claude.ai) y crea un nuevo Project.
2. En la sección de instrucciones del Project, pega todo el contenido del archivo `CLAUDE.md`.
3. Sube los archivos `banco_temas.md`, `biblioteca_estilo.md` y `ejemplo_publicacion.md` como archivos del Project.
4. Escribe tu primer mensaje en el chat del Project.

> En esta opción, el agente no puede editar los archivos automáticamente. Te indicará qué actualizar cuando sea necesario.

### Paso 3 — Eso es todo

La primera vez que envíes un mensaje, el agente detectará que el proyecto no está configurado y te guiará paso a paso a través de una breve entrevista inicial. Responde las preguntas y el agente se encargará del resto.

---

## Cómo usarlo en el día a día

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

Los archivos `banco_temas.md` y `biblioteca_estilo.md` son gestionados automáticamente por el agente cuando lo usas en Claude Code o Antigravity. No necesitas editarlos manualmente.

---

## Personalización avanzada

Si en algún momento quieres actualizar tus preferencias, simplemente díselo al agente con lenguaje natural:

> "Quiero agregar 'productividad personal' a mis temas."
> "Cambia mi tono a más casual."
> "Agrega este texto como nuevo ejemplo de estilo: [tu texto]"

El agente actualizará los archivos correspondientes de forma automática.

---

## Preguntas frecuentes

**¿El agente puede ver otros archivos de mi computadora?**
No. Cuando usas Claude Code o Antigravity, el agente solo tiene acceso a los archivos dentro de la carpeta del repositorio que abriste. No puede leer ni acceder a nada fuera de esa carpeta.

**¿Puedo usarlo en varios dispositivos?**
Sí. Como los datos se guardan en archivos dentro del repositorio, puedes hacer `git pull` en otro dispositivo y tendrás todo tu historial y configuración disponible.

**¿Qué pasa si abro la carpeta y veo los archivos en vez de un chat?**
Eso es el explorador de archivos del entorno, no el agente. El agente entra en acción cuando abres el chat y escribes tu primer mensaje. En Claude Code, eso ocurre al ejecutar `claude` en la terminal.

---

## Licencia

MIT — Úsalo, adáptalo y compártelo libremente.
