# Dashboard Interactivo de Ingresos y Clientes (2007–2010) en Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)
![Estado del Proyecto](https://img.shields.io/badge/Estado-Completo-brightgreen?style=for-the-badge)
![Tipo-Ejercicio](https://img.shields.io/badge/Tipo-Ejercicio%20educativo-blue?style=for-the-badge)

# 📊 Dashboard de Ingresos y Clientes – Power BI

## 📚 Índice

- [📄 Descripción del Proyecto](#-descripción-del-proyecto)
- [✅ Estado del Proyecto](#-estado-del-proyecto)
- [🎥 Demostración de Funciones y Aplicaciones](#-demostración-de-funciones-y-aplicaciones)
- [🔐 Acceso al Proyecto](#-acceso-al-proyecto)
- [🛠 Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [👤 Persona Desarrolladora](#-persona-desarrolladora)

## 📄 Descripción del Proyecto

Este dashboard fue desarrollado como parte de un ejercicio formativo en visualización de datos con **Power BI**. Los datos utilizados fueron proporcionados por el centro de formación, con fines exclusivamente educativos.  
El objetivo del proyecto es familiarizarse con la creación de dashboards interactivos, aplicando conceptos como modelado de datos y visualizaciones dinámicas.

## ✅ Estado del Proyecto

🟢 **Proyecto Completado**  
El ejercicio está finalizado y funcional, incluyendo filtros interactivos, múltiples visualizaciones y segmentadores de datos. Puede usarse como plantilla para futuros proyectos más avanzados.

## 🎥 Demostración de Funciones y Aplicaciones

### 📌 Visualizaciones implementadas:

1. **KPI de ingreso total** (`Tarjeta`)
2. **Gráfico de columnas apiladas**: Ingreso total por mes y año
3. **Gráfico combinado**: Ingreso total y costo total por cliente y año
4. **Gráfico de pastel**: Recuento de cliente por año
5. **Gráfico de barras horizontales**: Ingreso total por cliente y año
6. **Tabla**: Listado de clientes por año y mes

### 🧩 Pasos para construir este dashboard en Power BI:

1. **Cargar datos desde archivo Excel o CSV**
   - Columnas recomendadas: `Cliente`, `Año`, `Mes`, `Ingreso`, `Costo`, `RUC`, `Tipo de comprobante`
   - Realizar limpieza y transformación básica con Power Query

2. **Modelado de datos**
   - Establecer relaciones si se usan múltiples tablas (relaciones entre `Cliente`, `Fecha`, etc.)

     2.1. **Agregar visualizaciones**:
        - **Tarjeta**: para mostrar el ingreso total
        - **Gráfico de columnas apiladas**:
        -    Eje X: `Mes`
        -    Valores: `Ingreso Total`
        -    Leyenda: `Año`
        - **Gráfico combinado (columnas + línea)**:
        -    Eje X: `Cliente`
        -    Valores: `Ingreso Total` (columna), `Costo Total` (línea)
        -    Leyenda: `Año`
        - **Gráfico de pastel**:
        -    Valores: `% Clientes`
        -    Leyenda: `Año`
        -  **Gráfico de barras horizontales**:
        -     Eje Y: `Cliente`
        -    Valores: `Ingreso Total`
        -    Leyenda: `Año`
        - **Tabla**:
        -    Columnas: `Cliente`, `Año`, `Mes`

      2.2. **Agregar segmentadores interactivos**:
        -    Filtros tipo *slicer* para los siguientes campos:
        -       `Año`
        -      `Tipo de cliente`
        -     `RUC`
        -    `Tipo de comprobante`
        
3. **Crear medidas DAX**:
   DAX
Ingreso Total = SUM('Ventas'[Ingreso])
Costo Total = SUM('Ventas'[Costo])

## 🔐 Acceso al Proyecto

> ⚠️
> Por motivos de privacidad y licencia, no se distribuye el archivo `.pbix` original públicamente.  
> Sin embargo, puedes solicitar una **plantilla de ejemplo** contactándome directamente.

## 🛠 Tecnologías Utilizadas

- **Power BI Desktop** – Herramienta principal de visualización
- **Power Query Editor** – Transformación y limpieza de datos
- **Lenguaje DAX** – Cálculos y medidas personalizadas
- **Visualizaciones nativas de Power BI**
- **Datos ficticios o anonimizados** – Proporcionados por la institución formativa

## 👤 Persona Desarrolladora

📛 **[ Selene G.B.]**  
🎓 Estudiante de Ingeniería Ambiental – Universidad Nacional Agraria La Molina  
💡 Gestión de proyectos, sostenibilidad y herramientas digitales.  
📬 Contacto: [seleneheather.gb@gmail.com]  
🌐 GitHub: [https://github.com/tuusuario](https://github.com/Jeder14/Proyecto-1-Power-Bi.git)

---

> *Este proyecto representa un ejercicio práctico para consolidar conocimientos en Power BI, y forma parte de mi proceso formativo en análisis de datos para la sostenibilidad ambiental.*

