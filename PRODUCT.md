# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users
Voluntarios y encargados de Operación Infancia, con el mismo peso:
- Voluntarios en terreno, en el celular, durante o justo antes de una salida, buscando rápido qué hacer con los NNA.
- Encargados planificando antes de la salida, en computador, armando el programa con calma.

## Product Purpose
Catálogo de las actividades de los manuales de Programas de Operación Infancia. Permite encontrar una actividad (por habilidad socioemocional, tema y tiempo disponible), abrir su ficha (propósito, materiales, desarrollo, tips, reflexión) y ver el programa de la próxima salida. Encontrar una actividad y ver el programa del finde tienen el mismo peso.

## Operating Context
- Salidas de fin de semana (sábado y domingo) con bloques AM/PM, almuerzo y recreo activo 13:00–14:30, reflexión general 15:30–16:00.
- Reglas de oro: respeto, escucha activa, solidaridad.
- Terminología: NNA / NNAJ, núcleos, alianzas, círculo, papelógrafo, Vínculo y Comunidad, Talleres.

## Capabilities and Constraints
- Un solo `index.html` estático, sin build; datos de actividades embebidos en JS.
- Firebase Firestore para calificaciones con estrellas (anónimas por voterId).
- Vistas: Actividades (búsqueda + filtros + grilla), Este finde (por día), Herramientas (técnicas de facilitación, canciones, dinámicas de reflexión).
- La franja/tarjeta de "Próxima salida" solo aparece cuando hay una salida anunciada (FINDE con actividades). Sin salida anunciada, no se muestra y el resto de la pantalla sube; el diseño debe verse completo en ambos casos.
- Modo claro/oscuro con preferencia guardada.
- 6 habilidades socioemocionales con color propio: Trabajo en equipo, Emociones, Empatía, Resiliencia, Autoestima, Convivencia.

## Brand Commitments
- Logo de Operación Infancia (`logo-oi.png`, `icon-oi.png`) debe aparecer siempre.
- Paleta de la marca a mantener de forma similar: ciruela #800061, coral #F83860, amarillo #F8B840, fondo crema.
- Créditos del pie: "Hecho por La Pampilla con cariño para ustedes - Felipe Fesser" y copyright.

## Evidence on Hand
- 84 actividades reales en `index.html`; herramientas del manual en `TOOLS`.
- No hay fotos ni testimonios; no inventarlos.

## Product Principles
- Encontrar algo útil en segundos, en el celular y con una mano.
- La ficha tiene que poder seguirse en terreno: pasos claros, materiales a la vista.
- Cercano y cálido, como el voluntariado; nunca corporativo.
