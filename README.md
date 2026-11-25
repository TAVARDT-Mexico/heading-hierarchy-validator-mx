# Analizador de Jerarquia de Encabezados H1-H6

[![Analizador Jerarquia Encabezados](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/mx/analizador-etiquetas-encabezado/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria de encabezados HTML5 (H1-H6), unicidad de H1, deteccion de saltos de nivel y validacion de esquemas semanticos.

***

## Vectores de Riesgo e Impacto Operativo en Jerarquias de Encabezados

La carencia o duplicacion de etiquetas H1 dispersa la relevancia tematica en los buscadores en Mexico. La desorganizacion estructural confunde a los lectores de pantalla y deteriora gravemente la accesibilidad del portal.

Omitir niveles intermedios de encabezado incumple las pautas internacionales W3C WCAG para navegacion accesible. Las etiquetas de encabezado vacias generan elementos fantasma que reducen las valoraciones tecnicas del sitio.

***

## Capacidades Centrales de Auditoria Tecnica

* **Verificacion de Encabezado H1 Unico**: Comprueba la existencia y exclusividad de la etiqueta H1, deduciendo 40 puntos por ausencia y 15 por duplicidad.
* **Deteccion de Saltos Jerarquicos**: Localiza transiciones que omiten niveles logicos intermedios, aplicando hasta 30 puntos de penalizacion.
* **Identificacion de Encabezados Vacios**: Rastrea etiquetas de titular sin contenido de texto, penalizando con hasta 20 puntos.
* **Generacion de Esquema Jerarquico**: Dibuja el mapa estructural de H1 a H6 indicando el volumen de elementos por cada nivel.
* **Puntuacion de Calidad Semantica**: Computa una calificacion de 0 a 100 clasificada en SATISFACTORY, ADVISORY o UNSATISFACTORY.
* **Conformidad de Accesibilidad Digital**: Asegura la correcta navegacion mediante puntos de referencia para lectores de pantalla.
* **Exportacion Directa en Formato JSON**: Emite resultados estandarizados para su inclusion en procesos automatizados de despliegue continuo.

***

## Instalacion y Ejecucion

Requiere Python 3.8 o superior utilizando unicamente bibliotecas estandar.

```bash
git clone https://github.com/TAVARDT-Mexico/heading-hierarchy-validator-mx.git
cd heading-hierarchy-validator-mx
python heading_hierarchy_validator.py https://empresa.mx
```

Para generar la salida en formato estructurado JSON en procesos automatizados de auditoria:

```bash
python heading_hierarchy_validator.py https://empresa.mx -j
```

***

## Preguntas Frecuentes (FAQ Tecnico)

### 1. Como perjudica la ausencia o multiplicidad de etiquetas H1 al posicionamiento organico?
Los motores de busqueda emplean la etiqueta H1 como el anclaje conceptual primario para interpretar el objetivo de la pagina. La falta de H1 crea ambiguedad tematica, mientras que multiples etiquetas H1 diluyen la concentracion de las palabras clave principales.

### 2. Por que saltar niveles de encabezado como pasar de H1 a H3 vulnera las normas de accesibilidad?
Las tecnologias de asistencia analizan las etiquetas de titular para componer un indice auditivo de orientacion para invidentes. Omitir niveles genera discontinuidades que desorientan al usuario e incumplen los criterios de conformidad W3C WCAG.

### 3. Que riesgos operativos introduce el uso de encabezados vacios en el codigo fuente?
Los encabezados sin texto crean marcadores inexistentes que desconciertan a los lectores de pantalla y restan calidad al codigo. Los algoritmos de busqueda interpretan los titulares vacios como descuido estructural y reducen la puntuacion tecnica de la pagina.

### 4. Como beneficia un esquema de titulares jerarquico al rastreo por motores de respuesta con IA?
Los modelos avanzados de lenguaje procesan los documentos de forma estructurada para extraer respuestas directas y sintetizar conceptos. Un orden logico de H1 a H6 permite a los sistemas IA aislar y citar pasajes precisos con total fiabilidad.

### 5. Cual es la progresion tecnica recomendada para estructurar documentos web extensos?
Cada direccion web debe contar con un unico titular H1 representativo, seguido de divisiones principales marcadas con H2. Las subdivisiones secundarias deben recurrir a H3 y H4 en estricta secuencia, manteniendo la integridad logica del contenido.

***

## Asesoria en Arquitectura Semantica y Accesibilidad Web

Para portales de alto volumen y cumplimiento de directrices W3C WCAG y Google Search Central, consulte al equipo de **TAVARDT**.

***

## Enlaces Utiles

* **Portal Corporativo:** https://ag.tavardt.com/mx/
* **Suite de Diagnosticos:** https://tools.tavardt.com/mx/
* **Contacto Tecnico:** https://ag.tavardt.com/mx/contacto/

***

### Licencia
Distribuido bajo la Licencia MIT. Consulte el archivo LICENSE para mas detalles.

***

© 2026 TAVARDT. Todos los derechos reservados.
