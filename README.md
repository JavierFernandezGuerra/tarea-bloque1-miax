# Analizador Bursátil 📈

Este proyecto es un conjunto de herramientas para la **obtención y análisis de información bursátil**.  
El objetivo es facilitar la descarga de datos desde diferentes fuentes, estandarizar su formato y 
permitir su análisis estadístico y visual.  

El desarrollo se centra en aplicar **buenas prácticas de programación**, de forma que el proyecto 
pueda crecer y mantenerse de manera ordenada.

---

## 🎯 Objetivos del proyecto
- Crear un programa extractor que obtenga datos históricos de precios de acciones e índices desde diferentes APIs.  
- Estandarizar el formato de los datos descargados, sin importar la fuente original.  
- Implementar **DataClasses** para representar series temporales y carteras.  
- Añadir métodos estadísticos (media, desviación estándar, etc.).  
- Desarrollar una simulación de **Monte Carlo** sobre valores o carteras.  
- Incluir visualizaciones y un sistema de reportes automáticos en Markdown.  
- Mantener una estructura clara, con carpetas, dependencias y documentación organizada.  

---

## 📂 Estructura del proyecto
```bash
/src/
│── extractor/       # Módulos para obtener datos desde APIs (ej: Yahoo Finance, Alpha Vantage)
│── models/          # Clases de datos (series de precios, carteras)
│── analysis/        # Métodos de análisis, simulaciones y visualización
/tests/              # Pruebas unitarias
/docs/               # Documentación y diagramas de arquitectura
````
---

## ⚙️ Instalación
Clona este repositorio y entra en la carpeta:

```bash
git clone https://github.com/tu-usuario/analizador-bursatil.git
cd analizador-bursatil
pip install -r requirements.txt


