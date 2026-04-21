---
title: "Jornada de Investigación y Divulgación en Información y Cómputo Cuántico"
layout: single
permalink: /
author_profile: false
classes:
  - no-masthead
breadcrumbs: false
toc: true
header:
  image: /assets/images/event-banner.jpeg

sidebar:
  - title: "" 

ponentes:
  - name: "Claudia Zendejas-Morales"
    role: "Estudiante de posgrado en Quantum Information Science"
    affiliation: "University of Copenhagen / Technical University of Denmark (DTU)"
    talk_title: "Cuando el kernel cuántico deja de aprender: concentración exponencial y estrategias de mitigación"
    duration: "45-50 minutos"
    image_path: "/assets/images/Claudia.jpeg"
    linkedin: "https://www.linkedin.com/in/clauziuz/"
    bio: "Claudia Zendejas-Morales es física e ingeniera en computación, reconocida en el *Quantum 100* de la UNESCO (IYQ 2025). Posee dos MicroMasters en Tecnologías Cuánticas por Purdue University y es desarrolladora certificada de Qiskit. Como miembro activo de QWorld, ha coordinado programas globales como QClass23/24 y actualmente co-lidera el área de QEducation. Sus intereses de investigación abarcan la información cuántica teórica, el aprendizaje automático cuántico (QML) y los fundamentos matemáticos de la computación cuántica, centrando actualmente sus estudios de posgrado en Copenhague."

  - name: "Dr. Salvador Elías Venegas Andraca"
    role: "Investigador Principal del Unconventional Computing Lab"
    affiliation: "Tecnológico de Monterrey / UNAM"
    talk_title: "Computación cuántica: de la investigación científica al mercado de alta tecnología"
    duration: "50 minutos"
    image_path: "/assets/images/Salvador.jpg"
    linkedin: "https://www.linkedin.com/in/venegasandraca/"
    bio: "Salvador Elías Venegas Andraca es pionero de la computación cuántica en México y una autoridad mundial en el área. Doctor por la Universidad de Oxford con estancia postdoctoral en Harvard, es Investigador Nivel 3 del SNI y miembro del Quantum Economy Network del Foro Económico Mundial. Es autor de libros fundamentales como *Quantum Walks for Computer Scientists* y cuenta con más de tres mil citas en su campo. Su labor integra la academia y la industria, centrándose en algoritmos cuánticos, caminatas cuánticas, ciberseguridad y el análisis del mercado emergente de tecnologías cuánticas de alta especialidad."

  - name: "Dr. Javier Andres Orduz Ducuara"
    role: "Profesor"
    affiliation: "FES Acatlán UNAM"
    talk_title: "Criptografía en la era cuántica: Una perspectiva matemática"
    duration: "45-50 minutos"
    image_path: "/assets/images/Javier.jpeg"
    github: "https://jaorduz.github.io/" 
    bio: "El Dr. Javier Orduz es un investigador especializado en computación cuántica, inteligencia artificial y ciencia de datos. Su trabajo se enfoca en transformar conceptos matemáticos complejos en soluciones prácticas para sistemas inteligentes y seguridad digital. Como impulsor de iniciativas para acercar a más personas estas tecnologías, fundó QMexico una comunidad que promueve la educación cuántica en América Latina, y Qaldas, donde se desarrollan proyectos de IA y computación avanzada. Su labor integra la investigación y la docencia para inspirar a nuevas generaciones en ciencias y tecnología."

---
## Presentación

Les damos la bienvenida a la **Jornada de Investigación y Divulgación en Información y Cómputo Cuántico**, un espacio académico orientado a la presentación, discusión y articulación de investigaciones en el área.

Dirigido a investigadores, estudiantes de posgrado, estudiantes avanzados de licenciatura, grupos de investigación emergentes y público interesado en información y cómputo cuántico.

[Envío de pósters](https://docs.google.com/forms/d/e/1FAIpQLSfS9h_ZqV9QzWb8apmvWtSY5euiBi14-8FNRS7kRuMwQvE9NA/viewform?usp=sharing&ouid=112858010038445605015){: .btn .btn--primary .btn--large}
[Registro asistentes](https://docs.google.com/forms/d/e/1FAIpQLSf-l84Fk4j1KSedCQureZK0RgIE8Eg1nk3uk80pBU9EeNceyg/viewform?usp=sharing&ouid=112858010038445605015){: .btn .btn--primary .btn}
[Fechas importantes](#fechas-importantes){: .btn .btn--warning}
[Programa](#programa-preliminar){: .btn .btn--info}

> El registro de asistentes y el envío de pósters se realizan mediante formularios distintos.

> La postulación de un póster no es requisito para el registro ni para la asistencia al evento.

| Información | Detalle |
|---|---|
| **Modalidad** | Presencial |
| **Fecha** | 5 de junio de 2026 |
| **Horario** | Programa detallado por anunciar |
| **Sede** | Auditorio Dr. Víctor Flores Maldonado, [Edificio 9, ESFM - IPN, Ciudad de México](https://maps.app.goo.gl/xfYBHToRYQnLZkPA7)    |

### Objetivo general

Consolidar un espacio académico para la presentación, discusión, divulgación y articulación de trabajos en información y cómputo cuántico, fomentando el intercambio entre investigadores, estudiantes, grupos emergentes y público interesado.

### Objetivos específicos

- Visibilizar las líneas activas de investigación y los esfuerzos de divulgación en el área.
- Facilitar la interacción entre grupos de investigación del instituto, universidades invitadas y distintos sectores de la comunidad académica.
- Promover la creación de colaboraciones científicas y fortalecer la comunidad local en información y cómputo cuántico.
- Impulsar la apropiación y difusión de conceptos, métodos y aplicaciones del área entre estudiantes y público no especializado.

## Conferencias Plenarias

La jornada contará con ponencias invitadas por parte de especialistas en información y cómputo cuántico.

<div class="ponentes-container">
  {% for ponente in page.ponentes %}
    <div class="ponente-card" style="display: flex; flex-wrap: wrap; gap: 25px; margin-bottom: 50px; align-items: flex-start; background-color: rgba(0,0,0,0.02); padding: 20px; border-radius: 8px;">
      
      <div style="flex-shrink: 0; width: 160px; text-align: center;">
        {% if ponente.image_path %}
          <img src="{{ ponente.image_path | relative_url }}" alt="Foto de {{ ponente.name }}" style="width: 160px; height: 160px; border-radius: 50%; object-fit: cover; box-shadow: 0 4px 8px rgba(0,0,0,0.1); margin-bottom: 10px;">
        {% endif %}

        <div style="display: flex; flex-direction: column; gap: 5px; align-items: center;">
          {% if ponente.linkedin %}
            <a href="{{ ponente.linkedin }}" target="_blank" rel="noopener noreferrer" style="font-size: 0.9em; text-decoration: none; color: #0077b5;">LinkedIn</a>
          {% endif %}

          {% if ponente.github %}
            <a href="{{ ponente.github }}" target="_blank" rel="noopener noreferrer" style="font-size: 0.9em; text-decoration: none; color: #333;"> GitHub / Web</a>
          {% endif %}
        </div>
      </div> 

      <div class="ponente-info" style="flex: 1; min-width: 300px;">
        <h3 style="margin-top: 0; margin-bottom: 5px;">{{ ponente.name }}</h3>
        <p style="margin-top: 0; font-size: 0.95em; color: #555;">
          <strong>{{ ponente.role }}</strong><br>
          <em>{{ ponente.affiliation }}</em>
        </p>

        <div style="background-color: rgba(0,0,0,0.04); padding: 12px 15px; border-left: 4px solid #007acc; margin: 15px 0;">
          <p style="margin: 0;"><strong>Charla:</strong> {{ ponente.talk_title }}</p>
          <p style="margin: 0; font-size: 0.9em; margin-top: 5px;">⏱️ <strong>Duración:</strong> {{ ponente.duration }}</p>
        </div>

        <p style="text-align: justify; margin-bottom: 0;">{{ ponente.bio }}</p>
      </div>

    </div>
  {% endfor %}
</div>
## Call for Posters

Se invita a la comunidad a participar en la sesión de pósters de la Jornada.

La convocatoria está dirigida a contribuciones en información y cómputo cuántico, incluyendo investigaciones en progreso, resultados preliminares y trabajos de divulgación. Se busca favorecer el intercambio académico y la discusión de ideas en desarrollo dentro de la comunidad.

La modalidad de presentación consiste en la exhibición de un póster durante la sesión correspondiente. Al menos una persona autora deberá estar presente para la exposición y discusión del trabajo.

### Ejes temáticos

- *Algoritmos y Software*
- *Quantum Machine Learning (QML)*
- *Aplicaciones*
- *Teoría de la Información Cuántica*
- *Otros temas relacionados*

### Requisitos
- Idioma: español o inglés
- Incluir título, autores y afiliaciones
- Incluir archivo en formato PDF
- El trabajo debe corresponder a alguno de los ejes temáticos de la jornada

### Evaluación
Los pósters serán revisados por el comité científico con base en pertinencia temática, claridad expositiva y calidad académica general.

### Recomendaciones para la elaboración del póster

Aunque el formato es libre, se recomienda que el póster cumpla con criterios básicos de claridad académica y legibilidad. En particular, se sugiere:

- incluir título, autores y afiliaciones de manera visible;
- estructurar el contenido de forma ordenada;
- emplear figuras y gráficas claras;
- asegurar la legibilidad del texto y de los elementos gráficos a una distancia aproximada de 1.5 metros.

Como apoyo para la preparación del material, las personas participantes pueden consultar plantillas de uso libre disponibles en Overleaf:
[Plantillas de póster en Overleaf](https://www.overleaf.com/gallery/tagged/poster)

Estas plantillas son únicamente una referencia y no constituyen un formato obligatorio para el evento.

[Envío de pósters](https://docs.google.com/forms/d/e/1FAIpQLSfS9h_ZqV9QzWb8apmvWtSY5euiBi14-8FNRS7kRuMwQvE9NA/viewform?usp=sharing&ouid=112858010038445605015){: .btn .btn--primary .btn--large style="display: block; margin: 0 auto; width: fit-content;"}

> El formulario de envío requiere acceso con una cuenta de Google para cargar archivos.

## Fechas importantes

| Actividad | Fecha |
|---|---|
| **Recepción de pósters** | Desde la publicación de la convocatoria, hasta el 29 de abril de 2026|
| **Notificación de aceptación** | 13 al 20 de mayo de 2026  |
| **Evento** | 5 de junio de 2026 |

## Programa (Preliminar)

La jornada contempla las siguientes actividades:

- Apertura
- Conferencias plenarias
- Sesión de pósters
- Espacio de café e intercambio académico
- Cierre

> El programa detallado y horarios específicos por anunciar.

## Comité científico

> Por anunciar.

## Comité organizador

**Chair:** Roberto Navarro Arenas - `rnavarroa1600@alumno.ipn.mx`

<ul class="organizers-list">
<li>José Alberto Guzmán Vega - <code>jguzmanv1501@alumno.ipn.mx</code></li>
<li>Aarón Ortiz Mendoza - <code>aortizm1300@alumno.ipn.mx</code></li>
<li>David Jafet Zaleta Garcia - <code>dzaletag1800@alumno.ipn.mx</code></li>
<li>Jorge Gael López Figueras - <code>jlopezf2002@alumno.ipn.mx</code></li>
<li>Juan Carlos Jiménez Cervantes - <code>jjimenezc1200@alumno.ipn.mx</code></li>
<li>Dr. Raymundo Santana Carrillo - <code>rsantanac@ipn.mx</code></li>
</ul>

### Contacto

Para dudas, escribir a: [`rnavarroa1600@alumno.ipn.mx`](mailto:rnavarroa1600@alumno.ipn.mx)
