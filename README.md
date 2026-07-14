# 🎓 Orienta — Test Vocacional

Ayudando a jóvenes a encontrar su camino desde 2026.

## 📋 Descripción del proyecto

Orienta es una plataforma web gratuita que ayuda a estudiantes secundarios y jóvenes a descubrir qué carrera universitaria se adapta mejor a sus intereses, habilidades y estilo de vida, a través de un test vocacional interactivo.

## ❓ Problemática que abordamos

Muchos adolescentes llegan al final del secundario sin saber qué estudiar. La falta de orientación vocacional clara genera:

- Incertidumbre y ansiedad frente a la elección de carrera.
- Abandono universitario por elegir una carrera que no era la indicada.
- Jóvenes que quedan "estancados" sin animarse a comenzar una carrera.

> "Estar por terminar el colegio y no saber qué estudiar es una experiencia muy común — y muy solitaria."

## 🌍 Relación con los Objetivos de Desarrollo Sostenible (ODS)

Este proyecto se enmarca principalmente en:

| ODS | Descripción |
|---|---|
| **ODS 4 — Educación de calidad** | Brindamos orientación educativa gratuita y accesible para que más jóvenes puedan tomar decisiones informadas sobre su futuro académico. |
| **ODS 10 — Reducción de las desigualdades** | Al ser 100% gratuita, la herramienta democratiza el acceso a la orientación vocacional, que muchas veces solo está disponible en colegios privados o con costo. |
| **ODS 8 — Trabajo decente y crecimiento económico** | Ayudamos a los jóvenes a conectar con carreras y oportunidades laborales que se alineen con sus fortalezas. |

## 💡 Solución tecnológica

Orienta es un sitio web one-page desarrollado con HTML, CSS y JavaScript puro, sin necesidad de registro ni instalación. La solución incluye:

### ✅ Funcionalidades clave

- **Así funciona** — Explicación en 3 pasos (Respondé el test → Recibí tu perfil → Explorá opciones) que guía al usuario antes de empezar.
- **Test vocacional interactivo** — 20 preguntas sobre gustos, habilidades y estilo de vida. Al finalizar, el sistema calcula un perfil de afinidad por áreas (Salud, Tecnología, Arte, Ciencias, Humanidades, Negocios, Ingeniería, Ciencias Sociales) y recomienda carreras personalizadas.
- **Explorador de carreras** — Carreras con descripción detallada, duración, materias principales, habilidades requeridas y salidas laborales. Filtrable por área de interés.
- **Directorio de universidades** — Instituciones destacadas de América Latina con links directos a sus sitios oficiales, buscable por nombre, país o carrera.
- **Temporizador Pomodoro** — Bloques de 25 minutos de foco y 5 de descanso, con aviso sonoro y notificación al cambiar de fase, pensado para usar mientras se estudia o se exploran carreras.
- **Inicio de sesión** — Formulario de acceso con recuperación de contraseña (simulado, sin backend conectado por ahora).
- **Formulario de contacto** — Para que los usuarios puedan dejar dudas, sugerencias o comentarios sobre su experiencia con Orienta.

## 🛠️ Tecnologías utilizadas

- **HTML5** — estructura semántica del sitio
- **CSS3** — diseño responsivo con variables de color, animaciones y layout con Grid y Flexbox
- **JavaScript (Vanilla)** — lógica del test, cálculo de resultados, filtros, búsqueda dinámica y temporizador Pomodoro

### 🔒 Cero dependencias externas

El sitio **no** usa CDNs, Google Fonts ni ningún recurso externo: todo el HTML, CSS y JS es autocontenido y las tipografías son fuentes ya instaladas en el sistema operativo (Georgia, system-ui, etc). Esto significa que:

- Funciona sin conexión a internet.
- No se rompe si un CDN externo está caído o bloqueado (por ejemplo, en una red de colegio).
- Abre igual de rápido y sin errores tanto en GitHub Pages como abriendo `index.html` con doble clic desde la compu.

## 👥 Público objetivo

- Adolescentes cursando los últimos años del secundario
- Jóvenes que ya terminaron el secundario pero aún no eligieron carrera
- Estudiantes que comenzaron una carrera y están pensando en cambiar

## 📁 Estructura del proyecto

```
proyecto/
├── index.html       # Estructura principal del sitio
├── style.css        # Estilos y diseño visual
└── script.js        # Lógica del test y contenido dinámico
```

## 🚀 Cómo usar el proyecto

1. Clonar o descargar el repositorio
2. Abrir `index.html` en cualquier navegador (doble clic alcanza)
3. ¡Listo! No requiere servidor, internet ni dependencias externas

> ⚠️ Importante: los tres archivos (`index.html`, `style.css`, `script.js`) deben estar en la misma carpeta y conservar esos nombres exactos, ya que `index.html` los referencia por ruta relativa.

## ✅ Cómo comprobar que todo funciona

1. **Revisar errores en consola:** abrí `index.html`, presioná `F12` (o clic derecho → Inspeccionar) y andá a la pestaña **Console**. No debería aparecer ningún texto en rojo. Si aparece algo, copiá el mensaje exacto: te va a decir en qué línea y archivo está el problema.
2. **Probar el test de punta a punta:** hacé clic en "Hacer el test gratuito", respondé las 20 preguntas y confirmá que al final aparezcan los resultados con las barras de afinidad y las carreras recomendadas.
3. **Probar carreras:** entrá a la sección "Carreras", probá los filtros por área y hacé clic en una tarjeta para ver el modal de detalle.
4. **Probar universidades:** buscá por nombre, país o carrera en el buscador y confirmá que filtre en tiempo real.
5. **Probar Pomodoro:** iniciá el temporizador y confirmá que el reloj corra.
6. **Probar sin internet:** desconectá el wifi/datos y volvé a abrir `index.html`. Si todo lo anterior sigue funcionando igual, confirma que no hay dependencias externas rotas.
7. **Publicar en GitHub Pages** (opcional, para ver la versión "online"): en el repo andá a *Settings → Pages*, elegí la rama y la carpeta donde están los archivos, guardá, y GitHub te va a dar una URL pública (`https://usuario.github.io/repo/`) para compartir.

## 👩‍💻 Equipo

Grupo 11 — Área Educación
Proyecto desarrollado en el marco del programa Chicas en Tecnología (CET) — Programación Asistida con IA 2026

Hecho con ♥ para estudiantes de toda América Latina.
