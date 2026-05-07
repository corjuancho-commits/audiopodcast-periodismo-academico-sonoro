**07 de mayo de 2026, 04:52 p. m. — Documento 04 gestión de referencias**
Comprendo que necesitas el archivo `00_gobierno/04_gestion_referencias.md`, listo para copiar y pegar, con una estructura seria y profesional, pero sin volver el sistema pesado.

````markdown
# 04 — Gestión de referencias

## Identificación

**Proyecto:** Audiopodcast de periodismo académico sonoro  
**Autor:** Juan David Cortés Martínez  
**Documento:** Gestión de referencias  
**Ubicación:** `00_gobierno/04_gestion_referencias.md`  
**Estado:** Documento rector inicial  
**Versión:** 1.0  
**Fecha de creación:** 07 de mayo de 2026  

---

## 1. Propósito del documento

Este documento define cómo se gestionarán las fuentes, citas, referencias y bibliografía del audiopodcast.

Su propósito es garantizar que el proyecto mantenga rigor académico, trazabilidad documental y potencial de publicación, sin convertir cada episodio en una revisión bibliográfica pesada.

La gestión de referencias debe servir para tres fines:

1. respaldar afirmaciones técnicas, científicas, normativas o conceptuales;
2. facilitar la creación de derivados académicos, docentes o editoriales;
3. conservar una biblioteca organizada por episodio y por línea temática.

---

## 2. Principio central

La regla principal será:

> Pocas citas en la voz, buena trazabilidad en el archivo.

El episodio sonoro no debe llenarse de citas académicas que interrumpan la escucha. Sin embargo, las ideas importantes deben tener respaldo documental cuando lo requieran.

La bibliografía no debe usarse como adorno. Cada fuente debe tener una función clara dentro del episodio.

---

## 3. Cuándo se requieren referencias

Un episodio debe activar gestión de referencias cuando incluya:

- conceptos técnicos;
- afirmaciones científicas;
- datos epidemiológicos o estadísticos;
- marcos normativos;
- discusión sobre políticas públicas;
- inteligencia artificial, ciencia de datos o tecnología;
- teorías sociales, pedagógicas o institucionales;
- afirmaciones sobre calidad, seguridad, riesgo o toma de decisiones;
- potencial de convertirse en artículo, ensayo, nota técnica, clase o ponencia.

No todas las ideas requieren cita. Las experiencias personales, reflexiones autorales y observaciones narrativas pueden aparecer sin referencia, siempre que no se presenten como evidencia general.

---

## 4. Tipos de fuentes prioritarias

Se priorizarán fuentes de alta calidad, especialmente:

- artículos científicos;
- revisiones sistemáticas;
- libros académicos;
- capítulos de libro;
- tesis doctorales;
- documentos técnicos de organismos internacionales;
- documentos normativos oficiales;
- informes de universidades;
- publicaciones de sociedades científicas;
- lineamientos institucionales reconocidos;
- reportes técnicos de alto nivel.

Se evitarán como fuentes principales:

- blogs sin respaldo académico;
- notas de opinión sin evidencia;
- contenido comercial;
- páginas sin autoría clara;
- fuentes desactualizadas sin justificación;
- documentos sin trazabilidad.

---

## 5. Idiomas y actualidad

La búsqueda bibliográfica debe priorizar fuentes en:

- español;
- inglés;
- italiano;
- alemán.

Como regla general, se dará preferencia a fuentes publicadas en los últimos cinco años.

Se podrán usar fuentes anteriores cuando sean clásicas, estructurales o conceptualmente indispensables. En ese caso, debe justificarse su uso y, cuando sea posible, acompañarse de literatura reciente.

---

## 6. Relación entre episodio sonoro y bibliografía

La versión sonora del episodio debe privilegiar claridad, ritmo y comprensión.

Las referencias pueden aparecer de tres formas:

1. **En el guion**, cuando una cita o autor sea realmente necesario para la comprensión.
2. **En los show notes**, cuando la fuente sea útil para el oyente.
3. **En el archivo del episodio**, cuando la fuente respalda el trabajo, aunque no se mencione en voz.

La prioridad será no saturar el audio, pero sí conservar trazabilidad suficiente en GitHub.

---

## 7. Carpeta de referencias por episodio

Cada episodio tendrá una carpeta interna:

```text
referencias/
├── fuentes_candidatas.md
├── referencias.bib
├── notas_lectura.md
└── matriz_uso_fuentes.md
````

Estos archivos solo se completarán con el nivel de profundidad que el episodio requiera.

---

## 8. Fuentes candidatas

El archivo `fuentes_candidatas.md` registra fuentes que podrían servir para el episodio.

No toda fuente candidata termina citada.

Cada fuente candidata debe incluir, como mínimo:

```markdown
## Citekey

- **Autor:**
- **Año:**
- **Título:**
- **Tipo de fuente:**
- **Idioma:**
- **Institución / revista / editorial:**
- **DOI o URL:**
- **Tema que aporta:**
- **Uso posible en el episodio:**
- **Estado:** candidata / revisada / usada / descartada
```

---

## 9. Citekey

Cada fuente tendrá un identificador breve llamado `citekey`.

El citekey permite reconocer la fuente en notas, guion, matriz y archivo bibliográfico.

Formato sugerido:

```text
AutorAñoTema
```

Ejemplos:

```text
WHO2021DataQuality
Kitchin2021DataLives
OECD2023HealthDataGovernance
PAHO2024DigitalHealth
```

El citekey debe ser claro, corto y estable.

---

## 10. Archivo BibTeX

Cuando el episodio tenga bibliografía formal o potencial académico, se creará o actualizará el archivo:

```text
referencias.bib
```

Este archivo debe contener las referencias en formato BibTeX para facilitar futuras exportaciones a APA, Vancouver u otros estilos editoriales.

No es obligatorio llenar `referencias.bib` para episodios muy narrativos o preliminares, pero sí para episodios con vocación académica.

---

## 11. Notas de lectura

El archivo `notas_lectura.md` resume las ideas útiles de cada fuente.

Debe evitar copiar fragmentos largos. Su función es extraer lo relevante para el episodio.

Formato sugerido:

```markdown
## Citekey

### Idea central
Resumen breve de la idea principal de la fuente.

### Aporte al episodio
Explicación de cómo esta fuente ayuda a sostener el argumento.

### Fragmentos o conceptos útiles
Notas breves, paráfrasis o conceptos clave.

### Precauciones
Límites de la fuente, contexto, enfoque o posibles sesgos.
```

---

## 12. Matriz de uso de fuentes

El archivo `matriz_uso_fuentes.md` conecta cada fuente con una función concreta.

Formato sugerido:

```markdown
| Citekey | Concepto que soporta | Sección del episodio | Uso | Estado |
|---|---|---|---|---|
| WHO2021DataQuality | Calidad del dato en salud | Marco conceptual | Respaldo técnico | Candidata |
```

La matriz evita acumular bibliografía sin propósito.

---

## 13. Citas dentro del guion

Las citas dentro del guion deben usarse con moderación.

Se recomienda citar en voz cuando:

* el autor o institución aporta autoridad necesaria;
* se presenta un concepto técnico;
* se menciona una cifra específica;
* se refiere una norma;
* se discute evidencia científica;
* se atribuye una idea que no es propia.

En el guion sonoro, la cita debe integrarse de forma natural.

Ejemplo:

> Como han señalado organismos internacionales de salud, la calidad del dato no es solo un asunto técnico; también condiciona la capacidad de los sistemas para tomar decisiones.

La referencia completa puede quedar en show notes y GitHub.

---

## 14. Formato de referencias

El formato base para derivados académicos será **APA 7**.

Cuando una revista o convocatoria exija otro estilo, se podrá adaptar posteriormente a:

* Vancouver;
* Chicago;
* IEEE;
* norma específica de revista.

El archivo BibTeX debe facilitar esa conversión.

---

## 15. Referencias normativas

Cuando se usen normas, resoluciones, leyes, lineamientos o documentos oficiales, se debe registrar:

* país;
* entidad emisora;
* año;
* título completo;
* número de norma, si aplica;
* URL oficial;
* fecha de consulta, si aplica;
* uso dentro del episodio.

Las normas no deben citarse de memoria.

---

## 16. Estado de una fuente

Cada fuente puede tener uno de estos estados:

```text
Candidata
Revisada
Usada
Descartada
Pendiente de verificación
```

Una fuente no debe pasar a “usada” si no se ha revisado suficientemente.

---

## 17. Criterios de confiabilidad

Antes de usar una fuente, se debe valorar:

* autoría;
* institución o revista;
* año de publicación;
* metodología;
* pertinencia para el episodio;
* contexto geográfico;
* idioma;
* nivel de evidencia;
* sesgos posibles;
* utilidad real para la tesis.

La fuente más reciente no siempre es la mejor. La fuente más citada tampoco siempre es la más pertinente.

---

## 18. Uso de inteligencia artificial en referencias

La inteligencia artificial puede ayudar a:

* organizar fuentes;
* resumir documentos;
* extraer metadatos;
* crear citekeys;
* sugerir matrices;
* convertir referencias;
* preparar notas de lectura;
* identificar vacíos bibliográficos.

Pero no debe inventar fuentes.

Toda referencia usada debe ser verificable.

---

## 19. Referencias y derivados académicos

Cuando un episodio se proyecte como artículo, ensayo, ponencia o material académico, se debe fortalecer la bibliografía.

En ese caso, el episodio deberá contar con:

* fuentes candidatas revisadas;
* referencias en BibTeX;
* notas de lectura;
* matriz de uso;
* citas insertadas en el texto académico;
* bibliografía final en el formato requerido.

La versión académica puede tener más citas que la versión sonora.

---

## 20. Cierre bibliográfico de un episodio

Un episodio puede cerrarse en tres estados bibliográficos:

### Sin bibliografía formal

El episodio es principalmente narrativo, reflexivo o introductorio. No requiere bibliografía estructurada inmediata.

### Bibliografía mínima

El episodio usa algunas fuentes clave para respaldar conceptos, datos o afirmaciones.

### Bibliografía robusta

El episodio tiene potencial académico o técnico y requiere revisión más cuidadosa.

El estado bibliográfico debe quedar registrado en el `07_registro_maestro.md` de cada episodio.

---

## 21. Declaración de cierre

La gestión de referencias del podcast debe permitir rigor sin rigidez.

El objetivo no es llenar cada episodio de citas, sino asegurar que las ideas importantes puedan rastrearse, verificarse y convertirse, si es necesario, en productos académicos o técnicos de mayor alcance.

El podcast debe sonar claro y humano, pero estar documentado con seriedad.

---

## Historial de versiones

### Versión 1.0 — 07 de mayo de 2026

Primera versión del documento de gestión de referencias del audiopodcast.

```
```
