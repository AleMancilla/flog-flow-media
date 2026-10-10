# Sesión FlogFlow — IMDUMB

Paquete generado por el visor de FlogFlow para analizar la sesión con IA.
Cómo leerlo: t = segundos desde el inicio de la sesión · [#n] = request con detalle en «Red» · [img: …] = captura incluida en screens/ · NOTA = nota de quien revisó la sesión sobre la acción anterior · APP, CONN, KBD y JANK = segundo plano, conexión, teclado y frames lentos · INPUT = edición de un campo (lo escrito no se guarda).

- App: IMDUMB 1.0.0+1 · iOS Version 26.2 (Build 23C54) · locale en-BO
- Pantalla: 390×844 dp @3x
- Conexión al iniciar: wifi
- Inicio: 10/10/2026 13:54:31 (UTC-4) · duración 4m 22s
- Exportado: acciones 1–92 de 92 (+0.54s → +261.53s) · 16 pantallas · 31 requests · 2 errores · 0 logs · 1 nota
- Opciones: red estándar (bodies ≤ 2 KB) · capturas una por pantalla · secretos ocultos

## Notas

Notas escritas a mano por quien revisó la sesión, cada una sobre una acción concreta (lo que esperaba, lo que vio o lo que hay que revisar). Tómalas como contexto prioritario del análisis.

- +239.46s · acción 67 · ERROR s9 · Bad state: Error de prueba al abrir detalle desde Favoritos: Spider-Man: Brand New Day
  > Nota de demostración: al tocar la película desde Favoritos aparece este error.

## Hallazgos automáticos

- Errores: 2 — el primero en +239.46s (s9): Bad state: Error de prueba al abrir detalle desde Favoritos: Spider-Man: Brand New Day
- Mismo endpoint con distinta query: GET /3/discover/movie ×19 con 0.0 s de diferencia (#4, #5, #6, #7, #8, #9, #10, #11, #12, #13, #14, #15, #16, #17, #18, #19, #20, #21, #22)
- Taps sin etiqueta de widget: 14 de 30 (no se pudo identificar qué se tocó)
- La app pasó a segundo plano 1 vez (la más larga, 26.1 s)

## Recorrido

s1 → s2 (reemplazo) → s3 (reemplazo) → s4 (reemplazo) → s5 → s6 (atrás) → s7 → s8 → s9 (atrás) → s10 (atrás) → s11 → s12 (atrás) → s13 → s14 (atrás) → s15 (atrás) → s16

## Timeline

```
+0.54s    START   s1  [img: screens/01_t2.1s_pantalla_s1.jpg]
+2.57s    NAV     s1 → s2 (replace)  [img: screens/02_t4.3s_pantalla_s2.jpg]
+3.17s    NET     GET /3/movie/popular → 200 · 470 ms · 14 KB  [#1]
+7.40s    TAP     s2 · (sin etiqueta)
+8.45s    TAP     s2 · (ícono U+F57A)
+9.55s    TAP     s2 · (ícono U+F57A)
+9.72s    NAV     s2 → s3 (replace)  [img: screens/03_t10.3s_pantalla_s3.jpg]
+11.05s   TAP     s3 · (sin etiqueta)
+14.20s   INPUT   Escribió en «Nombre o alias»
+15.75s   TAP     s3 · (sin etiqueta)
+16.38s   TAP     s3 · (sin etiqueta)
+17.79s   NAV     s3 → s4 (replace)  [img: screens/04_t19.2s_pantalla_s4.jpg]
+18.39s   NET     GET /3/movie/now_playing → 200 · 450 ms · 13 KB  [#2]
+18.41s   NET     GET /3/genre/movie/list → 200 · 469 ms · 561 B  [#3]
+18.85s   NET     GET /3/discover/movie → 200 · 242 ms · 14 KB  [#4]
+18.85s   NET     GET /3/discover/movie → 200 · 248 ms · 14 KB  [#5]
+19.24s   NET     GET /3/discover/movie → 200 · 631 ms · 14 KB  [#6]
+19.24s   NET     GET /3/discover/movie → 200 · 633 ms · 12 KB  [#7]
+19.24s   NET     GET /3/discover/movie → 200 · 636 ms · 13 KB  [#8]
+19.25s   NET     GET /3/discover/movie → 200 · 639 ms · 14 KB  [#9]
+19.25s   NET     GET /3/discover/movie → 200 · 641 ms · 14 KB  [#10]
+19.25s   NET     GET /3/discover/movie → 200 · 647 ms · 13 KB  [#11]
+19.25s   NET     GET /3/discover/movie → 200 · 646 ms · 14 KB  [#12]
+19.26s   NET     GET /3/discover/movie → 200 · 653 ms · 16 KB  [#13]
+19.26s   NET     GET /3/discover/movie → 200 · 657 ms · 14 KB  [#14]
+19.27s   NET     GET /3/discover/movie → 200 · 659 ms · 14 KB  [#15]
+19.27s   NET     GET /3/discover/movie → 200 · 668 ms · 13 KB  [#16]
+19.28s   NET     GET /3/discover/movie → 200 · 675 ms · 13 KB  [#17]
+19.44s   NET     GET /3/discover/movie → 200 · 839 ms · 15 KB  [#18]
+19.48s   NET     GET /3/discover/movie → 200 · 873 ms · 14 KB  [#19]
+19.63s   NET     GET /3/discover/movie → 200 · 1021 ms · 14 KB  [#20]
+19.64s   NET     GET /3/discover/movie → 200 · 1028 ms · 17 KB  [#21]
+19.71s   NET     GET /3/discover/movie → 200 · 1106 ms · 11 KB  [#22]
+27.08s   SCROLL  s4
+29.13s   TAP     s4 · (sin etiqueta)
+29.25s   NAV     s4 → s5  [img: screens/05_t30.9s_pantalla_s5.jpg]
+29.72s   NET     GET /3/movie/969681/reviews → 200 · 396 ms · 69 B  [#23]
+29.75s   NET     GET /3/movie/969681/similar → 200 · 425 ms · 15 KB  [#24]
+29.79s   NET     GET /3/movie/969681&append_to_response=images → 200 · 462 ms · 2.0 KB  [#25]
+30.10s   SCROLL  s5
+30.10s   NET     GET /3/movie/969681/credits → 200 · 774 ms · 100 KB  [#26]
+32.20s   TAP     s5 · (sin etiqueta)
+32.94s   SCROLL  s5
+34.67s   TAP     s5 · "Favorito"
+36.67s   TAP     s5 · (ícono U+E092)
+36.75s   NAV     s5 → s6 (pop)  [img: screens/06_t38.4s_pantalla_s6.jpg]
+38.70s   SCROLL  s6  ×2
+41.40s   TAP     s6 · (ícono U+E567)
+76.77s   TAP     s6 · (sin etiqueta)
+81.61s   INPUT   Escribió en «Título, actor, género...»
+82.10s   NET     GET /3/search/movie → 200 · 376 ms · 8.5 KB  [#27]
+87.09s   APP     La app pasó a segundo plano
+113.22s  APP     La app volvió al primer plano (26 s en segundo plano)
+115.81s  TAP     s6 · (sin etiqueta)
+116.72s  TAP     s6 · (ícono U+E497)
+118.03s  TAP     s6 · "Favoritos"
+118.18s  NAV     s6 → s7  [img: screens/07_t118.8s_pantalla_s7.jpg]
+119.29s  TAP     s7 · "8.4"
+119.37s  NAV     s7 → s8  [img: screens/08_t120.0s_pantalla_s8.jpg]
+120.22s  SCROLL  s8  ×3
+133.26s  TAP     s8 · (ícono U+E092)
+133.32s  NAV     s8 → s9 (pop)  [img: screens/09_t134.1s_pantalla_s9.jpg]
+239.33s  TAP     s9 · (sin etiqueta)
+239.46s  ERROR   s9 · Bad state: Error de prueba al abrir detalle desde Favoritos: Spider-Man: Brand New Day  [img: screens/10_t239.5s_error_s9.jpg]
+239.46s  NOTA    «Nota de demostración: al tocar la película desde Favoritos aparece este error.»
+240.99s  SCROLL  s9
+242.31s  TAP     s9 · (sin etiqueta)
+242.44s  NAV     s9 → s10 (pop)  [img: screens/11_t244.2s_pantalla_s10.jpg]
+243.62s  TAP     s10 · (sin etiqueta)
+243.71s  NAV     s10 → s11  [img: screens/12_t244.6s_pantalla_s11.jpg]
+245.05s  TAP     s11 · (sin etiqueta)
+245.17s  ERROR   s11 · Bad state: Error de prueba al abrir detalle desde Favoritos: Spider-Man: Brand New Day  [img: screens/13_t245.2s_error_s11.jpg]
+247.58s  TAP     s11 · (ícono U+E092)
+247.71s  NAV     s11 → s12 (pop)  [img: screens/14_t249.8s_pantalla_s12.jpg]
+249.04s  TAP     s12 · (ícono U+F107)
+250.79s  TAP     s12 · (sin etiqueta)
+250.89s  NAV     s12 → s13  [img: screens/15_t252.2s_pantalla_s13.jpg]
+251.64s  NET     GET /3/movie/1712451&append_to_response=images → 200 · 679 ms · 1.0 KB  [#28]
+251.64s  NET     GET /3/movie/1712451/credits → 200 · 684 ms · 7.5 KB  [#29]
+251.72s  NET     GET /3/movie/1712451/reviews → 200 · 759 ms · 70 B  [#30]
+251.74s  NET     GET /3/movie/1712451/similar → 200 · 786 ms · 13 KB  [#31]
+252.54s  TAP     s13 · (sin etiqueta)
+254.57s  TAP     s13 · (ícono U+E092)
+254.71s  NAV     s13 → s14 (pop)  [img: screens/16_t256.4s_pantalla_s14.jpg]
+256.41s  TAP     s14 · (ícono U+E497)
+257.48s  TAP     s14 · "Cerrar sesión"
+258.79s  TAP     s14 · "Cerrar sesión"
+258.89s  NAV     s14 → s15 (pop)  [img: screens/17_t259.7s_pantalla_s15.jpg]
+258.95s  NAV     s15 → s16  [img: screens/18_t260.2s_pantalla_s16.jpg]
+261.53s  TAP     s16 · (ícono U+E34D)
```

## Red

### [#1] GET https://api.themoviedb.org/3/movie/popular?language=es-ES&page=1
+3.17s · s2 · status 200 · 470 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 17):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/4tjxYg2AbOzzG9G1YuiT2NzYhlH.jpg","genre_ids":[878,28,12],"id":969681,"title":"Spider-Man: Brand New Day","original_language":"en","original_title":"Spider-Man: Brand New Day","overview":"Han pasado cuatro años desde los acontecimientos de No Way Home, y Peter Parker ahora es un adulto que vive completamente solo, ha desaparecido voluntariamente de las vidas y recuerdos de quienes ama. Combatiendo el crimen en una Nueva York que ya no conoce su nombre, se ha dedicado por completo a p… (603 caracteres)","popularity":942.3201,"poster_path":"/9g0sEFhmvmK4nGhXj8DHuv2noYI.jpg","release_date":"2026-07-29","softcore":false,"video":false,"vote_average":8.4,"vote_count":4748},{"adult":false,"backdrop_path":"/3icyRAqgakNcQn6aDVz9libFmBA.jpg","genre_ids":[27,878,12],"id":1423191,"title":"Resident Evil","original_language":"en","original_title":"Resident Evil","overview":"Película basada en la saga de videojuegos de Capcom del mismo nombre. En una reinvención totalmente nueva, el mensajero médico Bryan se ve inmerso en una carrera de acción sin descanso por la supervivencia, mientras el caos se desata a su alrededor.","popularity":703.1893,"poster_path":"/ntmaNFJ7O60n45E1E6HZlXeSV5e.jpg","release_date":"2026-09-16","softcore":false,"video":false,"vote_average":7.323,"vote_count":838},{"adult":false,"backdrop_path":"/p40lmrdI4blcAPZQMTPaiy5v5Ym.jpg","genre_ids":[27,53],"id":1291595,"title":"Insidious: Fuera del más allá","original_language":"en","original_title":"Insidious: Out of the Further","overview":"La saga de terror vuelve a sus raíces sobrenaturales. Una nueva protagonista se enfrenta a misteriosas apariciones que van mucho más allá de los fenómenos de embrujamiento clásicos. El mal encuentra nuevos caminos en la realidad. Un trío de acechadores se infiltra en un tranquilo suburbio obligando … (431 caracteres)","popularity":376.7586,"poster_path":"/uIMddTcnM9P6PrJiDjsXIeYp902.jpg","release_date":"2026-08-19","softcore":false,"video":false,"vote_average":7.601,"vote_count":500},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#2] GET https://api.themoviedb.org/3/movie/now_playing?language=es-ES&page=1
+18.39s · s4 · status 200 · 450 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 17):
  content-type: application/json;charset=utf-8
Response body (13 KB, arrays/textos largos recortados):
```json
{"dates":{"maximum":"2026-10-14","minimum":"2026-09-02"},"page":1,"results":[{"adult":false,"backdrop_path":"/3icyRAqgakNcQn6aDVz9libFmBA.jpg","genre_ids":[27,878,12],"id":1423191,"title":"Resident Evil","original_language":"en","original_title":"Resident Evil","overview":"Película basada en la saga de videojuegos de Capcom del mismo nombre. En una reinvención totalmente nueva, el mensajero médico Bryan se ve inmerso en una carrera de acción sin descanso por la supervivencia, mientras el caos se desata a su alrededor.","popularity":703.1893,"poster_path":"/ntmaNFJ7O60n45E1E6HZlXeSV5e.jpg","release_date":"2026-09-16","softcore":false,"video":false,"vote_average":7.3,"vote_count":836},{"adult":false,"backdrop_path":"/bulFtfy3oBQtCnAMSi7g6DSSds3.jpg","genre_ids":[12,28,14],"id":1368337,"title":"La Odisea","original_language":"en","original_title":"The Odyssey","overview":"Tras la caída de Troya, el legendario rey de Ítaca, Odiseo a.k.a. Ulises, emprende un largo y peligroso viaje para regresar junto a su esposa Penélope y su hijo Telémaco. En el camino deberá enfrentarse a criaturas mitológicas, dioses caprichosos y pruebas que pondrán a prueba su ingenio, su resiste… (447 caracteres)","popularity":366.1539,"poster_path":"/sf2ke1nwFOLLcwLZiXu9VaMMv8e.jpg","release_date":"2026-07-15","softcore":false,"video":false,"vote_average":8,"vote_count":4070},{"adult":false,"backdrop_path":"/yT8EkAvEkJDFeAxK7s7HlIPELRT.jpg","genre_ids":[28,53],"id":1228834,"title":"Operación Teherán","original_language":"en","original_title":"The Fix","overview":"Tras el final de la guerra en Afganistán, un grupo de exoperadores de la CIA se han quedado marcados por la violencia, el abandono y la culpa. Sin patria ni propósitos a corto plazo, aceptan una última misión y viajan a Teherán para llevar a cabo un golpe arriesgado e ilegal que podría ser su opción… (595 caracteres)","popularity":271.1705,"poster_path":"/5uB1PWP3QHEcgMXKChsaYmtTUkQ.jpg","release_date":"2026-09-10","softcore":false,"video":false,"vote_average":6.783,"vote_count":53},"… (+17 elementos más)"],"total_pages":327,"total_results":6524}
```

### [#3] GET https://api.themoviedb.org/3/genre/movie/list?language=es-ES
+18.41s · s4 · status 200 · 469 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 17):
  content-type: application/json;charset=utf-8
Response body (561 B, arrays/textos largos recortados):
```json
{"genres":[{"id":28,"name":"Acción"},{"id":12,"name":"Aventura"},{"id":16,"name":"Animación"},"… (+16 elementos más)"]}
```

### [#4] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=28
+18.85s · s4 · status 200 · 242 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/4tjxYg2AbOzzG9G1YuiT2NzYhlH.jpg","genre_ids":[878,28,12],"id":969681,"title":"Spider-Man: Brand New Day","original_language":"en","original_title":"Spider-Man: Brand New Day","overview":"Han pasado cuatro años desde los acontecimientos de No Way Home, y Peter Parker ahora es un adulto que vive completamente solo, ha desaparecido voluntariamente de las vidas y recuerdos de quienes ama. Combatiendo el crimen en una Nueva York que ya no conoce su nombre, se ha dedicado por completo a p… (603 caracteres)","popularity":942.3201,"poster_path":"/9g0sEFhmvmK4nGhXj8DHuv2noYI.jpg","release_date":"2026-07-29","softcore":false,"video":false,"vote_average":8.38,"vote_count":4758},{"adult":false,"backdrop_path":"/twiVn9oFXOVR0uoYgawyEBlnFu8.jpg","genre_ids":[12,28,14],"id":1368337,"title":"La Odisea","original_language":"en","original_title":"The Odyssey","overview":"Tras la caída de Troya, el legendario rey de Ítaca, Odiseo a.k.a. Ulises, emprende un largo y peligroso viaje para regresar junto a su esposa Penélope y su hijo Telémaco. En el camino deberá enfrentarse a criaturas mitológicas, dioses caprichosos y pruebas que pondrán a prueba su ingenio, su resiste… (447 caracteres)","popularity":366.1539,"poster_path":"/sf2ke1nwFOLLcwLZiXu9VaMMv8e.jpg","release_date":"2026-07-15","softcore":false,"video":false,"vote_average":8,"vote_count":4070},{"adult":false,"backdrop_path":"/yT8EkAvEkJDFeAxK7s7HlIPELRT.jpg","genre_ids":[28,53],"id":1228834,"title":"Operación Teherán","original_language":"en","original_title":"The Fix","overview":"Tras el final de la guerra en Afganistán, un grupo de exoperadores de la CIA se han quedado marcados por la violencia, el abandono y la culpa. Sin patria ni propósitos a corto plazo, aceptan una última misión y viajan a Teherán para llevar a cabo un golpe arriesgado e ilegal que podría ser su opción… (595 caracteres)","popularity":271.1705,"poster_path":"/5uB1PWP3QHEcgMXKChsaYmtTUkQ.jpg","release_date":"2026-09-10","softcore":false,"video":false,"vote_average":6.783,"vote_count":53},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#5] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=12
+18.85s · s4 · status 200 · 248 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/4tjxYg2AbOzzG9G1YuiT2NzYhlH.jpg","genre_ids":[878,28,12],"id":969681,"title":"Spider-Man: Brand New Day","original_language":"en","original_title":"Spider-Man: Brand New Day","overview":"Han pasado cuatro años desde los acontecimientos de No Way Home, y Peter Parker ahora es un adulto que vive completamente solo, ha desaparecido voluntariamente de las vidas y recuerdos de quienes ama. Combatiendo el crimen en una Nueva York que ya no conoce su nombre, se ha dedicado por completo a p… (603 caracteres)","popularity":942.3201,"poster_path":"/9g0sEFhmvmK4nGhXj8DHuv2noYI.jpg","release_date":"2026-07-29","softcore":false,"video":false,"vote_average":8.38,"vote_count":4758},{"adult":false,"backdrop_path":"/3icyRAqgakNcQn6aDVz9libFmBA.jpg","genre_ids":[27,878,12],"id":1423191,"title":"Resident Evil","original_language":"en","original_title":"Resident Evil","overview":"Película basada en la saga de videojuegos de Capcom del mismo nombre. En una reinvención totalmente nueva, el mensajero médico Bryan se ve inmerso en una carrera de acción sin descanso por la supervivencia, mientras el caos se desata a su alrededor.","popularity":703.1893,"poster_path":"/ntmaNFJ7O60n45E1E6HZlXeSV5e.jpg","release_date":"2026-09-16","softcore":false,"video":false,"vote_average":7.3,"vote_count":839},{"adult":false,"backdrop_path":"/twiVn9oFXOVR0uoYgawyEBlnFu8.jpg","genre_ids":[12,28,14],"id":1368337,"title":"La Odisea","original_language":"en","original_title":"The Odyssey","overview":"Tras la caída de Troya, el legendario rey de Ítaca, Odiseo a.k.a. Ulises, emprende un largo y peligroso viaje para regresar junto a su esposa Penélope y su hijo Telémaco. En el camino deberá enfrentarse a criaturas mitológicas, dioses caprichosos y pruebas que pondrán a prueba su ingenio, su resiste… (447 caracteres)","popularity":366.1539,"poster_path":"/sf2ke1nwFOLLcwLZiXu9VaMMv8e.jpg","release_date":"2026-07-15","softcore":false,"video":false,"vote_average":8,"vote_count":4070},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#6] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=16
+19.24s · s4 · status 200 · 631 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/qjTqY5coNiz6sVtPng40IzltsoN.jpg","genre_ids":[16,10751,35,12],"id":1084244,"title":"Toy Story 5","original_language":"en","original_title":"Toy Story 5","overview":"Los juguetes de Bonnie se enfrentan a otra amenaza cuando la niña recibe una tableta llamada Lilypad, la cual absorbe toda su atención y pone en peligro el juego tradicional. Todos deben unirse para competir contra la tecnología y recuperar su lugar.","popularity":151.0495,"poster_path":"/pTjZfbFVWUIwUM5OzX3LVh84ejU.jpg","release_date":"2026-06-17","softcore":false,"video":false,"vote_average":8.3,"vote_count":2552},{"adult":false,"backdrop_path":"/rJT7ARv4G2sr1uTZnBEUSigg1hf.jpg","genre_ids":[16,28,12,14],"id":1599191,"title":"仙逆剧场版：弑仙之战","original_language":"zh","original_title":"仙逆剧场版：弑仙之战","overview":"","popularity":95.7413,"poster_path":"/cpgLuRAT8SW7YiZaBYUGZ43GiLL.jpg","release_date":"2026-10-01","softcore":false,"video":false,"vote_average":7.633,"vote_count":15},{"adult":false,"backdrop_path":"/lgotja3xMoJZbynwHfcQcJAEMWH.jpg","genre_ids":[16,12,35,9648,10751],"id":1084242,"title":"Zootrópolis 2","original_language":"en","original_title":"Zootopia 2","overview":"Después de resolver el caso más importante en la historia de Zootrópolis, los policías novatos Judy Hopps y Nick Wilde descubren que su asociación no es tan sólida como pensaban cuando el Jefe Bogo les ordena unirse al programa de consejería \"Compañeros en Crisis\". Pero no pasa mucho tiempo para que… (413 caracteres)","popularity":93.2525,"poster_path":"/4fRdfQPjHiuDSkzaxFAV44k7Iem.jpg","release_date":"2025-11-26","softcore":false,"video":false,"vote_average":7.666,"vote_count":3535},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#7] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=27
+19.24s · s4 · status 200 · 633 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (12 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/3icyRAqgakNcQn6aDVz9libFmBA.jpg","genre_ids":[27,878,12],"id":1423191,"title":"Resident Evil","original_language":"en","original_title":"Resident Evil","overview":"Película basada en la saga de videojuegos de Capcom del mismo nombre. En una reinvención totalmente nueva, el mensajero médico Bryan se ve inmerso en una carrera de acción sin descanso por la supervivencia, mientras el caos se desata a su alrededor.","popularity":703.1893,"poster_path":"/ntmaNFJ7O60n45E1E6HZlXeSV5e.jpg","release_date":"2026-09-16","softcore":false,"video":false,"vote_average":7.3,"vote_count":839},{"adult":false,"backdrop_path":"/p40lmrdI4blcAPZQMTPaiy5v5Ym.jpg","genre_ids":[27,53],"id":1291595,"title":"Insidious: Fuera del más allá","original_language":"en","original_title":"Insidious: Out of the Further","overview":"La saga de terror vuelve a sus raíces sobrenaturales. Una nueva protagonista se enfrenta a misteriosas apariciones que van mucho más allá de los fenómenos de embrujamiento clásicos. El mal encuentra nuevos caminos en la realidad. Un trío de acechadores se infiltra en un tranquilo suburbio obligando … (431 caracteres)","popularity":376.7586,"poster_path":"/uIMddTcnM9P6PrJiDjsXIeYp902.jpg","release_date":"2026-08-19","softcore":false,"video":false,"vote_average":7.595,"vote_count":503},{"adult":false,"backdrop_path":"/yKx5gYrYgakKZuUWAsuFDStBroy.jpg","genre_ids":[27],"id":1712451,"title":"Dead Residents Evil","original_language":"en","original_title":"Resident Dead","overview":"Un padre lucha contra un ejercito de no-muertos junto a su hija, gravemente herida, para llegar a la cura antes de que ella se transforme. Si logra llegar al laboratorio con la vacuna a tiempo, cree que su hija estará a salvo. Lamentablemente, el desafío más horrible lo espera en su destino final.","popularity":179.573,"poster_path":"/yX8ziNTZ5aOszJ3l4R3BlT2gBIa.jpg","release_date":"2026-09-04","softcore":false,"video":false,"vote_average":5.929,"vote_count":7},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#8] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=9648
+19.24s · s4 · status 200 · 636 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (13 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/b9q9VmbXDvJmTziRqkwdEmFdwhr.jpg","genre_ids":[878,9648,53],"id":1101383,"title":"El final de Oak Street","original_language":"en","original_title":"The End of Oak Street","overview":"Después de que un misterioso fenómeno cósmico arranque Oak Street de su entorno suburbano y transporte a sus habitantes a un lugar desconocido, la familia Platt pronto descubre que su propia supervivencia depende de que permanezcan unidos mientras se orientan en un entorno que ya no reconocen.","popularity":165.7164,"poster_path":"/g9DUGw8ufetrwhCIrwq3h1NlpWO.jpg","release_date":"2026-08-12","softcore":false,"video":false,"vote_average":7.088,"vote_count":1950},{"adult":false,"backdrop_path":"/vgZDb7kmaxP24cFbt1KJdMLlHFZ.jpg","genre_ids":[27,14,9648],"id":1232569,"title":"Pinocho: Desatado","original_language":"en","original_title":"Pinocchio: Unstrung","overview":"Gepetto le regala para el cumple de su nieto James un titere llamado Pinocho, aunque no sabian que estaria desquiciado, donde buscaria matar a quien fuera junto con su consciencia llamada Pepe Grillo para convertirse en un niño de verdad","popularity":138.4103,"poster_path":"/kuPRjis9YN1V9m4ud0hePtREUCo.jpg","release_date":"2026-07-22","softcore":false,"video":false,"vote_average":6.5,"vote_count":127},{"adult":false,"backdrop_path":"/9qxyrJfjk577ym5WD6HCDmunoyO.jpg","genre_ids":[9648,53],"id":1283515,"title":"Verity. La sombra de un engaño","original_language":"en","original_title":"Verity","overview":"Lowen Ashleigh es contratada como escritora fantasma por Jeremy Crawford para escribir las novelas de su esposa Verity, autora de bestsellers, impedida tras un accidente. Lowen descubre las inquietantes verdades de Verity mientras reside en casa de los Crawford para trabajar.","popularity":110.7586,"poster_path":"/t1rkXeUMJzsCS142ctqzbz4zGq7.jpg","release_date":"2026-09-30","softcore":false,"video":false,"vote_average":6.411,"vote_count":146},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#9] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=10770
+19.25s · s4 · status 200 · 639 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/hDwl0YMxwGhNe7u8wgHHk2Hyw3W.jpg","genre_ids":[10770,10751,28,878],"id":1506560,"title":"Furia de los Thunderman","original_language":"en","original_title":"Clash of the Thundermans","overview":"Chloe, la hermana pequeña, desarrolla de repente un poder energético impredecible, y la Liga de Héroes exige enviarla a un internado de alta seguridad. La familia se divide: unos quieren entregarla por seguridad y otros deciden esconderla. Cuando la decana revela un plan oculto y peligroso, todos te… (352 caracteres)","popularity":35.1696,"poster_path":"/7zgvtsSPFH4rnV4UEXt9aqNKzIB.jpg","release_date":"2026-09-03","softcore":false,"video":false,"vote_average":6.5,"vote_count":64},{"adult":false,"backdrop_path":"/qlfqDJ9Piv5ufzYA8j2319mwKZU.jpg","genre_ids":[14,10770,10751,12],"id":1318621,"title":"Los Descendientes: viaje al mundo oscuro","original_language":"en","original_title":"Descendants: Wicked Wonderland","overview":"Red y Chloe logran cambiar la historia: impiden que la Reina de Corazones se vuelva villana y salvan a Cenicienta. Todo parece irles de maravilla, pero alterar el pasado tiene consecuencias inesperadas. Sombrerero, antiguo amigo de Red, emerge como nuevo villano y captura a la Reina. Para salvarla a… (508 caracteres)","popularity":20.9146,"poster_path":"/pBY8LeKTcgqeWKztgclJvRs8z1T.jpg","release_date":"2026-07-16","softcore":false,"video":false,"vote_average":7.5,"vote_count":189},{"adult":false,"backdrop_path":"/vDR2h5uQNgWyx3fsEVnEOcNFibZ.jpg","genre_ids":[53,80,10770],"id":801335,"title":"La chica en el sótano","original_language":"en","original_title":"Girl in the Basement","overview":"Sara es una adolescente que está deseando cumplir 18 años para alejarse de su padre controlador, Don. Pero antes de que pudiera apagar las velas, Don la aprisiona en el sótano de su casa.","popularity":18.3947,"poster_path":"/4p6uMC8PxEHSY5hJR0KJkOt3wPk.jpg","release_date":"2021-02-27","softcore":false,"video":false,"vote_average":7.572,"vote_count":900},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#10] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=14
+19.25s · s4 · status 200 · 641 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/twiVn9oFXOVR0uoYgawyEBlnFu8.jpg","genre_ids":[12,28,14],"id":1368337,"title":"La Odisea","original_language":"en","original_title":"The Odyssey","overview":"Tras la caída de Troya, el legendario rey de Ítaca, Odiseo a.k.a. Ulises, emprende un largo y peligroso viaje para regresar junto a su esposa Penélope y su hijo Telémaco. En el camino deberá enfrentarse a criaturas mitológicas, dioses caprichosos y pruebas que pondrán a prueba su ingenio, su resiste… (447 caracteres)","popularity":366.1539,"poster_path":"/sf2ke1nwFOLLcwLZiXu9VaMMv8e.jpg","release_date":"2026-07-15","softcore":false,"video":false,"vote_average":8,"vote_count":4070},{"adult":false,"backdrop_path":"/vgZDb7kmaxP24cFbt1KJdMLlHFZ.jpg","genre_ids":[27,14,9648],"id":1232569,"title":"Pinocho: Desatado","original_language":"en","original_title":"Pinocchio: Unstrung","overview":"Gepetto le regala para el cumple de su nieto James un titere llamado Pinocho, aunque no sabian que estaria desquiciado, donde buscaria matar a quien fuera junto con su consciencia llamada Pepe Grillo para convertirse en un niño de verdad","popularity":138.4103,"poster_path":"/kuPRjis9YN1V9m4ud0hePtREUCo.jpg","release_date":"2026-07-22","softcore":false,"video":false,"vote_average":6.5,"vote_count":127},{"adult":false,"backdrop_path":"/rJT7ARv4G2sr1uTZnBEUSigg1hf.jpg","genre_ids":[16,28,12,14],"id":1599191,"title":"仙逆剧场版：弑仙之战","original_language":"zh","original_title":"仙逆剧场版：弑仙之战","overview":"","popularity":95.7413,"poster_path":"/cpgLuRAT8SW7YiZaBYUGZ43GiLL.jpg","release_date":"2026-10-01","softcore":false,"video":false,"vote_average":7.633,"vote_count":15},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#11] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=35
+19.25s · s4 · status 200 · 647 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (13 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/iXR79oKsLHwLno9jdzxxeFP21sy.jpg","genre_ids":[28,35],"id":1377237,"title":"Entrega al límite","original_language":"en","original_title":"Runner","overview":"Un exsoldado se ve envuelto en una brutal carrera contrarreloj cuando una entrega médica crucial los convierte, a él y a su inesperada compañera, en el objetivo de un cártel despiadado. A medida que la misión se transforma en una cacería mortal, cada desvío, retraso y bala los acerca más al fracaso.… (441 caracteres)","popularity":252.7218,"poster_path":"/pmjSjZtFOYDWhAs4B2AbBE8hTQf.jpg","release_date":"2026-09-07","softcore":false,"video":false,"vote_average":8.297,"vote_count":454},{"adult":false,"backdrop_path":"/viZqGq9TNvQ5uXSD4ahg2RpRONT.jpg","genre_ids":[35,12,10751],"id":1204680,"title":"Coyote vs. Acme","original_language":"en","original_title":"Coyote vs. Acme","overview":"Después de que todos los productos fabricados por ACME Corporation le salgan mal a Wile E. Coyote, en su persecución del Correcaminos, contrata a un abogado humano igualmente desafortunado para demandar a la empresa. Cuando el abogado de Wile E. descubre que el intimidante jefe de su antiguo bufete … (380 caracteres)","popularity":174.5056,"poster_path":"/vWFz9spZFBkJvForuYrKK2ntOLB.jpg","release_date":"2026-08-17","softcore":false,"video":false,"vote_average":7.508,"vote_count":708},{"adult":false,"backdrop_path":"/jdJsnhHfkIi3J7jwfiCFT4gXNx5.jpg","genre_ids":[28,35,12],"id":1148365,"title":"Matchbox: La película","original_language":"en","original_title":"Matchbox the Movie","overview":"Varios amigos de la infancia se reúnen y el reencuentro se sale de madre cuando acaban metidos en un peligroso complot internacional y se ven obligados a salvar el mundo.","popularity":164.8642,"poster_path":"/ev2GnYar3LUyui8sOu4gqeMXvLi.jpg","release_date":"2026-10-05","softcore":false,"video":false,"vote_average":7.643,"vote_count":98},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#12] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=10751
+19.25s · s4 · status 200 · 646 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/viZqGq9TNvQ5uXSD4ahg2RpRONT.jpg","genre_ids":[35,12,10751],"id":1204680,"title":"Coyote vs. Acme","original_language":"en","original_title":"Coyote vs. Acme","overview":"Después de que todos los productos fabricados por ACME Corporation le salgan mal a Wile E. Coyote, en su persecución del Correcaminos, contrata a un abogado humano igualmente desafortunado para demandar a la empresa. Cuando el abogado de Wile E. descubre que el intimidante jefe de su antiguo bufete … (380 caracteres)","popularity":174.5056,"poster_path":"/vWFz9spZFBkJvForuYrKK2ntOLB.jpg","release_date":"2026-08-17","softcore":false,"video":false,"vote_average":7.508,"vote_count":708},{"adult":false,"backdrop_path":"/qjTqY5coNiz6sVtPng40IzltsoN.jpg","genre_ids":[16,10751,35,12],"id":1084244,"title":"Toy Story 5","original_language":"en","original_title":"Toy Story 5","overview":"Los juguetes de Bonnie se enfrentan a otra amenaza cuando la niña recibe una tableta llamada Lilypad, la cual absorbe toda su atención y pone en peligro el juego tradicional. Todos deben unirse para competir contra la tecnología y recuperar su lugar.","popularity":151.0495,"poster_path":"/pTjZfbFVWUIwUM5OzX3LVh84ejU.jpg","release_date":"2026-06-17","softcore":false,"video":false,"vote_average":8.3,"vote_count":2552},{"adult":false,"backdrop_path":"/c6BPbkO5Npt1OdwttAxCFo06wtH.jpg","genre_ids":[10751,14,35,12],"id":1108427,"title":"Vaiana","original_language":"en","original_title":"Moana","overview":"Vaiana (Catherine Lagaʻaia) responde a la llamada del océano y, por primera vez, viaja más allá del arrecife de su isla de Motunui con el semidiós Maui (Dwayne Johnson) en un viaje inolvidable para devolver la prosperidad a su pueblo.","popularity":94.5736,"poster_path":"/xUUksaUc30wX5orsYytApurKbX.jpg","release_date":"2026-07-08","softcore":false,"video":false,"vote_average":7.4,"vote_count":879},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#13] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=10752
+19.26s · s4 · status 200 · 653 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (16 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/8FCHJ21JBQOgATY2WI8vwYAiXg8.jpg","genre_ids":[36,18,53,10752],"id":205596,"title":"The Imitation Game (Descifrando Enigma)","original_language":"en","original_title":"The Imitation Game","overview":"Durante el invierno de 1952, las autoridades británicas entraron en el hogar del matemático, analista y héroe de guerra Alan Turing, con la intención de investigar la denuncia de un robo. Al final acabaron arrestando a Turing acusándole de indecencia grave, un cargo que le supondría una devastadora … (698 caracteres)","popularity":49.98,"poster_path":"/pdd20KgHJec4BM4sfHS8oefaDUI.jpg","release_date":"2014-11-14","softcore":false,"video":false,"vote_average":7.978,"vote_count":18509},{"adult":false,"backdrop_path":"/uujYvxE9s6KY4SbBZ0ZFN3oBJhW.jpg","genre_ids":[28,10752],"id":1594914,"title":"Lucky Strike","original_language":"en","original_title":"Lucky Strike","overview":"Un soldado estadounidense gravemente herido lucha por sobrevivir, durante la II Guerra Mundial, detrás de las líneas enemigas en la Bélgica devastada por la guerra durante la brutal Batalla de las Ardenas. Aislado y obligado a afrontar unas condiciones extremas, debe confiar en su ingenio, su entren… (548 caracteres)","popularity":38.9801,"poster_path":"/c4az2YuhUDmGTRYjsYdD3tFjwuG.jpg","release_date":"2026-06-26","softcore":false,"video":false,"vote_average":6.6,"vote_count":55},{"adult":false,"backdrop_path":"/kP8rK9dGS1pr0HrnmXfIi2heWjo.jpg","genre_ids":[18,28,12,36,10752],"id":1495,"title":"El reino de los cielos","original_language":"en","original_title":"Kingdom of Heaven","overview":"Balián de Ibelín viaja a Jerusalén durante las cruzadas del siglo XII, donde será el defensor de su pueblo.","popularity":37.7937,"poster_path":"/pIrjgBmZYnwKvx4WoTkhyhKSHTp.jpg","release_date":"2005-05-03","softcore":false,"video":false,"vote_average":7.096,"vote_count":5288},"… (+17 elementos más)"],"total_pages":676,"total_results":13519}
```

### [#14] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=878
+19.26s · s4 · status 200 · 657 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/4tjxYg2AbOzzG9G1YuiT2NzYhlH.jpg","genre_ids":[878,28,12],"id":969681,"title":"Spider-Man: Brand New Day","original_language":"en","original_title":"Spider-Man: Brand New Day","overview":"Han pasado cuatro años desde los acontecimientos de No Way Home, y Peter Parker ahora es un adulto que vive completamente solo, ha desaparecido voluntariamente de las vidas y recuerdos de quienes ama. Combatiendo el crimen en una Nueva York que ya no conoce su nombre, se ha dedicado por completo a p… (603 caracteres)","popularity":942.3201,"poster_path":"/9g0sEFhmvmK4nGhXj8DHuv2noYI.jpg","release_date":"2026-07-29","softcore":false,"video":false,"vote_average":8.38,"vote_count":4758},{"adult":false,"backdrop_path":"/3icyRAqgakNcQn6aDVz9libFmBA.jpg","genre_ids":[27,878,12],"id":1423191,"title":"Resident Evil","original_language":"en","original_title":"Resident Evil","overview":"Película basada en la saga de videojuegos de Capcom del mismo nombre. En una reinvención totalmente nueva, el mensajero médico Bryan se ve inmerso en una carrera de acción sin descanso por la supervivencia, mientras el caos se desata a su alrededor.","popularity":703.1893,"poster_path":"/ntmaNFJ7O60n45E1E6HZlXeSV5e.jpg","release_date":"2026-09-16","softcore":false,"video":false,"vote_average":7.3,"vote_count":839},{"adult":false,"backdrop_path":"/k22XyPbce7zvzzf5OnT4uaY8ZD1.jpg","genre_ids":[878,18,53],"id":1751701,"title":"After Impact","original_language":"en","original_title":"After Impact","overview":"Después de heredar el enorme invernadero de su padre cuando un asteroide amenaza a la Tierra, Ethan enfrenta la traición y el aislamiento. Sobreviviendo al impacto en el búnker de su familia, maltratado y desesperado, una voz en la radio revela que no está solo.","popularity":195.0907,"poster_path":"/yzDuAQCY2n6zzOlBkn6JzhLhY3k.jpg","release_date":"2026-09-15","softcore":false,"video":false,"vote_average":6,"vote_count":25},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#15] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=10749
+19.27s · s4 · status 200 · 659 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/o7Oy9Gbx1CCyaweL8xUhtMW4Puq.jpg","genre_ids":[10749,35],"id":1032863,"title":"La hipótesis del amor","original_language":"en","original_title":"The Love Hypothesis","overview":"Olive es una brillante estudiante de doctorado. Cuando descubre que su mejor amiga, Ahn, se ha enamorado de Jeremy, el chico que a ella le gustaba, Olive besa impulsivamente al intimidante profesor Adam Carlsen para demostrar que lo ha superado. El beso les lleva a ambos a mantener una relación fals… (525 caracteres)","popularity":132.4337,"poster_path":"/ylrSdW6fZYwaInYH6WAqvIEnSiV.jpg","release_date":"2026-09-23","softcore":false,"video":false,"vote_average":8.017,"vote_count":545},{"adult":false,"backdrop_path":"/wH2RtKsUjGc3ycRvxqOSbzov0av.jpg","genre_ids":[18,10749],"id":45722,"title":"No mires para abajo","original_language":"es","original_title":"No mires para abajo","overview":"Eloy es un adolescente de diecinueve años que trabaja junto a sus padres. Su trabajo consiste en repartir lápidas y figuras ornamentales en las sepulturas que atiende el negocio familiar en el cementerio de la ciudad. Al morir su padre, Eloy ve acelerar el tiempo que lo llevará a madurar en un mundo… (500 caracteres)","popularity":80.5723,"poster_path":"/97FUF1MbKpW0ZwwhnDbeoI2cPB4.jpg","release_date":"2008-10-18","softcore":false,"video":false,"vote_average":5.7,"vote_count":71},{"adult":false,"backdrop_path":"/uU1Mt4JWhDvl4vKb3AfxNsorkoM.jpg","genre_ids":[10751,14,10749],"id":321612,"title":"La bella y la bestia","original_language":"en","original_title":"Beauty and the Beast","overview":"Bella, una joven hermosa y brillante, asume el lugar de su padre como prisionero en el castillo de una bestia. Poco a poco, la valiente Bella irá dándose cuenta de que el príncipe bestia no es el malvado ser que todos creen que es y tiene, en realidad, un gran corazón.","popularity":70.1215,"poster_path":"/aGJkPbMixqD6j0OjbbGouSMbiZO.jpg","release_date":"2017-03-16","softcore":false,"video":false,"vote_average":7,"vote_count":16202},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#16] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=53
+19.27s · s4 · status 200 · 668 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (13 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/p40lmrdI4blcAPZQMTPaiy5v5Ym.jpg","genre_ids":[27,53],"id":1291595,"title":"Insidious: Fuera del más allá","original_language":"en","original_title":"Insidious: Out of the Further","overview":"La saga de terror vuelve a sus raíces sobrenaturales. Una nueva protagonista se enfrenta a misteriosas apariciones que van mucho más allá de los fenómenos de embrujamiento clásicos. El mal encuentra nuevos caminos en la realidad. Un trío de acechadores se infiltra en un tranquilo suburbio obligando … (431 caracteres)","popularity":376.7586,"poster_path":"/uIMddTcnM9P6PrJiDjsXIeYp902.jpg","release_date":"2026-08-19","softcore":false,"video":false,"vote_average":7.595,"vote_count":503},{"adult":false,"backdrop_path":"/yT8EkAvEkJDFeAxK7s7HlIPELRT.jpg","genre_ids":[28,53],"id":1228834,"title":"Operación Teherán","original_language":"en","original_title":"The Fix","overview":"Tras el final de la guerra en Afganistán, un grupo de exoperadores de la CIA se han quedado marcados por la violencia, el abandono y la culpa. Sin patria ni propósitos a corto plazo, aceptan una última misión y viajan a Teherán para llevar a cabo un golpe arriesgado e ilegal que podría ser su opción… (595 caracteres)","popularity":271.1705,"poster_path":"/5uB1PWP3QHEcgMXKChsaYmtTUkQ.jpg","release_date":"2026-09-10","softcore":false,"video":false,"vote_average":6.783,"vote_count":53},{"adult":false,"backdrop_path":"/yBDxqDB29kpH9VojTytjGWBgmdJ.jpg","genre_ids":[53],"id":1101412,"title":"Fall 2: Deadpoint","original_language":"en","original_title":"Fall 2: Deadpoint","overview":"Tras perder a su intrépida hermana Shiloh, Jax, profundamente dolida, emprende una peligrosa escalada con Luce, una vieja amiga de Shiloh, para honrar su memoria. Mientras caminan sobre la cuerda floja por los peligrosos tablones del monte Kwan, un aterrador desprendimiento de rocas les deja varados… (475 caracteres)","popularity":241.2549,"poster_path":"/ccBIyg1ITvuCDr4eMeEH0ZgNh4t.jpg","release_date":"2026-09-01","softcore":false,"video":false,"vote_average":7.216,"vote_count":317},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#17] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=18
+19.28s · s4 · status 200 · 675 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (13 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/k22XyPbce7zvzzf5OnT4uaY8ZD1.jpg","genre_ids":[878,18,53],"id":1751701,"title":"After Impact","original_language":"en","original_title":"After Impact","overview":"Después de heredar el enorme invernadero de su padre cuando un asteroide amenaza a la Tierra, Ethan enfrenta la traición y el aislamiento. Sobreviviendo al impacto en el búnker de su familia, maltratado y desesperado, una voz en la radio revela que no está solo.","popularity":195.0907,"poster_path":"/yzDuAQCY2n6zzOlBkn6JzhLhY3k.jpg","release_date":"2026-09-15","softcore":false,"video":false,"vote_average":6,"vote_count":25},{"adult":false,"backdrop_path":"/u3EtxdmZeiliW98c5Oegk5LIGZa.jpg","genre_ids":[35,18],"id":1248832,"title":"Digger","original_language":"en","original_title":"Digger","overview":"El hombre más poderoso del mundo se embarca en una misión frenética para demostrar que es el salvador de la humanidad antes de que el desastre que ha desencadenado lo destruya todo.","popularity":148.5371,"poster_path":"/koqE0V2IgIPVy5o2vVkoGJvnB8b.jpg","release_date":"2026-09-28","softcore":false,"video":false,"vote_average":7.478,"vote_count":275},{"adult":false,"backdrop_path":"/tzoarEu7TsG959upiELyYPm5kO9.jpg","genre_ids":[53,18],"id":1236045,"title":"Animales","original_language":"en","original_title":"Animals","overview":"El secuestro de su hijo obliga a un candidato a la alcaldía de Los Ángeles y a su mujer a reunir el dinero del rescate y a tomar decisiones que podrían destruir sus vidas.","popularity":136.1972,"poster_path":"/hhycOr6ji35RMGHnstHN4UKAvR4.jpg","release_date":"2026-10-09","softcore":false,"video":false,"vote_average":7.069,"vote_count":94},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#18] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=80
+19.44s · s4 · status 200 · 839 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (15 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/ch8ck4dxosMqp2lvIVYOdHVeKNp.jpg","genre_ids":[80,9648,53],"id":1300945,"title":"Un lugar llamado silencio","original_language":"zh","original_title":"Un lugar llamado silencio","overview":"Chen Yutong, una estudiante de secundaria, muere tras caer desde lo alto después de sufrir acoso escolar durante un largo periodo. El acoso no cesa y se extiende a su mejor amiga. Sin embargo, los acosadores comienzan a morir uno a uno en circunstancias misteriosas. A medida que se desarrollan los a… (494 caracteres)","popularity":67.8612,"poster_path":"/lJvZqB9wf23viJtnm0IDHFSUrhB.jpg","release_date":"2024-07-03","softcore":false,"video":false,"vote_average":7.708,"vote_count":72},{"adult":false,"backdrop_path":"/58D9nalUYW5L5K0guw7hcpsEJBH.jpg","genre_ids":[53,18,80],"id":1492640,"title":"Unabomber","original_language":"en","original_title":"UNABOMBER","overview":"Un estudiante de Harvard se convierte en 'Unabomber' tras someterse a una serie de experimentos psicológicos. Años más tarde, la investigación de un agente del FBI revela cómo su pasado determinó la campaña mortal que se cobró la vida de tres personas e hirió a otras veintitrés entre 1978 y 1995.","popularity":63.6429,"poster_path":"/crV6ba2FVfHW64PzjJehMxUj9e7.jpg","release_date":"2026-09-25","softcore":false,"video":false,"vote_average":6.6,"vote_count":405},{"adult":false,"backdrop_path":"/ejdD20cdHNFAYAN2DlqPToXKyzx.jpg","genre_ids":[18,80],"id":238,"title":"El padrino","original_language":"en","original_title":"The Godfather","overview":"Don Vito Corleone, conocido dentro de los círculos del hampa como \"El Padrino\", es el patriarca de una de las cinco familias que ejercen el mando de la Cosa Nostra en Nueva York (Estados Unidos) durante la década de 1940. Don Corleone tiene cuatro hijos: una chica, Connie, y tres varones; Sonny, Mic… (479 caracteres)","popularity":59.0144,"poster_path":"/5HlLUsmsv60cZVTzVns9ICZD6zU.jpg","release_date":"1972-03-14","softcore":false,"video":false,"vote_average":8.7,"vote_count":23727},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#19] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=36
+19.48s · s4 · status 200 · 873 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/y0reRTsewsPh0ePtgvDeLIsb5Wk.jpg","genre_ids":[36,18,28],"id":977942,"title":"El hombre que desafió al rey","original_language":"en","original_title":"The Uprising","overview":"En la Inglaterra del siglo XIV, asolada por la peste, un campesino desencadena una rebelión contra el rey Ricardo II y se convierte involuntariamente en una leyenda de la resistencia.","popularity":112.6194,"poster_path":"/rveEjlQQ0LlyyPk8ev2pHBmQPZZ.jpg","release_date":"2026-09-10","softcore":false,"video":false,"vote_average":7.9,"vote_count":271},{"adult":false,"backdrop_path":"/neeNHeXjMF5fXoCJRsOmkNGC7q.jpg","genre_ids":[18,36],"id":872585,"title":"Oppenheimer","original_language":"en","original_title":"Oppenheimer","overview":"Película sobre el físico J. Robert Oppenheimer y su papel como desarrollador de la bomba atómica. Basada en el libro 'American Prometheus: The Triumph and Tragedy of J. Robert Oppenheimer' de Kai Bird y Martin J. Sherwin.","popularity":55.1882,"poster_path":"/mJRUREPjTqqMEKwEiM2sdmIGngz.jpg","release_date":"2023-07-19","softcore":false,"video":false,"vote_average":8,"vote_count":12661},{"adult":false,"backdrop_path":"/wXTaGcqX3jvdXSKCJAkl5jZyrKp.jpg","genre_ids":[18,36,53],"id":1281331,"title":"El Precio de la Red","original_language":"en","original_title":"The Social Reckoning","overview":"Explora las prácticas internas de Facebook, la difusión de información falsa, el impacto en la salud mental de los adolescentes y la conexión con los eventos del 6 de enero en el Capitolio.","popularity":53.3617,"poster_path":"/xT7yxocpGjqzalCUTr9IFDf8Oyb.jpg","release_date":"2026-10-07","softcore":false,"video":false,"vote_average":7.438,"vote_count":40},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#20] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=10402
+19.63s · s4 · status 200 · 1021 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (14 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/ufSwlnECLoUbBjPrFqEQcWBzHwc.jpg","genre_ids":[10402,18],"id":936075,"title":"Michael","original_language":"en","original_title":"Michael","overview":"El viaje de Michael Jackson más allá de la música, desde el descubrimiento de su extraordinario talento como líder de los Jackson Five hasta convertirse en una visionaria estrella cuya ambición creativa despertó un incansable afán por consagrarse como el mayor icono de la industria del entretenimien… (303 caracteres)","popularity":56.7038,"poster_path":"/2uK36ujoDXOfNiJ5Yp3raVprB51.jpg","release_date":"2026-04-22","softcore":false,"video":false,"vote_average":8.613,"vote_count":4520},{"adult":false,"backdrop_path":"/g7CHF8gTLGooTbP4GznIGwaqAGL.jpg","genre_ids":[10751,16,10402,12],"id":354912,"title":"Coco","original_language":"en","original_title":"Coco","overview":"Un joven aspirante a músico llamado Miguel se embarca en un viaje extraordinario a la mágica tierra de sus ancestros. Allí, el encantador embaucador Héctor se convierte en su inesperado amigo y le ayuda a descubrir los misterios detrás de las historias y tradiciones de su familia.","popularity":56.2378,"poster_path":"/vwsFGblLYxWBNjg9pdWN1Mm5YfW.jpg","release_date":"2017-10-27","softcore":false,"video":false,"vote_average":8.199,"vote_count":21510},{"adult":false,"backdrop_path":"/fRGxZuo7jJUWQsVg9PREb98Aclp.jpg","genre_ids":[18,10402,53],"id":244786,"title":"Whiplash","original_language":"en","original_title":"Whiplash","overview":"El objetivo de Andrew Neiman, un joven y ambicioso baterista de jazz, es triunfar en el elitista Conservatorio de Música de la Costa Este en el que estudia. Marcado por el fracaso de la carrera literaria de su padre, Andrew alberga sueños de grandeza. Terence Fletcher, un profesor conocido tanto por… (698 caracteres)","popularity":39.9818,"poster_path":"/uy36CPy5ARuC8qrH8Esg2ndFyJ5.jpg","release_date":"2014-10-10","softcore":false,"video":false,"vote_average":8.4,"vote_count":17202},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#21] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=37
+19.64s · s4 · status 200 · 1028 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (17 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/2oZklIzUbvZXXzIFzv7Hi68d6xf.jpg","genre_ids":[18,37],"id":68718,"title":"Django desencadenado","original_language":"en","original_title":"Django Unchained","overview":"Dos años antes de estallar la Guerra Civil (1861-1865), Schultz, un cazarrecompensas alemán que le sigue la pista a unos asesinos, le promete al esclavo Django dejarlo en libertad si le ayuda a atraparlos. Terminado con éxito el trabajo, Django prefiere seguir al lado del alemán y ayudarle a captura… (751 caracteres)","popularity":37.3551,"poster_path":"/fIxAE6BKfAzhPRYm7DdldBaYu5T.jpg","release_date":"2012-12-25","softcore":false,"video":false,"vote_average":8.193,"vote_count":28742},{"adult":false,"backdrop_path":"/x4biAVdPVCghBlsVIzB6NmbghIz.jpg","genre_ids":[37],"id":429,"title":"El bueno, el feo y el malo","original_language":"it","original_title":"Il buono, il brutto, il cattivo","overview":"Durante la Guerra de Secesión, tres cazadores de recompensas se lanzan a la búsqueda de un tesoro que ninguno de los tres truhanes puede localizar sin la ayuda de los otros dos. Tuco sabe que el tesoro se encuentra en un cementerio, mientras que Joe conoce el nombre inscrito en la tumba que lo escon… (492 caracteres)","popularity":30.9775,"poster_path":"/71HKV5F9bfm05ZZnjGmRuFpUVCo.jpg","release_date":"1966-12-23","softcore":false,"video":false,"vote_average":8.5,"vote_count":10023},{"adult":false,"backdrop_path":"/gddUsvfyySrM5k8B8wwJy2VRlBx.jpg","genre_ids":[80,53,37],"id":6977,"title":"No es país para viejos","original_language":"en","original_title":"No Country for Old Men","overview":"El veterano de la Guerra de Vietnam ahora cazador Llewellyn Moss descubre por casualidad una sangrienta escena en algún lugar de la frontera entre Texas y México, mientras estaba cazando algunos animales en el árido paisaje. Se trata de un negocio que se cerró mal entre contrabandistas de drogas y a… (650 caracteres)","popularity":30.7455,"poster_path":"/x9sQnOXhvec93L6cfWMGIx7BS4h.jpg","release_date":"2007-11-09","softcore":false,"video":false,"vote_average":7.951,"vote_count":13881},"… (+17 elementos más)"],"total_pages":518,"total_results":10352}
```

### [#22] GET https://api.themoviedb.org/3/discover/movie?include_adult=false&include_video=true&language=es-ES&page=1&sort_by=popularity.desc&with_genres=99
+19.71s · s4 · status 200 · 1106 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (11 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/7Ud7QIJo21odjCaev6V4md9sK16.jpg","genre_ids":[99,10402],"id":1447853,"title":"Oasis: Don't Look Back in Anger","original_language":"en","original_title":"Oasis: Don't Look Back in Anger","overview":"Narra la gira de reunión de Liam y Noel Gallagher, \"Oasis Live ‘25\", uno de los regresos al rock más esperados. La película relata el acontecimiento musical de 2025, capturando tanto la experiencia de la banda como la de sus seguidores en todo el mundo. Esta perspectiva única incluye acceso a los en… (640 caracteres)","popularity":25.5717,"poster_path":"/5XoHhKZ1IROW6f5UlRpADHnTL2l.jpg","release_date":"2026-09-09","softcore":false,"video":false,"vote_average":7.6,"vote_count":23},{"adult":false,"backdrop_path":"/dUbP1HNdI0aCq1zgRJw28PWSqmk.jpg","genre_ids":[28,35,99],"id":1612018,"title":"Jackass: Lo mejor para el final","original_language":"en","original_title":"Jackass: Best and Last","overview":"Johnny Knoxville, Steve-O y el elenco clásico —junto a los integrantes más jóvenes— se reúnen por última vez en un formato que combina nuevas bromas y acrobacias extremas con escenas inéditas, descartes históricos y material de archivo. Acompañada de comentarios e intervenciones del director Jeff Tr… (441 caracteres)","popularity":19.9613,"poster_path":"/8sVomxZ7OBnjaHA0C8lAvSq1fr.jpg","release_date":"2026-06-25","softcore":false,"video":false,"vote_average":7.318,"vote_count":274},{"adult":false,"backdrop_path":"/yATuNOVifq933nYIqHX9LNp83Vx.jpg","genre_ids":[99],"id":1040159,"title":"My Massive Cock","original_language":"en","original_title":"My Massive Cock","overview":"","popularity":18.4283,"poster_path":"/wlvj1XbkHVItYE0ko4Xg4L08Ycj.jpg","release_date":"2022-10-24","softcore":false,"video":false,"vote_average":5.8,"vote_count":14},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#23] GET https://api.themoviedb.org/3/movie/969681/reviews?language=es-ES
+29.72s · s5 · status 200 · 396 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 17):
  content-type: application/json;charset=utf-8
Response body (69 B):
```json
{"id":969681,"page":1,"results":[],"total_pages":0,"total_results":0}
```

### [#24] GET https://api.themoviedb.org/3/movie/969681/similar?language=es-ES&page=1
+29.75s · s5 · status 200 · 425 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 17):
  content-type: application/json;charset=utf-8
Response body (15 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/49hriJp9Oop5Gu3pxeKzy3v2hgi.jpg","genre_ids":[28,80,18,53],"id":2076,"title":"The gang (Golpe perfecto)","original_language":"en","original_title":"Swindle","overview":"Seth (Tom Sizemore) es un policía encubierto que va tras la pista de unos delincuentes y consigue infiltrarse en la banda liderada por Sophie (Sherilyn Fenn), que planea el robo a un banco, del que Michael (Dave Foley) es director.","popularity":2.4761,"poster_path":"/8sx0hrhPZASfMLJaDYRw4hgouSU.jpg","release_date":"2002-04-01","softcore":false,"video":false,"vote_average":4.6,"vote_count":19},{"adult":false,"backdrop_path":"/p4GzAzjlL7lXIVGvayg7zvzGTSi.jpg","genre_ids":[12,28,878],"id":2080,"title":"X-Men orígenes: Lobezno","original_language":"en","original_title":"X-Men Origins: Wolverine","overview":"Narra los inicios del arma X y la forma en la que Wolverine se convirtió en mutante. Logan, convertido en un mutante que se hace llamar Lobezno, y que es capaz de sacar unas afiladas garras y de una fuerza y agilidad sobrehumana, ultima su venganza contra Victor Creed, culpable de la muerte de su no… (382 caracteres)","popularity":2.196,"poster_path":"/k2wFS6LAYDjOdSAtRc1Ey7roB4G.jpg","release_date":"2009-04-28","softcore":false,"video":false,"vote_average":6.299,"vote_count":11608},{"adult":false,"backdrop_path":"/5bYqpwhaKYaQdM31tsI67VxImc3.jpg","genre_ids":[28,12,14,878],"id":266037,"title":"Kamen Rider Wizard - La Película: En Tierra Mágica","original_language":"ja","original_title":"劇場版 仮面ライダーウィザード in Magic Land","overview":"Haruto va en busca de Koyomi quien ha sido secuestrada por un mago dorado, el cual desea crear un nuevo mundo a su semejanza. Parece ser que logra su cometido y ahora Haruto y Koyomi se encuentran en un mundo donde todas las personas tienen la capacidad de utilizar magia. Allí son reinados por un pe… (708 caracteres)","popularity":2.067,"poster_path":"/cX5iSQsCeLn1VfLWvSoAEwdTWJk.jpg","release_date":"2013-08-03","softcore":false,"video":false,"vote_average":5.7,"vote_count":11},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```

### [#25] GET https://api.themoviedb.org/3/movie/969681&append_to_response=images?language=es-ES
+29.79s · s5 · status 200 · 462 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (2.0 KB, arrays/textos largos recortados):
```json
{"adult":false,"backdrop_path":"/4tjxYg2AbOzzG9G1YuiT2NzYhlH.jpg","belongs_to_collection":{"id":531241,"name":"Spider-Man (Vengadores) - Colección","poster_path":"/2E7Jukg8JvyJgKlql7UIWqVwOMU.jpg","backdrop_path":"/AvnqpRwlEaYNVL6wzC4RN94EdSd.jpg"},"budget":225000000,"genres":[{"id":878,"name":"Ciencia ficción"},{"id":28,"name":"Acción"},{"id":12,"name":"Aventura"}],"homepage":"","id":969681,"imdb_id":"tt22084616","origin_country":["US"],"original_language":"en","original_title":"Spider-Man: Brand New Day","overview":"Han pasado cuatro años desde los acontecimientos de No Way Home, y Peter Parker ahora es un adulto que vive completamente solo, ha desaparecido voluntariamente de las vidas y recuerdos de quienes ama. Combatiendo el crimen en una Nueva York que ya no conoce su nombre, se ha dedicado por completo a p… (603 caracteres)","popularity":942.3201,"poster_path":"/9g0sEFhmvmK4nGhXj8DHuv2noYI.jpg","production_companies":[{"id":420,"logo_path":"/hUzeosd33nzE5MCNsZxCGEKTXaQ.png","name":"Marvel Studios","origin_country":"US"},{"id":5,"logo_path":"/71BqEFAF4V3qjjMPCpLuyJFB9A.png","name":"Columbia Pictures","origin_country":"US"},{"id":84041,"logo_path":"/nw4kyc29QRpNtFbdsBHkRSFavvt.png","name":"Pascal Pictures","origin_country":"US"},{"id":22213,"logo_path":"/qx9K6bFWJupwde0xQDwOvXkOaL8.png","name":"TSG Entertainment","origin_country":"US"}],"production_countries":[{"iso_3166_1":"US","name":"United States of America"}],"release_date":"2026-07-29","revenue":2505477000,"runtime":145,"softcore":false,"spoken_languages":[{"english_name":"English","iso_639_1":"en","name":"English"}],"status":"Released","tagline":"Un nuevo día comienza ahora.","title":"Spider-Man: Brand New Day","video":false,"vote_average":8.38,"vote_count":4758}
```

### [#26] GET https://api.themoviedb.org/3/movie/969681/credits?language=es-ES
+30.10s · s5 · status 200 · 774 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 17):
  content-type: application/json;charset=utf-8
Response body (100 KB, arrays/textos largos recortados):
```json
{"id":969681,"cast":[{"adult":false,"gender":2,"id":1136406,"known_for_department":"Acting","name":"Tom Holland","original_name":"Tom Holland","popularity":21.4881,"profile_path":"/adwEBb2sCSzqwnpVgNEG7irl1Ne.jpg","cast_id":4,"character":"Peter Parker / Spider-Man","credit_id":"630cbd43ede1b00083c3badf","order":0},{"adult":false,"gender":1,"id":1590797,"known_for_department":"Acting","name":"Sadie Sink","original_name":"Sadie Sink","popularity":15.2839,"profile_path":"/92FddzBfK50XOUbtwjqHPraoGHy.jpg","cast_id":30,"character":"Jean Grey","credit_id":"67d1c1557761a3a68f60db95","order":1},{"adult":false,"gender":2,"id":2028037,"known_for_department":"Acting","name":"Tramell Tillman","original_name":"Tramell Tillman","popularity":3.4551,"profile_path":"/bEA15zMnkcXlRroYjKrFUWiiK7y.jpg","cast_id":72,"character":"William 'Bill' Metzger","credit_id":"68a63cb7af8882c8675dd68b","order":2},"… (+56 elementos más)"],"crew":[{"adult":false,"gender":2,"id":10850,"known_for_department":"Production","name":"Kevin Feige","original_name":"Kevin Feige","popularity":3.2338,"profile_path":"/kCBqXZ5PT5udYGEj2wfTSFbLMvT.jpg","credit_id":"628d559ed48cee2cbfca858a","department":"Production","job":"Producer"},{"adult":false,"gender":1,"id":1425616,"known_for_department":"Production","name":"Amy Pascal","original_name":"Amy Pascal","popularity":1.2907,"profile_path":"/cZ526e4oPN1i44Q0BxYW8nOtrzR.jpg","credit_id":"65e51be61ad93b01860898a0","department":"Production","job":"Producer"},{"adult":false,"gender":2,"id":57027,"known_for_department":"Production","name":"Louis D'Esposito","original_name":"Louis D'Esposito","popularity":2.1495,"profile_path":"/ewtzT2ZMIX2DNyGUUkHLn36fjgF.jpg","credit_id":"641a69d3688cd0010c5f38d8","department":"Production","job":"Executive Producer"},"… (+321 elementos más)"]}
```

### [#27] GET https://api.themoviedb.org/3/search/movie?query=Jackie&include_adult=false&language=es-ES&page=1
+82.10s · s6 · status 200 · 376 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (8.5 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/gvaeY5kz3wHrMU6xLdnybziwYXw.jpg","genre_ids":[80,18,53],"id":184,"title":"Jackie Brown","original_language":"en","original_title":"Jackie Brown","overview":"Jackie Brown es una azafata de vuelo que necesita dinero y hace de correo para Robbie, un mafioso buscado por la policía. Todo parece ir bien hasta que un día es sorprendida en la aduana y acusada de tráfico de drogas y evasión de capital. Sólo podrá evitar su ingreso en prisión, si acepta una propu… (352 caracteres)","popularity":13.8841,"poster_path":"/vNrJ3ODvu2dvqIdHHbzgsVjgp4X.jpg","release_date":"1997-12-25","softcore":false,"video":false,"vote_average":7.358,"vote_count":7160},{"adult":false,"backdrop_path":"/lF41LYBSLVpZ61rZci471pqi6UW.jpg","genre_ids":[18],"id":376866,"title":"Jackie","original_language":"en","original_title":"Jackie","overview":"Película sobre la exprimera dama estadounidense Jacqueline Kennedy, centrada en los días inmediatamente posteriores al asesinato de JFK, en Dallas, el 22 de noviembre del año 1963.","popularity":4.9575,"poster_path":"/hxmIRglqQMNb9A6NLQt5zCO39N7.jpg","release_date":"2016-12-02","softcore":false,"video":false,"vote_average":6.449,"vote_count":2477},{"adult":false,"backdrop_path":"/nNG4BdYO4kexeQ4N5lgEtpOnYBh.jpg","genre_ids":[35],"id":1693983,"title":"Jackie the Stripper","original_language":"en","original_title":"Jackie the Stripper","overview":"","popularity":4.2602,"poster_path":"/eyFW5SanGL2I86CfxxhszmQiG9k.jpg","release_date":"2026-07-02","softcore":false,"video":false,"vote_average":4,"vote_count":1},"… (+17 elementos más)"],"total_pages":12,"total_results":229}
```

### [#28] GET https://api.themoviedb.org/3/movie/1712451&append_to_response=images?language=es-ES
+251.64s · s13 · status 200 · 679 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (1.0 KB):
```json
{"adult":false,"backdrop_path":"/yKx5gYrYgakKZuUWAsuFDStBroy.jpg","belongs_to_collection":null,"budget":0,"genres":[{"id":27,"name":"Terror"}],"homepage":"","id":1712451,"imdb_id":"tt43640339","origin_country":["US"],"original_language":"en","original_title":"Resident Dead","overview":"Un padre lucha contra un ejercito de no-muertos junto a su hija, gravemente herida, para llegar a la cura antes de que ella se transforme. Si logra llegar al laboratorio con la vacuna a tiempo, cree que su hija estará a salvo. Lamentablemente, el desafío más horrible lo espera en su destino final.","popularity":179.573,"poster_path":"/yX8ziNTZ5aOszJ3l4R3BlT2gBIa.jpg","production_companies":[{"id":1311,"logo_path":"/ic2bTizdzRLDVzAvN7MXdUg3WQV.png","name":"The Asylum","origin_country":"US"}],"production_countries":[{"iso_3166_1":"US","name":"United States of America"}],"release_date":"2026-09-04","revenue":0,"runtime":86,"softcore":false,"spoken_languages":[],"status":"Released","tagline":"","title":"Dead Residents Evil","video":false,"vote_average":5.929,"vote_count":7}
```

### [#29] GET https://api.themoviedb.org/3/movie/1712451/credits?language=es-ES
+251.64s · s13 · status 200 · 684 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 21):
  content-type: application/json;charset=utf-8
Response body (7.5 KB, arrays/textos largos recortados):
```json
{"id":1712451,"cast":[{"adult":false,"gender":2,"id":1387577,"known_for_department":"Acting","name":"John Wells","original_name":"John Wells","popularity":0.9084,"profile_path":"/udDheh1OOGggBFQm56N5QSdrc6q.jpg","cast_id":6,"character":"Joe","credit_id":"6a7fc9666dbb461570393b6d","order":0},{"adult":false,"gender":0,"id":4158959,"known_for_department":"Art","name":"Isabel Ramirez","original_name":"Isabel Ramirez","popularity":0.8991,"profile_path":"/wVyHo6XE3o3QbeiftOF0bgIfhcU.jpg","cast_id":10,"character":"Ashley","credit_id":"6a89d356ff159b9c5dbc5a8b","order":1},{"adult":false,"gender":0,"id":5337173,"known_for_department":"Acting","name":"Thandiwe McMillan","original_name":"Thandiwe McMillan","popularity":0.9878,"profile_path":"/mr5BEL2guLAYOuXJyreNziKtwfV.jpg","cast_id":7,"character":"Dawn","credit_id":"6a7fc9a9fa0e1c226fc93236","order":2},"… (+6 elementos más)"],"crew":[{"adult":false,"gender":2,"id":2427740,"known_for_department":"Writing","name":"Ryan Ebert","original_name":"Ryan Ebert","popularity":1.0762,"profile_path":"/7TWzBqJY7KkM9PoJBENXSMxzLut.jpg","credit_id":"6a2a5644e6be46337d8eab9d","department":"Directing","job":"Director"},{"adult":false,"gender":2,"id":2427740,"known_for_department":"Writing","name":"Ryan Ebert","original_name":"Ryan Ebert","popularity":1.0762,"profile_path":"/7TWzBqJY7KkM9PoJBENXSMxzLut.jpg","credit_id":"6a2a5650a3f83897ee50e555","department":"Writing","job":"Writer"},{"adult":false,"gender":2,"id":30053,"known_for_department":"Production","name":"David Michael Latt","original_name":"David Michael Latt","popularity":0.8868,"profile_path":"/cBkmGgFkGFFyyE6aWDYovvaHL0g.jpg","credit_id":"6a2a566e0c09eef07aefd787","department":"Production","job":"Producer"},"… (+16 elementos más)"]}
```

### [#30] GET https://api.themoviedb.org/3/movie/1712451/reviews?language=es-ES
+251.72s · s13 · status 200 · 759 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 17):
  content-type: application/json;charset=utf-8
Response body (70 B):
```json
{"id":1712451,"page":1,"results":[],"total_pages":0,"total_results":0}
```

### [#31] GET https://api.themoviedb.org/3/movie/1712451/similar?language=es-ES&page=1
+251.74s · s13 · status 200 · 786 ms
Request headers:
  Accept: application/json
  Content-Type: application/json
  Authorization: [REDACTED]
Response headers (relevantes: 1 de 17):
  content-type: application/json;charset=utf-8
Response body (13 KB, arrays/textos largos recortados):
```json
{"page":1,"results":[{"adult":false,"backdrop_path":"/5UX6M0aEphiW6Xmy5rpYX75glbo.jpg","genre_ids":[14,27,35],"id":927,"title":"Gremlins","original_language":"en","original_title":"Gremlins","overview":"Rand es un viajante que un día regala a su hijo Billy una tierna y extraña criatura, un mogwai. El inocente regalo, sin embargo, será el origen de toda una ola de gamberradas y fechorías en un pequeño pueblo de Estados Unidos. Todo empieza cuando son infringidas, una tras otra, las tres reglas básic… (433 caracteres)","popularity":15.0645,"poster_path":"/73Lf0JYHyWyZQGu04wvzzM3hh0l.jpg","release_date":"1984-06-08","softcore":false,"video":false,"vote_average":7.146,"vote_count":7191},{"adult":false,"backdrop_path":"/8WIufsaJgm7VWgAc5ALWdJ8v2kB.jpg","genre_ids":[14,27,35],"id":766,"title":"El ejército de las tinieblas","original_language":"en","original_title":"Army of Darkness","overview":"Inglaterra, siglo XIII. Las fuerzas del mal ejercen su reinado en la Edad Media. Valerosos caballeros se disponen a entrar en desigual batalla, mientras que los atemorizados campesinos se refugian tras los muros del castillo. Todo cambia con la inesperada llegada de un nuevo héroe, provisto de sofis… (346 caracteres)","popularity":14.4303,"poster_path":"/aWko0iXOEbqvWZa8NVKrUbBMJYy.jpg","release_date":"1992-10-31","softcore":false,"video":false,"vote_average":7.258,"vote_count":3709},{"adult":false,"backdrop_path":"/2eZUHO2gEktRTaWQuxXF3NtLWjH.jpg","genre_ids":[27,878,28],"id":460962,"title":"Alien Convergence","original_language":"en","original_title":"Alien Convergence","overview":"Cuando una serie de alienígenas reptilianos toma control del mundo, los supervivientes que quedan deben hacer piña para enfrentarse a ellos. Mockbuster de Asylum lanzado a rebufo de \"Alien: Covenant\" de Ridley Scott.","popularity":2.1398,"poster_path":"/p4c6HeYIV5ARX33hWmqbeBGj1lW.jpg","release_date":"2017-06-27","softcore":false,"video":false,"vote_average":3.8,"vote_count":54},"… (+17 elementos más)"],"total_pages":1001,"total_results":20001}
```


## Errores

### +239.46s · s9 · contexto: FlutterError  [img: screens/10_t239.5s_error_s9.jpg]
Bad state: Error de prueba al abrir detalle desde Favoritos: Spider-Man: Brand New Day
```
#0      _FavoritesScreenState._buildList.<anonymous closure>.<anonymous closure> (package:imdumb/features/profile/presentation/screens/favorites_screen.dart:111:13)
… (15 frames de Flutter/Dart omitidos)
```

### +245.17s · s11 · contexto: FlutterError  [img: screens/13_t245.2s_error_s11.jpg]
Bad state: Error de prueba al abrir detalle desde Favoritos: Spider-Man: Brand New Day
```
#0      _FavoritesScreenState._buildList.<anonymous closure>.<anonymous closure> (package:imdumb/features/profile/presentation/screens/favorites_screen.dart:111:13)
… (15 frames de Flutter/Dart omitidos)
```

## Capturas incluidas

- screens/01_t2.1s_pantalla_s1.jpg — +2.14s · pantalla · s1 (último estado capturado de la pantalla)
- screens/02_t4.3s_pantalla_s2.jpg — +4.25s · pantalla · s2 (último estado capturado de la pantalla)
- screens/03_t10.3s_pantalla_s3.jpg — +10.34s · pantalla · s3 (último estado capturado de la pantalla)
- screens/04_t19.2s_pantalla_s4.jpg — +19.21s · pantalla · s4 (último estado capturado de la pantalla)
- screens/05_t30.9s_pantalla_s5.jpg — +30.87s · pantalla · s5 (último estado capturado de la pantalla)
- screens/06_t38.4s_pantalla_s6.jpg — +38.35s · pantalla · s6 (último estado capturado de la pantalla)
- screens/07_t118.8s_pantalla_s7.jpg — +118.81s · pantalla · s7 (último estado capturado de la pantalla)
- screens/08_t120.0s_pantalla_s8.jpg — +119.99s · pantalla · s8 (último estado capturado de la pantalla)
- screens/09_t134.1s_pantalla_s9.jpg — +134.10s · pantalla · s9 (último estado capturado de la pantalla)
- screens/10_t239.5s_error_s9.jpg — +239.46s · error · s9
- screens/11_t244.2s_pantalla_s10.jpg — +244.17s · pantalla · s10 (último estado capturado de la pantalla)
- screens/12_t244.6s_pantalla_s11.jpg — +244.60s · pantalla · s11 (último estado capturado de la pantalla)
- screens/13_t245.2s_error_s11.jpg — +245.17s · error · s11
- screens/14_t249.8s_pantalla_s12.jpg — +249.78s · pantalla · s12 (último estado capturado de la pantalla)
- screens/15_t252.2s_pantalla_s13.jpg — +252.21s · pantalla · s13 (último estado capturado de la pantalla)
- screens/16_t256.4s_pantalla_s14.jpg — +256.41s · pantalla · s14 (último estado capturado de la pantalla)
- screens/17_t259.7s_pantalla_s15.jpg — +259.74s · pantalla · s15 (último estado capturado de la pantalla)
- screens/18_t260.2s_pantalla_s16.jpg — +260.18s · pantalla · s16 (último estado capturado de la pantalla)
