# Ilustraciones y monstruitos

## Estilo de ilustración

Las ilustraciones de Kangoo se generan con **ChatGPT** (otras herramientas no logran el estilo). Referencias oficiales en `assets/ilustraciones/`:

- `registro-familia.webp`: la familia y la cuidadora en el living (la referencia principal de personajes).
- `login.webp`: el niño y la niña.
- `registro-cuidadora.webp`: escena de la cuidadora.

Rasgos del estilo: ilustración digital pictórica y cálida, bordes suaves, luz dorada de atardecer, paleta ámbar y miel, livings acogedores con plantas, cuadros, lámparas y alfombra crema, caras alegres con mejillas rosadas y ojos expresivos. **Sin texto ni logos dentro de la imagen.**

## Personajes fijos

Se repiten siempre con la misma ropa, para que Kangoo tenga una familia reconocible:

| Personaje | Cómo es |
|---|---|
| **Cuidadora** | Veintitantos, pelo castaño oscuro largo y ondulado, sweater de lana trenzado color crema, jeans azules doblados abajo, zapatillas blancas |
| **Mamá** | Pelo castaño oscuro largo y liso, cárdigan terracota sobre polera blanca, jeans azules |
| **Papá** | Pelo corto oscuro, barba corta, polera verde petróleo, jeans |
| **Niño** (~4 años) | Pelo oscuro corto, polera azul verdosa, pantalón beige |
| **Niña** (~3 años) | Pelo oscuro con colita, polera rosada, jeans |

## Los monstruitos

Tres mascotas que aparecen en el sitio y el portal, a veces como peluches dentro de las ilustraciones. Referencia: `assets/monstruitos/mascotas-fiesta-quietas.webp`.

| Monstruito | Cómo es | Nivel de cuidadora que representa |
|---|---|---|
| **Verde** | Cuerpo alto tipo gomita, cresta naranja con puntas, dientecitos | Kangoo Brote |
| **Morado** | Cuerpo delgado tipo gato, orejas redondas y dos antenitas, guatita lila. **No es un oso. No tiene brazos.** | Kangoo Vuelo |
| **Amarillo** | Jirafa-dinosaurio de cuello largo, manchas y cresta naranjas | Kangoo Nido |

Archivos: `verde.webp`, `morado.webp`, `amarillo.webp` (para web), `*-hd.png` (alta resolución, fondo transparente), y escenas fijas `bienvenida-familia-estatico.webp`, `bienvenida-cuidadora-estatico.webp`, `revision-estatico.webp`.

No les cambies la forma, los colores ni las proporciones. Si una pieza necesita una pose nueva, pídela al equipo.

## Prompt base para ChatGPT

Adjunta `assets/ilustraciones/registro-familia.webp` (estilo y personajes) y `assets/monstruitos/mascotas-fiesta-quietas.webp`, y empieza el prompt con:

```
Create a new illustration in exactly the same art style, rendering quality and lighting as the first attached image: warm painterly digital illustration, soft blended edges, glowing golden-hour light, amber and honey palette, cozy detailed home interior with plants, framed pictures, warm lamps and a cream shaggy rug, joyful faces with rosy cheeks and expressive eyes. Characters must be the SAME people as in the reference, with the SAME faces, hair and clothes. If the Kangoo plush monsters appear, draw them exactly as in the second attached image: GREEN (tall gumdrop body, orange spiky crest, small teeth), PURPLE (slim cat-like body, small round ears and two tiny antenna nubs, lavender belly; NOT a teddy bear, no arms), YELLOW (long-necked giraffe-dinosaur with orange spots and crest). No text, no letters, no logos.
Scene: [describe la escena]
```

Una imagen por conversación da resultados más consistentes.
