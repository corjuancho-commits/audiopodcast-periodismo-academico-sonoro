# 01 — Arquitectura operativa del audiopodcast

## Identificación

**Proyecto:** Audiopodcast de periodismo académico sonoro  
**Autor:** Juan David Cortés Martínez  
**Documento:** Arquitectura operativa del proyecto  
**Ubicación:** `00_gobierno/01_arquitectura_operativa.md`  
**Estado:** Documento rector inicial  
**Versión:** 1.0  
**Fecha de creación:** 07 de mayo de 2026  

---

## 1. Propósito del documento

Este documento define la arquitectura operativa del audiopodcast.

Su función es convertir el concepto editorial del proyecto en un sistema práctico de producción, archivo, publicación y trazabilidad.

El audiopodcast no debe depender de improvisaciones, memoria dispersa ni decisiones tomadas de manera aislada en cada episodio. Cada entrega debe nacer de una estructura mínima, desarrollarse en un flujo claro, producir derivados útiles y quedar archivada de forma ordenada en el repositorio.

La arquitectura operativa tiene cuatro objetivos principales:

1. Reducir el trabajo tedioso de producción.
2. Proteger la identidad intelectual del podcast.
3. Organizar cada episodio como unidad editorial, sonora, documental y eventualmente académica.
4. Permitir que el proyecto crezca progresivamente sin volverse pesado ni burocrático.

---

## 2. Principio operativo central

El principio central del proyecto es:

> Ningún episodio se produce de forma improvisada.

Cada episodio debe pasar por una ruta mínima de gobierno editorial antes de llegar a guion, grabación, publicación o archivo.

Esto no significa llenar formularios innecesarios ni convertir cada episodio en una tesis. Significa que cada entrega debe tener claridad sobre su problema, pregunta rectora, tesis, audiencia, estructura narrativa, productos derivados y criterio de cierre.

El proyecto debe ser profesional desde el inicio, pero estructuralmente liviano.

---

## 3. Modelo general de operación

El podcast funcionará mediante una arquitectura de dos niveles principales:

1. **Chat 0 — Gobierno General del Podcast**
2. **Chats hijos por episodio**

El Chat 0 gobierna el sistema completo.  
Los chats hijos desarrollan episodios específicos.

Esta separación evita que cada episodio rediseñe el proyecto desde cero y permite mantener coherencia entre entregas.

---

## 4. Chat 0 — Gobierno General del Podcast

El Chat 0 es el órgano rector del proyecto.

Su función no es escribir episodios de manera improvisada, sino gobernar la arquitectura editorial, pedagógica, documental y operativa del podcast.

### 4.1 Funciones del Chat 0

El Chat 0 debe:

- custodiar la identidad intelectual del podcast;
- convertir ideas sueltas en episodios viables;
- decidir si una idea corresponde a episodio, serie, nota breve o backlog;
- construir la ficha maestra de cada episodio;
- generar el prompt maestro para cada chat hijo;
- definir el orden de producción;
- evitar dispersión temática;
- impedir duplicaciones innecesarias;
- decidir cuándo un episodio está listo para pasar a producción;
- validar el cierre de cada episodio;
- mantener actualizado el backlog;
- orientar la estructura documental del repositorio;
- decidir qué productos derivados deben producirse;
- activar la capa académica cuando sea pertinente.

### 4.2 Lo que el Chat 0 no debe hacer

El Chat 0 no debe:

- redactar episodios completos de forma improvisada;
- cerrar episodios sin criterios verificables;
- inventar evidencia;
- imponer complejidad innecesaria;
- convertir todos los episodios en artículos académicos;
- producir derivados si el episodio aún no tiene base suficiente;
- mezclar el gobierno del proyecto con el desarrollo profundo de un episodio específico.

---

## 5. Chats hijos por episodio

Cada episodio tendrá su propio chat de desarrollo.

Ese chat hijo se abrirá únicamente cuando el Chat 0 haya producido un prompt maestro específico.

El chat hijo debe trabajar exclusivamente el episodio asignado.

### 5.1 Funciones del chat hijo

Cada chat hijo debe:

- recibir el prompt maestro del episodio;
- trabajar con la ficha maestra aprobada;
- revisar el borrador o la idea base;
- hacer diagnóstico editorial;
- proponer ajustes estructurales;
- depurar el guion;
- producir el guion final listo para grabación;
- generar el paquete RSS/Captivate.fm;
- organizar los derivados;
- preparar los archivos base para GitHub;
- identificar necesidades bibliográficas;
- entregar matriz de cierre.

### 5.2 Límites del chat hijo

El chat hijo no puede:

- rediseñar el podcast completo;
- alterar la tesis madre del proyecto;
- cambiar la línea editorial general;
- abrir nuevos episodios;
- cerrar un episodio sin entregar productos mínimos;
- inventar fuentes o referencias;
- expandir el episodio más allá de su función aprobada;
- mezclar el episodio con otros temas no autorizados.

---

## 6. Niveles de decisión del proyecto

Toda solicitud dentro del proyecto debe ubicarse en uno de estos niveles:

### Nivel 0 — Gobierno general del proyecto

Corresponde a decisiones sobre identidad, arquitectura madre, repositorio, flujo de trabajo, criterios de cierre, automatización y organización general.

### Nivel 1 — Sistema editorial

Corresponde a decisiones sobre tono, líneas temáticas, temporadas, tipos de episodio, público, promesa de valor y reglas narrativas.

### Nivel 2 — Evaluación de ideas de episodio

Corresponde a recibir una idea, depurarla, decidir si tiene potencial y ubicarla como episodio, serie, nota breve o insumo de backlog.

### Nivel 3 — Diseño estructural de episodio

Corresponde a construir la ficha maestra del episodio: problema, pregunta rectora, tesis, audiencia, capas analíticas, riesgos, evidencia y entregables.

### Nivel 4 — Prompt maestro de episodio

Corresponde a generar el prompt que abrirá el chat hijo del episodio.

### Nivel 5 — Cierre, documentación y archivo

Corresponde a validar guion, RSS, show notes, derivados, referencias, registro maestro y estado final del episodio.

---

## 7. Flujo operativo de un episodio

Cada episodio seguirá una ruta mínima de producción.

### 7.1 Entrada de idea o borrador

El episodio puede nacer de:

- una idea suelta;
- una pregunta;
- una experiencia profesional;
- una noticia;
- una lectura;
- una clase;
- un problema institucional;
- un borrador ya escrito;
- una investigación en curso;
- una necesidad pedagógica;
- una reflexión sobre salud, datos, IA o sociedad.

La entrada no se convierte automáticamente en episodio. Primero debe ser evaluada.

### 7.2 Evaluación por Chat 0

El Chat 0 decide:

- si la idea pertenece al podcast;
- si debe ser episodio completo;
- si conviene como serie;
- si debe ser nota breve;
- si debe ir al backlog;
- si requiere investigación previa;
- si tiene potencial académico;
- si se conecta con episodios anteriores o futuros.

### 7.3 Ficha maestra

Si la idea avanza, se construye una ficha maestra.

La ficha maestra define:

- ID del episodio;
- título provisional;
- problema central;
- pregunta rectora;
- tesis;
- audiencia principal;
- promesa de valor;
- tipo de episodio;
- estructura narrativa;
- capas analíticas;
- evidencia requerida;
- riesgos;
- productos derivados;
- criterio de cierre.

La ficha maestra es el contrato editorial del episodio.

### 7.4 Prompt maestro

Con la ficha aprobada, el Chat 0 genera el prompt maestro del episodio.

Este prompt contiene:

- identidad del chat hijo;
- autoridad y límites;
- materiales base;
- función del episodio;
- problema central;
- pregunta rectora;
- tesis;
- audiencia;
- estructura narrativa;
- riesgos;
- entregables;
- criterios de cierre.

El prompt maestro se copia en un nuevo chat, exclusivo para ese episodio.

### 7.5 Desarrollo en chat hijo

El chat hijo trabaja por fases:

1. diagnóstico editorial;
2. ajuste estructural;
3. guion final;
4. paquete RSS;
5. archivo GitHub;
6. referencias candidatas;
7. matriz de cierre.

### 7.6 Retorno al Chat 0

Cuando el chat hijo entrega sus productos, el resultado vuelve al Chat 0.

El Chat 0 valida:

- coherencia con el proyecto madre;
- cumplimiento de la ficha;
- calidad narrativa;
- utilidad para el oyente;
- estructura RSS;
- archivo GitHub;
- estado bibliográfico;
- potencial de publicación;
- cierre real del episodio.

### 7.7 Archivo final

Una vez validado, el episodio se archiva en su carpeta correspondiente del repositorio.

Solo después de este cierre puede habilitarse formalmente el siguiente episodio.

---

## 8. Regla de avance entre episodios

La regla general será:

> No se inicia formalmente un episodio nuevo si el episodio anterior no está suficientemente cerrado.

Esto no impide capturar ideas futuras. Las ideas se registran en el backlog y se retoman cuando corresponda.

La producción debe ser secuencial para evitar dispersión, pero el sistema debe permitir conservar intuiciones, referencias y temas emergentes.

---

## 9. Estructura documental del repositorio

El repositorio se organizará de forma progresiva.

La estructura inicial será:

```text
audiopodcast-periodismo-academico-sonoro/
├── README.md
├── 00_gobierno/
│   ├── 00_concepto_madre.md
│   ├── 01_arquitectura_operativa.md
│   ├── 02_sistema_editorial.md
│   ├── 03_flujo_produccion_episodios.md
│   ├── 04_gestion_referencias.md
│   ├── 05_backlog_episodios.md
│   └── 06_criterios_cierre_publicacion.md
├── episodios/
│   └── EPI-001_empezar-a-mirar-la-salud-con-ojos-de-datos/
│       ├── 00_ficha_maestra.md
│       ├── 01_prompt_maestro.md
│       ├── 02_borrador_original.md
│       ├── 03_guion_final.md
│       ├── 04_rss_captivate.md
│       ├── 05_show_notes.md
│       ├── 06_derivados.md
│       ├── 07_registro_maestro.md
│       ├── referencias/
│       │   ├── fuentes_candidatas.md
│       │   ├── referencias.bib
│       │   ├── notas_lectura.md
│       │   └── matriz_uso_fuentes.md
│       └── archivo/
│           ├── versiones.md
│           └── decisiones_editoriales.md
└── recursos/
    ├── plantillas/
    ├── referencias/
    └── criterios/
