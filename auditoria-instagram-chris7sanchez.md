# Auditoría de perfil — @chris7sanchez

**v2 — con datos reales de Instagram Insights** (vía conector Supermetrics, cuenta
`17841401167513288`). Sustituye a la v1, que estaba construida sobre hipótesis y era
incorrecta en sus dos conclusiones principales.

Ventana disponible en la API: 2024-09-07 → 2026-09-06. Consultado el 2026-09-06.

---

## El hallazgo que anula todo lo demás

**11 publicaciones en 24 meses. La última, el 3 de noviembre de 2025. 10 meses de silencio.**

En los últimos 12 meses: 2 publicaciones.

No hay una estrategia que auditar. La frustración declarada ("nunca consigo mantenerlo, aunque
lo he hecho a temporadas") describe mal el problema: esto no son temporadas, es una cuenta
apagada con destellos ocasionales.

### Alcance mensual de la cuenta

| Periodo | Alcance medio/mes |
|---|---|
| sep 2024 – nov 2025 (con actividad) | 20.313 |
| jun – ago 2026 (últimos 3 meses) | 2.774 |
| **Variación** | **−86%** |

Detalle importante: **no cayó de golpe**. Tras el último post (nov-2025) el alcance aguantó
entre 12.000 y 17.000/mes hasta mayo de 2026 — unos 6 meses de inercia — y colapsó en junio
(2.464). La gracia se ha consumido. A partir de aquí cada mes de silencio cuesta más caro.

```
2024-09  20.785        2025-09  14.341
2024-10  15.259        2025-10  15.448
2024-11  15.582        2025-11   7.778  <- último post: 3-nov-2025
2024-12  25.278        2025-12  11.944
2025-01  17.254        2026-01  12.058
2025-02  20.026        2026-02   8.532
2025-03  14.487        2026-03  17.246
2025-04  24.796        2026-04   6.140
2025-05  32.142        2026-05  12.878
2025-06  16.606        2026-06   2.464  <- fin de la inercia
2025-07  12.636        2026-07   3.294
2025-08  52.280        2026-08   2.563
```

---

## Dónde se fue el trabajo: las Stories

Métrica `profile_views` (visualizaciones de contenido: reels + posts + stories). Disponible
desde ago-2025:

| Mes | Views de contenido | Posts publicados ese mes |
|---|---|---|
| 2025-08 | 51.320 | 1 |
| 2025-09 | **218.035** | **0** |
| 2025-10 | 98.701 | 1 |
| 2025-11 | 125.540 | 1 |
| 2025-12 | 126.764 | 0 |
| 2026-01 | 113.238 | 0 |
| 2026-02 | 39.739 | 0 |
| 2026-03 | 46.642 | 0 |
| 2026-04 | 21.531 | 0 |
| 2026-05 | 41.209 | 0 |
| 2026-06 | 9.276 | 0 |
| 2026-07 | 13.784 | 0 |
| 2026-08 | 15.509 | 0 |

[Probable, por exclusión] 218.035 visualizaciones en un mes con cero publicaciones sólo puede
ser Stories. Durante meses se generaron 100.000–200.000 visualizaciones mensuales en el único
formato que **caduca en 24 h, no llega a no-seguidores, no se indexa, no se puede enseñar a una
marca y no se puede volver a ver**.

El hallazgo más caro de la auditoría: no es que no hubiera trabajo. Es que todo el trabajo fue
al formato que no capitaliza.

---

## Rendimiento por publicación (11 posts, 24 meses)

| Fecha | Tipo | Views | Alcance | Guardados | Compartidos | Likes | Comentarios |
|---|---|---|---|---|---|---|---|
| 2025-10-31 | FEED | 61.795 | 15.935 | 60 | 20 | 1.406 | 50 |
| 2025-06-18 | FEED | 46.956 | 10.821 | 21 | 11 | 843 | 19 |
| 2024-12-22 | FEED | 42.947 | 12.268 | 49 | 2 | 1.822 | 84 |
| 2024-12-25 | REELS | 18.662 | 12.373 | 14 | 18 | 536 | 48 |
| 2025-08-12 | REELS | 17.517 | 9.947 | 9 | 4 | 876 | 130 |
| 2025-02-21 | REELS | 15.926 | 10.677 | 20 | 0 | 620 | 24 |
| 2025-07-03 | REELS | 15.494 | 8.916 | 8 | 4 | 681 | 60 |
| 2024-09-19 | REELS | 11.379 | 5.014 | 11 | 0 | 528 | 28 |
| 2025-11-03 | REELS | 4.733 | 3.636 | 6 | 10 | 225 | 21 |
| 2025-07-03 | REELS | 332 | 293 | 0 | 0 | 1 | 0 |
| 2025-02-03 | REELS | 101 | 124 | 2 | 0 | 8 | 0 |

### Feed gana a Reels, y por mucho

| Tipo | Nº | Alcance medio | Views medias |
|---|---|---|---|
| FEED (foto/carrusel) | 3 | **13.008** | 50.566 |
| REELS | 8 | 6.373 | 10.518 |

**Tu feed alcanza el doble de gente que tus reels.** Las "views" no se miden igual en ambos
formatos, así que la comparación buena es el alcance: 13.008 vs 6.373. Esto contradice el
consejo estándar de "todo a reels" y es específico de esta cuenta.

Nota operativa: el 3-jul-2025 se publicaron dos reels con 70 minutos de diferencia. El segundo
hizo 332 views frente a 15.494 del primero. Canibalización total.

---

## El número que explica por qué no hay dinero

**200 guardados y 69 compartidos en 24 meses.**

El mejor post de los dos años: 61.795 views, 1.406 me gusta, **60 guardados**.

- 23 me gusta por cada guardado
- Guardados / alcance = 0,38%
- Compartidos / alcance = 0,13%

Contenido que **gusta** pero no **sirve**. Los me gusta no se monetizan: son un aplauso.
Los guardados y los compartidos sí, porque son la señal de que alguien vuelve y de que alguien
te enseña a un tercero. Ese es el motivo real por el que 65.000 seguidores no se convierten en
ingreso, y no tiene nada que ver con la bio.

**La otra cara:** el engagement por alcance del mejor post es del 9,6% y sobre seguidores del
2,4%. Eso es bueno para 65K. La cuenta no está rota — está apagada.

---

## Audiencia

### Países (top 15 de 64.899 seguidores)

| País | Seguidores | % |
|---|---|---|
| España | 30.060 | 46,3% |
| México | 4.828 | 7,4% |
| EE. UU. | 2.443 | 3,8% |
| Argentina | 1.010 | 1,6% |
| Colombia | 960 | 1,5% |
| Brasil | 907 | 1,4% |
| Italia | 644 | 1,0% |
| Ecuador | 623 | 1,0% |
| Perú | 622 | 1,0% |
| Chile | 566 | 0,9% |
| **Taiwán** | **502** | **0,8%** |
| Venezuela | 496 | 0,8% |
| Rep. Dominicana | 377 | 0,6% |
| Paraguay | 283 | 0,4% |
| Guatemala | 265 | 0,4% |

**Corrección de la v1:** la hipótesis de que LatAm dominara la audiencia era falsa. LatAm
hispanohablante suma ~11.300 (17,5%). España es el 46,3%. **Eres perfectamente vendible a una
marca española.**

**Lo que sí hay que mirar:** el top 40 de países sólo suma 48.110 de 64.899. El 26% restante
(~16.800) está repartido en una cola larguísima de países con menos de 79 seguidores cada uno.
Y dentro del top 40 aparecen Taiwán (502, puesto 11, por encima de Venezuela), Nigeria (198),
India (148), Indonesia (147), Irak (117), Vietnam (108), China (90). Además, 15.165 seguidores
(23%) no tienen datos demográficos asignados.

[Probable] Hay un colchón relevante de cuentas inactivas o de baja calidad acumuladas en 15
años. Infla el número de seguidores y hunde el engagement rate — que es exactamente la métrica
que mira un brand manager antes de escribir.

### Edad y género (de los 49.734 clasificados)

| Edad | Total | % |
|---|---|---|
| 25-34 | 20.033 | 40,3% |
| 35-44 | 16.008 | 32,2% |
| 45-54 | 6.738 | 13,5% |
| 18-24 | 4.337 | 8,7% |
| 55-64 | 1.912 | 3,8% |
| 65+ | 603 | 1,2% |
| 13-17 | 103 | 0,2% |

**25-44 = 72,5%.** Adultos con poder adquisitivo. Género: 61% mujeres / 39% hombres entre los
identificados.

Es una audiencia buena. Mejor de lo que probablemente crees.

### Crecimiento actual

184 seguidores nuevos en los últimos 30 días (~6/día) **sin publicar nada**. Es inercia de la
carrera, no crecimiento. Aviso: la API sólo da altas, no bajas — el neto puede ser plano o
negativo.

---

## La bio actual, destripada

```
Actor, director y a veces granuja.
Me as a photographer: @chrisXgraphy
Tiktok: @chris7sanchez
```
Web: `http://www.christian-sanchez.es/`

Tres líneas, tres fugas:

1. **"Actor, director y a veces granuja"** — identidad + chiste. Cero promesa. Ni una palabra
   sobre qué recibe quien te sigue.
2. **"Me as a photographer: @chrisXgraphy"** — en inglés, para una audiencia 46% española. Y
   manda tráfico a una segunda cuenta tuya: partes tu audiencia entre dos perfiles y ninguno
   alcanza masa crítica.
3. **"Tiktok: @chris7sanchez"** — [Probable] Instagram autoenlaza las @menciones de la bio a
   **cuentas de Instagram**. Esa línea es un enlace a tu propio perfil: el visitante hace clic
   y vuelve donde ya estaba. Es un error funcional, no de estilo.

Dicho esto: **la bio no está en el top 3 de problemas.** Con 11 posts en 24 meses casi nadie
llega a leerla.

---

## Los 3 errores más graves (revisados, con datos)

1. **No publicas.** 11 posts en 24 meses, 10 meses sin nada. Todo lo demás es secundario.
2. **El esfuerzo se fue a Stories.** 100.000–200.000 visualizaciones mensuales en formato que
   caduca, no descubre y no se vende.
3. **Contenido de simpatía, no de utilidad.** 200 guardados en dos años. Los likes no pagan.

La bio rota, los destacados y el nicho no entran en el top 3. Son optimizaciones de conversión
sobre un tráfico que hoy es de 2.500 personas al mes.

---

## Lo que sí funciona y hay que conservar

- **La capacidad está intacta.** Un solo post (31-oct-2025) hizo 61.795 views y 15.935 de
  alcance con la cuenta ya medio dormida. No tienes un problema de contenido.
- **El feed rinde el doble que los reels.** Es tu ventaja y no la estás usando.
- **La audiencia es buena y vendible:** 46% España, 72,5% entre 25 y 44 años.
- **Engagement sano:** 9,6% sobre alcance en el mejor post.
- **Autoridad verificable** (Wikipedia, IMDb, FilmAffinity, Prime Video). No se fabrica.

---

## La única acción de esta semana

**Publicar en el feed. Cuatro veces. Formato foto o carrusel, no reel.**

Por qué esto y no otra cosa:

- Tu cuenta acabó de tocar suelo (2.563 de alcance en agosto frente a 20.313 de media
  histórica). Los 6 meses de inercia ya se han gastado.
- La capacidad está demostrada: 61.795 views con un post.
- El feed te da 2x el alcance de los reels.
- Es lo único que revierte el error nº1, que causa los otros dos.

**Lo que NO debes hacer esta semana:** reescribir la bio, rehacer destacados, definir tu nicho,
montar un media kit. Todo eso lo recomendé en la v1 y todo eso es prematuro. Optimizar la
conversión de un tráfico de 2.500 personas al mes es optimizar cero.

### Orden posterior

- **Mes 1:** 12 publicaciones de feed. Mismo formato reconocible. Métrica de control:
  **guardados**, no me gusta. Objetivo: pasar de 0,38% a >2% de guardados sobre alcance.
- **Mes 2:** con los datos del mes 1, decidir formato definitivo → reescribir bio y destacados
  sobre lo que los datos digan, no sobre intuición. Arreglar el enlace roto de la bio.
- **Mes 3:** limpieza de seguidores inactivos si el engagement rate sigue penalizado, y
  primer contacto con marcas usando alcance y guardados, nunca el número de seguidores.

---

## Pendiente / limitaciones de los datos

- La API de Instagram Insights sólo llega a **2024-09-07**. No hay forma de comparar con las
  "temporadas buenas" anteriores.
- `follower_count` sólo cubre 30 días y sólo da altas, no bajas. El crecimiento neto real es
  desconocido.
- Las Stories históricas no son recuperables (expiran); su peso está inferido por exclusión
  a partir de `profile_views` en meses sin publicaciones.
- Los destacados y el orden del feed no son accesibles por API: siguen pendientes de captura.
