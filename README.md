# TravelApp

Planifica itinerarios día a día, guarda tus vuelos y tours, y descubre los viajes de otras personas cerca de ti.

## Qué es

TravelApp es una aplicación web de una sola página (`travelapp.html`) para organizar viajes:

- **Itinerario día a día**, en vista de lista o de calendario, con título y color personalizados por día.
- **Vuelos**: aerolínea, número de vuelo, horarios, escalas, número de reserva y estado (a tiempo, retrasado, cancelado...), con autorrelleno a partir de una foto de la reserva.
- **Tours y actividades de varios días**: se reparten solos por todos los días que duran.
- **Imagen de fondo** por viaje.
- **Mis viajes** y **Explorar**: guarda tus viajes y descubre los que ha compartido otra gente cerca de ti.

## Cómo funciona

Es una única página HTML autocontenida (HTML, CSS y JavaScript en un solo archivo, sin build ni dependencias de servidor). Los datos se guardan mediante las capacidades en tiempo de ejecución de [Claude Artifacts](https://claude.ai) (`db`, `user`, `assets`, `sample`): al abrirse dentro de claude.ai, la app guarda y sincroniza los viajes en tiempo real entre quienes lo vean; abierta fuera de ese entorno, funciona en modo demo local con datos de ejemplo.

## Uso

Abre `travelapp.html` publicado como Artifact en [claude.ai](https://claude.ai) (por ejemplo desde la galería en `claude.ai/code/artifacts`) para tener la app completa con guardado y colaboración en tiempo real.
