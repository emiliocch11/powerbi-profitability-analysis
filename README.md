# Análisis de Rentabilidad | Power BI

**Proyecto de Business Intelligence · Data Analyst Expert — Ciencia de Datos Ecuador**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power_Query-008272?style=flat-square)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat-square)

## Descripción

Proyecto académico desarrollado durante un módulo de cuatro semanas con entregas progresivas. El informe de Power BI se titula **Proyecto Análisis Rentabilidad** y presenta indicadores comerciales y financieros de un modelo de ventas. El propósito es facilitar la exploración de ingresos, utilidad, rentabilidad y cumplimiento de metas mediante visualizaciones interactivas.

**Autor:** Emilio Caldas  
**Contexto:** Formación Data Analyst Expert, Ciencia de Datos Ecuador  
**Tipo de fuente de datos:** [COMPLETAR: origen y naturaleza de los datos; no se ha verificado si son reales o sintéticos]

## Objetivos

- Preparar y transformar datos en Power Query mediante un proceso ETL.
- Construir un modelo de datos que permita cruzar información comercial.
- Analizar indicadores financieros y de rentabilidad.
- Facilitar la exploración por periodos y otras dimensiones del negocio.

## Desarrollo por entregas

### Entrega 1 — Importación y transformación

El encargo contempló importar, explorar, evaluar calidad, limpiar, estandarizar e integrar los datos mediante Power Query. **Pendiente de documentar:** transformaciones específicas ejecutadas y reglas de negocio aplicadas, a partir de la vista de Power Query o capturas.

### Entrega 2 — Modelo y cálculos

El encargo solicitó una tabla de hechos y al menos tres dimensiones, medidas, columnas o tablas calculadas y un caso de parámetro de campos. En las referencias del informe se observan los siguientes elementos:

- `Fact_Ventas`
- `Dim_Calendario`
- `Dim_Producto`
- `Dim_Sucursal`
- `Dim_Vendedor`
- `Cascada Categorias`

Estas referencias confirman que los objetos aparecen en las visualizaciones; **no constituyen por sí solas una verificación de relaciones, cardinalidad, expresiones DAX o parámetros de campos**.

### Entregas 3 y final — Reporte visual

El PDF de instrucciones finales solicita un informe con portada, al menos cinco visualizaciones (incluyendo tarjetas, tendencias y Top N), dos medidas calculadas, marcadores y navegación por botones.

El archivo `.pbix` contiene **dos páginas** (`Intro` y `Página 2`) y en la segunda página se identifican:

- Tarjetas: **Ingresos Netos**, **Utilidad Neta**, **% Rentabilidad**, **Venta Promedio**, **Meta de Ventas**.
- Indicador: **% Cumplimiento Meta**.
- Gráfico de cascada: **Cascada Ingresos → Utilidad**.
- Gráfico de líneas: **Evolución KPIs**.
- Gráfico de columnas agrupadas y tabla de detalle.
- Segmentador temporal con año, trimestre, mes y día.

**Por verificar en Power BI Desktop:** funcionamiento de interacciones, marcadores y botones; presencia de análisis Top N y parámetros de campos; medidas DAX exactas y valores numéricos de los KPIs.

## Modelo de análisis

| Objeto identificado | Uso en el informe |
| --- | --- |
| `Fact_Ventas` | Medidas comerciales y financieras |
| `Dim_Calendario` | Exploración por año, trimestre, mes y día |
| `Dim_Producto` | Análisis por categoría |
| `Dim_Sucursal` | Análisis por sucursal |
| `Dim_Vendedor` | Análisis por vendedor |
| `Cascada Categorias` | Categorías del gráfico de cascada |

## Indicadores

- Ingresos netos
- Utilidad neta
- Porcentaje de rentabilidad
- Venta promedio
- Meta de ventas
- Porcentaje de cumplimiento de meta

No se publican cifras ni conclusiones numéricas porque no se pudieron confirmar desde los archivos disponibles sin ejecutar el modelo en Power BI Desktop.

## Archivos

- [`report/analisis-rentabilidad.pbix`](report/analisis-rentabilidad.pbix) — informe editable en Power BI Desktop.
- [`docs/requisitos-proyecto-final.pdf`](docs/requisitos-proyecto-final.pdf) — consigna de entrega final.

## Cómo explorar el informe

1. Descarga el archivo `.pbix` desde la carpeta `report/`.
2. Ábrelo con **Microsoft Power BI Desktop** (Windows).
3. Revisa la portada y navega al informe de rentabilidad.
4. Explora el segmentador de fechas y los gráficos.
5. Si intentas actualizar los datos, comprueba las rutas y credenciales de las fuentes en Power Query.

## Próximas mejoras de documentación

- [ ] Incorporar captura de portada y dashboard en `assets/`.
- [ ] Documentar origen de datos, registros y transformaciones ETL efectivamente realizadas.
- [ ] Añadir diagrama y explicación validada de relaciones del modelo.
- [ ] Incluir las fórmulas DAX relevantes y explicar el denominador de cada KPI.
- [ ] Agregar hallazgos y recomendaciones basados en cifras verificadas.
- [ ] Confirmar marcadores, navegación, Top N y parámetros de campos en Power BI Desktop.

---

**Emilio Caldas** · [LinkedIn](https://www.linkedin.com/in/emiliocaldas/)
