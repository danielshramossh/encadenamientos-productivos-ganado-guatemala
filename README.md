# Encadenamientos Productivos de la Cría de Ganado Bovino (AE012) — Guatemala 2023

Análisis de redes de los encadenamientos productivos de la actividad ganadera guatemalteca (AE012: cría de ganado bovino, excepto búfalos), basado en el Cuadro de Oferta y Utilización (COU) 2023 del Banco de Guatemala, con enfoque especial en el agua natural como recurso transversal.

## 🎯 Objetivo

Mapear y analizar las interdependencias sectoriales de la actividad ganadera (AE012) dentro del Sistema de Cuentas Nacionales de Guatemala, identificando su estructura de oferta, su consumo intermedio (demanda) y las oportunidades de fortalecimiento mediante prácticas sostenibles.

## 📊 Principales hallazgos (2023)

- **PIB de la actividad:** Q 5,825.68 millones (Valor Agregado Bruto: Q 5,822.7 millones)
- **Oferta total:** Q 9,927.1 millones — liderada por ganado bovino vivo (70.5%) y leche cruda (29.5%)
- **Consumo intermedio (demanda):** Q 4,100 millones — liderado por alimentos para animales (40%) y medicamentos veterinarios (14.8%)
- **Empleo generado:** ~98,000 empleos

## 🕸️ Análisis de redes con Pajek

El componente central del proyecto es la modelación de los encadenamientos productivos como **redes de interdependencia**, visualizando la actividad AE012 como nodo central conectado con sus productos de oferta y sus insumos de demanda.

| Archivo | Red modelada |
|---|---|
| `Oferta.paj` | Red de oferta: AE012 → Ganado bovino, Leche cruda, Agua natural (4 vértices) |
| `Demanda.paj` | Red de demanda/consumo intermedio: AE012 → 6 principales insumos (Tabaco, alimentación animal, productos farmacéuticos, etc.) |
| `ganado_bovino_v4_.paj` | Red completa e integrada: oferta y demanda conjuntas (43 vértices, incluyendo todos los productos codificados según Nomenclatura de Productos para Guatemala - NPG) |

## 📂 Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `Análisis_de_Cuentas_Nacionales.pdf` | Informe completo: introducción, análisis de oferta, demanda y su relación, conclusiones y anexos con tablas del COU |
| `Resumen_de_Cuadros_de_Oferta_y_Utilización.xlsx` | Datos base extraídos del COU 2023, organizados en 4 hojas (Ganado bovino general, Oferta, Demanda, Agua) |
| `Oferta.paj`, `Demanda.paj`, `ganado_bovino_v4_.paj` | Archivos de red de Pajek utilizados para generar las gráficas de encadenamiento productivo |

## 🛠️ Herramientas utilizadas

- **Pajek** — software de análisis y visualización de redes sociales/económicas, usado para modelar los encadenamientos productivos como grafos
- **Microsoft Excel** — procesamiento de los cuadros de oferta y utilización

## ▶️ Cómo abrir los archivos

**Redes (`.paj`):**
1. Descarga [Pajek](http://mrvar.fdv.uni-lj.si/pajek/) (gratuito)
2. Abre los archivos `.paj` desde File → Network → Read Network
3. Genera la visualización desde el menú Draw

**Excel:** abre directamente con Microsoft Excel o Google Sheets.

## 📜 Fuente de datos

Cuadro de Oferta y Utilización (COU) 2023, Cuentas Nacionales, Banco de Guatemala.

## ⚠️ Nota

Cifras preliminares (p/) según metodología del Sistema de Cuentas Nacionales (SCN). El análisis e interpretación son elaboración propia con fines académicos.

---
*Proyecto desarrollado para el curso de Cuentas Nacionales, Facultad de Ciencias Económicas, UMG.*
