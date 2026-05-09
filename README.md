# 🏪 Alura Store — Análisis de Ventas y Rendimiento

Análisis comparativo del rendimiento de 4 tiendas para identificar cuál tiene el menor desempeño y fundamentar una recomendación de negocio basada en datos.

> Challenge ONE Data Science LATAM — Alura Latam | Dataset provisto por Alura.

---

## 🎯 Objetivo

El dueño de Alura Store necesita decidir **qué tienda vender** para financiar un nuevo emprendimiento. El análisis evalúa 4 tiendas en base a facturación, satisfacción de clientes, productos más vendidos y costos logísticos para emitir una recomendación fundamentada.

---

## 📊 Resultados por tienda

### Facturación total

| Tienda | Facturación Total |
|---|---|
| 🥇 Tienda 1 | $1.150.880.400 |
| 🥈 Tienda 2 | $1.116.343.500 |
| 🥉 Tienda 3 | $1.098.019.600 |
| ⚠️ Tienda 4 | $1.038.375.700 |

### Calificación promedio de clientes

| Tienda | Calificación |
|---|---|
| Tienda 1 | ⭐ 3.98 |
| Tienda 2 | ⭐ 4.04 |
| Tienda 3 | ⭐ 4.05 |
| Tienda 4 | ⭐ 4.00 |

### Costo de envío promedio

| Tienda | Costo promedio |
|---|---|
| Tienda 1 | $26.018,61 |
| Tienda 2 | $25.216,24 |
| Tienda 3 | $24.805,68 |
| Tienda 4 | $23.459,46 |

### Productos más y menos vendidos

| Tienda | Más vendido | Menos vendido |
|---|---|---|
| Tienda 1 | Microondas | Auriculares con micrófono |
| Tienda 2 | Iniciando en programación | Juego de mesa |
| Tienda 3 | Kit de bancas | Bloques de construcción |
| Tienda 4 | Cama box | Guitarra eléctrica |

---

## 💡 Recomendación final

**Se recomienda vender la Tienda 4.**

Presenta el peor desempeño en los indicadores más críticos:
- **Facturación más baja** de las 4 tiendas ($1.038.375.700 — $112M menos que Tienda 1)
- **Menor costo de envío** sugiere menor volumen o alcance geográfico reducido
- Mix de productos sin un líder claro de categoría

Las Tiendas 2 y 3 tienen mejor calificación promedio de clientes y mayor potencial de crecimiento, por lo que conservarlas es estratégicamente más valioso.

---

## 🔍 Análisis realizado

- **Facturación total** por tienda — comparación de ingresos
- **Ventas por categoría de producto** — identificación de categorías dominantes
- **Calificación promedio** — satisfacción del cliente por tienda
- **Productos más y menos vendidos** — análisis de mix de productos
- **Costo de envío promedio** — eficiencia logística por tienda

---

## 🛠️ Stack tecnológico

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data-150458?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

- **Librerías:** pandas
- **Entorno:** Google Colab
- **Datos:** 4 datasets CSV con datos de ventas por tienda
- **Técnicas:** agrupaciones, value_counts, comparación multi-tienda

---

## 📁 Estructura del proyecto

```
alura-store-analisis-ventas/
│
├── AluraStoreLatam.ipynb   # Notebook principal
└── README.md
```

---

## 👩‍💻 Autora

**Antonella Ríos**
Junior Data Analyst | Python · SQL · Power BI · Machine Learning
[LinkedIn](https://www.linkedin.com/in/antonellarios) · [GitHub](https://github.com/antonellarios)
