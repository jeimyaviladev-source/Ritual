# Ritual
Este es un proyecto personal que quiero compartir, es un programa inspirado en los pomodoros pensado para relajar la mente la ansiedad y ayudar a la concentración tome en cuenta lo que yo necesitaba por experiencia y pensando si realmente esto le ayudaría a las personas, espero que le ayude tanto como a mi!. *no para uso comercial* .

entonces te explico como funciona
## Abrir la app

Abre `index.html` en el navegador. No necesita instalación ni cuenta. YouTube se abre en una pestaña aparte cuando la app está abierta como archivo local. Si sirves la app desde un servidor web local, los reproductores compatibles se muestran dentro del reproductor flotante.

Para usar la ventana Picture-in-Picture propia del navegador, inicia un servidor estático desde esta carpeta, por ejemplo:

```powershell
python -m http.server 8000
```

Después visita `http://localhost:8000`.

## Incluye

- Temporizadores para enfoque, pausa corta y pausa larga, con tiempos configurables.
- Tareas, notas con formato, sonidos ambientales y controles de volumen.
- Ventanas independientes y movibles para tareas, notas, sonidos y progreso; pueden permanecer abiertas a la vez.
- Fondos temáticos, imagen propia y controles de color para el reloj y el texto principal.
- Playlists guardadas de YouTube y Spotify, más audio local durante la sesión.

Los datos se guardan en `localStorage` de este navegador y dispositivo. Los sonidos usan los archivos de `assets/sounds`; sus fuentes y licencias están anotadas en [`assets/sounds/SOURCES.md`](assets/sounds/SOURCES.md). Este proyecto es independiente y no usa recursos, marca ni código de Flocus.

a lo largo del proyecto fui mejorando cosas como la ventana flotante, los sonidos ambientales, el poder agregar tus propias playlist y listas de youtube, las ventanas flotantes son flotantes para poder desplegarlas en cualquier momento sin interferir con el cronometro también pensé en el modo ambiente que te deja solamente el cronometro para ocultar cualquier cosa que podría distraerte, en fin todo esta pensado para los propósito de concentración y disciplina. ya que padecer de TDAH me llevo a buscar causas y soluciones y dichas estrategias que ayudan las implante en este proyecto como la divide las tareas en micro-pasos (la sección de tares), el uso de temporizadores externos (cronómetros), el aumento del estímulo de la tarea como poner música de fondo sin letra y los (sonidos) ambientales, y la anotación de ideas fugaces (notas). decidí agregar mensajes motivacionales, pantalla completa una ventana que almacena tu progreso, y una sección de ajustes donde puedes personalizar la duración del cronometro, estilo del reloj, colores, iconos de sección, volumen en general y fondos. 
