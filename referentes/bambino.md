> **Nota para marketing:** análisis interno del 2026-10-01. Los datos sobre Bambino no están verificados con fuentes, y la columna "Kangoo hoy" quedó desactualizada (Kangoo ya verifica identidad con carnet y selfie). Úsalo como inspiración, no como dato para publicar.

# Análisis de Bambino — referente de recomendaciones comunitarias

**Fecha:** 2026-10-01 (documento original: "Análisis de Bambino Oct 2026")
**Pregunta que responde:** ¿Cómo valida Bambino a sus cuidadoras y cómo usa las recomendaciones de la comunidad, y qué le sirve a Kangoo?
**Fuente:** documento entregado por Alonso (`analisis-bambino-2026-10.docx`, misma carpeta). **No trae fuentes citadas ni fecha de consulta** → los datos sobre Bambino, Stripe Identity, Checkr y Family Watchdog se tratan como **no verificados** hasta confirmarlos con búsqueda web (`DERIVACION-INVESTIGACION.md`).
**Por qué importa:** Bambino funciona muy parecido a como Kangoo quiere funcionar: la confianza nace de recomendaciones de personas cercanas, no de algoritmos.

---

## 1. Verificación de la cuidadora (según el documento)

| Capa | Cómo lo hace Bambino | Equivalente en Kangoo hoy |
|---|---|---|
| Identidad | Stripe Identity: foto del documento + selfie en vivo (prueba de vida), análisis de falsificación, comparación biométrica. La app no guarda el carnet ni la selfie | Foto del carnet revisada a mano por la admin. Evaluación de biometría pendiente: tarea 13 (Didit) |
| Teléfono | Valida que el celular sea real; bloquea números virtuales, temporales o desechables | No existe |
| Listas de seguridad | Revisa bases de delincuentes sexuales y listas de vigilancia (Family Watchdog) | Certificado de antecedentes e inhabilidades, revisados a mano |
| Recomendación comunitaria | **Obligatoria:** ninguna niñera acepta trabajos sin al menos una recomendación positiva de un padre o madre de su red | Obligatoria para "perfil completo", pero hoy basta con que exista (aunque esté pendiente o rechazada) |
| Antecedentes avanzados | Opcional y pagado por la cuidadora (Checkr); al aprobar obtiene una insignia | No existe |

## 2. Perfil de la cuidadora (según el documento)

Arriba del todo: foto, nombre y nivel (Junior, Standard, Advanced, Elite). Justo debajo, tres datos:

1. **Tarifa por hora.**
2. **Promedio de estrellas** de las opiniones de otros padres.
3. **Conexiones en común:** si la cuidadora ya trabajó con amigos o vecinos del usuario (sincroniza contactos del teléfono).

El perfil solo queda activo con al menos una recomendación inicial.

## 3. Cómo pedir recomendaciones humanas (tips del documento)

- Sustituir el "escribe tu reseña" en blanco por **preguntas guía**:
  - "¿Qué fue lo que más les gustó a tus hijos de estar con ella?"
  - "Cuéntanos un detalle o momento que te haya hecho sentir seguro/a."
- Estructura de una recomendación creíble:
  1. **El vínculo:** de dónde la conoces (vecina, prima, hija de un amigo, alguien que ya te ayudó).
  2. **El rasgo clave:** paciencia, puntualidad, madurez, creatividad.
  3. **El aval final:** una frase que demuestre confianza plena.

## 4. Discurso del fundador (resumen)

La diferencia de Bambino no es la verificación (que también hace) sino el **aval personal de amigos y vecinos**: toda cuidadora necesita uno. La categoría "Elite" suma verificación completa de antecedentes.

---

## Qué le sirve a Kangoo

1. **Confirma la tesis de Kangoo:** la recomendación de una persona cercana como requisito para entrar. Kangoo ya la exige; falta que sea creíble (hoy la puede autoescribir la propia cuidadora).
2. **Vínculo + rasgo + aval** es una estructura directa para simplificar el formulario de referencias.
3. **Preguntas guía** en lugar de un cuadro de texto en blanco.
4. **Estrellas y conexiones en común arriba del perfil** → insumo para UX/UI y para el Epic Comunidad (10). Sincronizar contactos del teléfono toca datos personales de terceros → pasa por Confianza, Seguridad & Legal.
5. **Teléfono validado** y **biometría** (tarea 13) refuerzan la identidad.
6. **Mostrar la tarifa** choca con que Kangoo no cobra el cuidado (hoy la tarifa va sugerida en la descripción). Decisión de negocio, no copiar sin discutir.

## Pendientes

- `[PENDIENTE: requiere investigación — confirmar con fuentes cómo opera Bambino hoy: país, verificación, requisito de recomendación, niveles y modelo de cobro]`
- `[PENDIENTE: requiere investigación — si Stripe Identity o Didit funcionan con la cédula chilena y su costo por verificación]`
