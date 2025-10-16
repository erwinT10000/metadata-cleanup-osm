markdown
#  Eliminación de Metadatos Sensibles en Archivos para OSM

Este proyecto ofrece una guía técnica y dos scripts en Bash para escanear y eliminar metadatos sensibles en archivos compartidos en el ecosistema de OpenStreetMap (OSM), como imágenes y documentos técnicos.

##  Objetivo

Fortalecer la privacidad de los colaboradores y mejorar la calidad de los datos abiertos mediante herramientas prácticas y automatizadas.

##  Contenido

-  Guía técnica: “Guía para la eliminación de Metadatos Sensibles aplicado al uso de OpenStreetMap”
-  Script de escaneo: `check_metadata.sh`
-  Script de limpieza: `clean_metadata.sh`
-  Ejemplos y plantillas de comunicación

## Herramientas utilizadas

- [`exiftool`](https://exiftool.org/)
- [`pdf-redact-tools`](https://github.com/firstlookmedia/pdf-redact-tools)

##  Cómo usar

### 1. Escanear archivos

```bash
bash check_metadata.sh archivo.pdf