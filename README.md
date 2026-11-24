# Validador de Etiqueta Canonica y Consolidacion de URLs

[![Validador Etiqueta Canonica](https://img.shields.io/badge/TAVARDT-Canonical-5b3cf5.svg)](https://tools.tavardt.com/es/validador-etiqueta-canonica/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria de rutas canonicas, deteccion de etiquetas duplicadas y prevencion de canibalizacion SEO.

Desarrollado y mantenido por la division de arquitectura web e indexacion de **TAVARDT**.

***

## Capacidades de Auditoria de Etiqueta Canonica

* **Deteccion de Enlaces Canonicos**: Comprueba la declaracion de `<link rel="canonical">` en cabeceras HTML y cabeceras HTTP `Link`.
* **Prevencion de Etiquetas Duplicadas**: Detecta y alerta sobre multiples etiquetas canonical contradictorias en una misma URL.
* **Validacion de URLs Absolutas**: Confirma que el destino este estructurado como URL absoluta y protocolo seguro HTTPS.
* **Comprobacion de Estado del Destino**: Valida que la pagina canonica de destino responda con codigo HTTP 200 OK.
* **Puntuacion de Salud de Indexacion**: Indice cuantitativo de 0 a 100 con pasos de resolucion tecnica.

***

## Instalacion y Ejecucion

Requiere Python 3.8 o superior sin dependencias externas.

```bash
git clone https://github.com/TAVARDT-Espana/canonical-tag-validator-es.git
cd canonical-tag-validator-es
python canonical_validator.py https://empresa.es
```

Para generar salida estructurada JSON:

```bash
python canonical_validator.py https://empresa.es -json
```

***

## Diagnostico Completo en la Web

Para revision profunda de consolidacion canonica:

* **Validador de Etiqueta Canonica Oficial**
* **[Portal Corporativo TAVARDT](https://ag.tavardt.com/es/)**

***

## Consultoria en Arquitectura Web y SEO

Para proyectos avanzados de consolidacion de catalogo y cumplimiento de Estandares W3C y Directrices Digitales UE, consulte al equipo de **TAVARDT**.

***

## Enlaces Útiles

* **Portal Corporativo:** https://ag.tavardt.com/es/
* **Suite de Diagnósticos:** https://tools.tavardt.com/es/
* **Contacto Técnico:** https://ag.tavardt.com/es/contacto/

***

© 2026 TAVARDT. Todos los derechos reservados.
