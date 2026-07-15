# MiPesca — Posts para Instagram

Imágenes en `landing/social/posts/` (1080×1350, formato feed 4:5).
Para regenerarlas tras editar `posts-src.html`:
`node scripts/render-posts-instagram.mjs` (desde `pescaespana-api/`).

Orden de publicación sugerido: Post 1 (lanzamiento) → Post 2 a los 2-3 días →
Post 4 → Post 3 → Post 5 cada jueves/viernes como cita semanal.

---

## Post 1 · Presentación (carrusel: post1-1 a post1-5)

**Caption:**

¿Cuántas veces has ido a pescar "a ver si hay suerte"? 🎣

La suerte se puede calcular. MiPesca junta la teoría solunar, la meteo y
las mareas de tu spot en una sola puntuación de 0 a 100, hora a hora.

Y además:
📍 Mapa en vivo estilo Waze: mira quién está pescando ahora
📓 Diario de capturas con fotos
🐟 Pokédex con 70 especies por desbloquear
🏆 Rangos y logros: de Grumete a Leyenda del mar

Gratis, sin descargas, en tu navegador → link en la bio.

¿Tú de qué pescas: orilla, roca o barco? Te leo en comentarios 👇

**Hashtags:**
#pesca #pescaespaña #pescadeportiva #surfcasting #spinning #pescadesdeorilla #pescaenelmar #solunar #mareas #pescadores #pescando #appdepesca #lubina #dorada #sargo #pescasostenible

---

## Post 2 · Educativo: los 3 momentos en que pican más (carrusel: post2-1 a post2-5)

**Caption:**

Guarda este post para tu próxima salida 📌

Los peces no pican igual todo el día. Hay 3 momentos que concentran la
mayor parte de la actividad:

1️⃣ Amanecer y atardecer — los depredadores cazan con poca luz
2️⃣ Periodos solunares mayores — luna en el cenit o el nadir, ~2 h de actividad
3️⃣ Cambios de marea — el agua en movimiento arrastra comida

¿Demasiado que mirar? MiPesca lo calcula por ti y te lo da en una
puntuación de 0 a 100 para tu spot. Gratis → link en la bio.

¿Cuál es tu hora fetiche para pescar? 👇

**Hashtags:**
#pesca #consejosdepesca #pescaespaña #teoriasolunar #solunar #mareas #pleamar #pescadeportiva #surfcasting #spinning #pescadesdeorilla #amanecer #pescaenelmar #trucosdepesca #pescadores

---

## Post 3 · Pokédex y niveles (carrusel: post3-1 a post3-3)

**Caption:**

¿Te acuerdas de tu primera lubina? Tu Pokédex sí. 🐟

En MiPesca cada captura desbloquea la ficha de su especie: 70 especies
de nuestras costas y ríos esperándote, con sus avisos de especies
venenosas y protegidas incluidos.

Y mientras completas la colección, subes de rango: 7 niveles desde
Grumete hasta Leyenda del mar y 16 logros por el camino. 🏆

Pescar ahora tiene partida guardada. Gratis → link en la bio.

¿Cuántas especies distintas crees que llevas? Di un número sin mirar 👇

**Hashtags:**
#pesca #pescaespaña #pokedex #pescadeportiva #capturas #lubina #dorada #sargo #pescaresponsable #catchandrelease #pescadores #appdepesca #gamificacion #pescaenelmar

---

## Post 4 · Mapa en vivo + chat de playa (carrusel: post4-1 a post4-3)

**Caption:**

Waze te dice dónde hay radar. MiPesca te dice dónde están pescando. 🗺️

Mapa en tiempo real con la gente que está en el agua ahora mismo, tus
spots guardados y avisos de zona. Y cada playa tiene su chat: qué está
entrando, con qué cebo, cómo está el mar — directamente de quien lo
está viendo.

Los mensajes se borran solos a las 12 h: lo que pasa en la playa, se
queda en la playa. 🤫

Gratis, sin descargas → link en la bio.

Etiqueta a tu compañero de pesca, ese que siempre llega tarde 👇

**Hashtags:**
#pesca #pescaespaña #mapadepesca #spotsdepesca #pescadeportiva #surfcasting #spinning #comunidaddepesca #pescadesdeorilla #chatdepesca #pescadores #appdepesca #pescaenelmar

---

## Post 5 · Pronóstico del finde (plantilla semanal: post5-pronostico-finde)

Editar cada semana en `posts-src.html` (lugar, puntuación, etiqueta y
filas de horas — sección marcada como EDITABLE) y re-renderizar.
Publicar jueves por la tarde o viernes por la mañana.

**Caption (plantilla):**

PRONÓSTICO DEL FINDE 🗓️ 📍 [Zona]

La puntuación de MiPesca para [spot] este fin de semana: [XX]/100 —
[etiqueta]. Las mejores ventanas:

🌅 Sábado [hh:mm–hh:mm] → [motivo]
🌇 Sábado [hh:mm–hh:mm] → [motivo]
🌊 Domingo [hh:mm–hh:mm] → [motivo]

¿Tu spot no es este? Mira el tuyo hora a hora en pescando.es → link en
la bio. Gratis.

¿Quién sale este finde? 👇

**Hashtags:**
#pesca #pescaespaña #pronosticodepesca #solunar #mareas #findesemana #pescadeportiva #surfcasting #spinning #cadiz #pescaenelmar #pescadores
(cambiar el hashtag de provincia según la zona)

---

## Notas

- Formato 4:5 (1080×1350): ocupa el máximo espacio en el feed.
- Primera línea del caption = gancho (es lo único visible sin pulsar "más").
- Todas las capturas de pantalla son reales de la app (las de `landing/img/`).
- Los CTA dicen "link en la bio": poner https://mipesca.vercel.app/ (o
  pescando.es cuando esté el dominio) en la bio del perfil.
- Responder a todos los comentarios la primera hora mejora el alcance.
