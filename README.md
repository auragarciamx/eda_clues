# 🏥 Análisis Exploratorio de Datos (EDA) - CLUES 2025

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-red.svg)](VERSION)

## 📋 Descripción

Este proyecto contiene un **análisis exploratorio de datos (EDA) completo** del **Catálogo de Establecimientos de Salud (CLUES) 2025** de México. El análisis proporciona insights detallados sobre la distribución, características y calidad de los datos de **58,616 establecimientos de salud** en todo el territorio nacional.

### 🎯 Objetivos del Análisis

- **📊 Exploración exhaustiva** de la estructura y calidad de los datos CLUES
- **🗺️ Análisis geográfico** de la distribución de establecimientos de salud
- **🏥 Clasificación y análisis** de tipos de servicios e instituciones
- **📈 Visualizaciones informativas** para facilitar la comprensión
- **💡 Reporte ejecutivo** listo para compartir y tomar decisiones

### 🔍 Hallazgos Clave

- **58,616 establecimientos** analizados across 32 entidades federativas
- **81.9%** son de consulta externa (atención primaria)
- **69.1%** ubicados en áreas urbanas vs **30.9%** rurales
- **34.6%** pertenecen a la Secretaría de Salud
- **30.3%** son servicios médicos privados
- **104 tipologías** diferentes de establecimientos

## 📁 Estructura del Proyecto

```
eda_clues/
├── 📂 src/                         # Código fuente
│   └── analisis_clues_2025.ipynb   # Notebook principal del análisis
├── 📂 data/                        # Datos fuente
│   └── Catálogos CLUES Establecimiento Salud 2025.xlsx
├── 📂 images/                      # Visualizaciones generadas
│   ├── distribucion_geografica.png
│   ├── tipos_establecimiento.png
│   ├── distribucion_institucional.png
│   └── nivel_atencion_estrato.png
├── 📂 docs/                        # Documentación adicional
├── 📄 README.md                    # Este archivo
├── 📄 requirements.txt             # Dependencias de Python
├── 📄 CHANGELOG.md                 # Historial de versiones
├── 📄 VERSION                      # Versión actual
└── 📄 .gitignore                   # Configuración Git
```

## 🚀 Instalación y Uso

### Prerrequisitos

- Python 3.7 o superior
- Jupyter Notebook o JupyterLab

### Instalación

1. **Clonar o descargar** este repositorio
2. **Instalar las dependencias**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Iniciar Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
4. **Abrir el archivo** `analisis_clues_2025.ipynb`

### Ejecución

1. **Verificar** que el archivo de datos Excel esté en la carpeta `data/`
2. **Ejecutar todas las celdas** del notebook (Cell → Run All)
3. **Revisar los resultados** y visualizaciones generadas

## 📊 Contenido del Análisis

### 1. **Carga y Exploración Inicial**
- Lectura del archivo Excel
- Información básica del dataset
- Análisis de calidad de datos

### 2. **Análisis Descriptivo**
- Estadísticas de variables numéricas
- Análisis de variables categóricas
- Detección de valores atípicos

### 3. **Visualizaciones**
- Distribuciones de variables
- Gráficos de correlación
- Visualizaciones categóricas

### 4. **Análisis Específico CLUES**
- Identificación de variables de salud
- Análisis geográfico
- Análisis institucional
- Visualizaciones especializadas

### 5. **Conclusiones y Recomendaciones**
- Resumen de hallazgos principales
- Recomendaciones para uso de datos
- Próximos pasos sugeridos

## 📈 Resultados Principales

### 📊 **Estadísticas Generales**
- **58,616 establecimientos** de salud analizados
- **67 variables** con **71.4% completitud** general
- **32 entidades**, **2,319 municipios**, **12,386 localidades**

### 🗺️ **Distribución Geográfica**
- **Estado de México** lidera con 5,171 establecimientos (8.8%)
- **CDMX** (6.8%), **Veracruz** (6.7%), **Oaxaca** (6.4%) siguen en orden
- Distribución nacional relativamente equilibrada

### 🏥 **Tipos de Establecimientos**
- **81.9%** Consulta Externa (atención primaria)
- **11.0%** Hospitalización (atención especializada)
- **5.9%** Apoyo (laboratorios, diagnóstico)
- **1.2%** Asistencia Social

### 🏛️ **Análisis Institucional**
- **34.6%** Secretaría de Salud (sector público)
- **30.3%** Servicios Médicos Privados
- **18.0%** IMSS Bienestar
- **7.7%** IMSS tradicional

### 📊 **Cobertura y Operación**
- **69.8%** en operación activa
- **69.1%** urbano vs **30.9%** rural
- **81.5%** primer nivel de atención

## 🔧 Personalización

Para adaptar el análisis a otros datasets:

1. **Cambiar la ruta** del archivo de datos en la celda de carga
2. **Ajustar las palabras clave** de búsqueda para variables específicas
3. **Modificar las visualizaciones** según las necesidades del nuevo dataset

## 📤 Exportación de Resultados

### Opciones disponibles:

- **PDF**: `jupyter nbconvert --to pdf analisis_clues_2025.ipynb`
- **HTML**: `jupyter nbconvert --to html analisis_clues_2025.ipynb`
- **Presentación**: Copiar gráficos clave a PowerPoint/Google Slides

## ⚠️ Consideraciones Importantes

- **Privacidad**: Verificar que no hay datos sensibles antes de compartir
- **Calidad**: Validar la integridad de los datos CLUES antes del análisis
- **Actualizaciones**: El análisis está diseñado para datos de 2025

## 🤝 Soporte y Contribuciones

Para reportar problemas o sugerir mejoras:

1. **Documentar** la versión de Python y sistema operativo
2. **Incluir** el mensaje de error completo (si aplica)
3. **Describir** los pasos para reproducir el problema

## 🗺️ Roadmap - Versión 2.0

### 🚀 **Próximas Características**
- **🕒 Análisis temporal** con datos históricos CLUES
- **🗺️ Mapas interactivos** con Folium/Plotly
- **👥 Integración demográfica** (INEGI, CONAPO)
- **📊 Dashboard web** interactivo
- **🔍 Análisis de accesibilidad** geográfica
- **🤖 API REST** para consultas automatizadas
- **📈 Métricas de cobertura** poblacional
- **🔄 Pipelines automatizados** de actualización

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Por favor:

1. **Fork** el repositorio
2. **Crear branch** para tu feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** tus cambios (`git commit -m 'Add AmazingFeature'`)
4. **Push** al branch (`git push origin feature/AmazingFeature`)
5. **Abrir Pull Request**

### 📝 **Tipos de Contribuciones**
- 🐛 Reportar bugs
- 💡 Proponer nuevas funcionalidades
- 📚 Mejorar documentación
- 🧪 Agregar tests
- 🎨 Mejorar visualizaciones

## 📄 Licencia

Distribuido bajo la Licencia MIT. Ver `LICENSE` para más información.

## 📧 Contacto

**Aura García** - [@auragarciamx](https://github.com/auragarciamx)

**Link del Proyecto**: [https://github.com/auragarciamx/eda_clues](https://github.com/auragarciamx/eda_clues)

## 🙏 Agradecimientos

- **Secretaría de Salud** por la disponibilidad de datos CLUES
- **Comunidad Python** por las herramientas de análisis
- **Proyecto CLUES** por la sistematización de información de salud

---

**📅 Fecha de creación**: Diciembre 2024  
**🏷️ Versión**: 1.0.0  
**🐍 Lenguaje**: Python 3.7+  
**📊 Última actualización**: 14 de Diciembre, 2024 