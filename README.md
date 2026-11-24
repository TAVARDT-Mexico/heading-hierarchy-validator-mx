# Analizador de Jerarquia de Encabezados H1-H6

[![Analizador Jerarquia Encabezados](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/mx/analizador-etiquetas-encabezado/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Evaluacion de coherencia semantica, deteccion de saltos jerarquicos y optimizacion para motores de busqueda.

Desarrollado y respaldado por la division de calidad digital de **TAVARDT Mexico**.

***

## Capacidades de Diagnostico de Encabezados

* **Validacion de Titulo H1 Principal**: Comprobacion de presencia y unicidad del H1 en plataformas de comercio y medios.
* **Deteccion de Rupturas Jerarquicas**: Identificacion de saltos indebidos entre niveles H2 a H6.
* **Supervision de Contenido Vacio**: Deteccion de etiquetas de encabezado sin texto visible para el usuario.
* **Esquema de Documento Accesible**: Mapeo claro de la estructura de lectura para usuarios y rastreadores.
* **Indice de Calidad Semantica**: Puntuacion de 0 a 100 con lineamientos practicos de resolucion.

***

## Instalacion y Uso

Requiere Python 3.8 o superior sin librerias adicionales.

```bash
git clone https://github.com/TAVARDT-Mexico/heading-hierarchy-validator-mx.git
cd heading-hierarchy-validator-mx
python heading_hierarchy_validator.py https://empresa.mx
```

Generacion de reporte en JSON:

```bash
python heading_hierarchy_validator.py https://empresa.mx -json
```

***

## Herramienta en Linea

Para pruebas en la nube con analisis visual:

* **Analizador de Jerarquia de Encabezados en Mexico**
* **[Portal TAVARDT Mexico](https://ag.tavardt.com/mx/)**

***

## Soporte y Asesoria

Para estructuracion de contenidos conforme a Estandares Digitales Nacionales y Google Search Central, contacte a **TAVARDT Mexico**.

***

© 2026 TAVARDT. Todos los derechos reservados.
