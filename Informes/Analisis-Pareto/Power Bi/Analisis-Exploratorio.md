# 📊 Análisis Exploratorio de Datos

## 🗂️ Análisis de valores nulos o faltantes

- **ADDRESSLINE2** → 2.521 valores en blanco de 2.823 registros (~89%).  
  📌 *Es una dirección secundaria, por lo que es normal que muchos clientes no hayan brindado este dato.*  
  🔧 Transformación: Reemplazar valores vacíos por `"N/A"`.

- **STATE** → 1.486 registros vacíos (~53%).  
  📌 *Clientes ubicados en países o regiones sin división por estados.*  
  🔧 Transformación: Reemplazar valores vacíos por `"N/A"`.

---

## 📊 Análisis descriptivo

- **Cantidad de productos por orden (QUANTITYORDERED):**  
  Rango entre **6** y **97** unidades por orden.

- **Precio unitario de productos (PRICEEACH):**  
  Desde **$37** hasta **$9.991**.

- **Ventas por transacción (SALES):**  
  Desde **$777** hasta **$977.403**.

---

## ❓ Preguntas exploratorias

### ✅ ¿Cuál es la venta total?
- **Ventas totales:** **$709M**
- **Período de análisis:** 2 años y 5 meses → 2023, 2024 y parte de 2025.
- 📈 **Crecimiento 2025 vs 2024:** +24% (parcial con 5 meses).
- **Mes con mayores ingresos:** **Noviembre**

---

### ✅ ¿Qué línea de productos genera más ingresos?
- **Top 2 líneas → representan más del 50% de las ventas:**
  - **Classic Cars:** 39% → $276M
  - **Vintage Cars:** 18.4% → $130M
- 📌 **Línea menos rentable:** *Trains → solo 2% ($17M)*

---

### ✅ ¿Cuál es el estado de las órdenes?
| Estado     | Cantidad de órdenes | Participación en ventas |
|------------|---------------------|-------------------------|
| Canceladas | 4                   | ~2%                    |
| En proceso | 6                   | ~1%                    |
| En espera  | 4                   | ~1%                    |
| Entregadas | 286                 | ~92%                   |

➡️ **Observación:** Buena gestión logística, pero hay **21 órdenes no entregadas** → se recomienda revisar causas.

---

### ✅ ¿Cómo se distribuyen las cantidades ordenadas por tamaño de pedido?

📊 **Distribución por tamaño de pedido:**
- **Medium → 53%** (**52.519 unidades**)
- **Small → 39%**
- **Large → 7%**

➡️ Las ventas también siguen esta tendencia → **pedidos pequeños y medianos representan ~90% de los ingresos.**

---

## 📝 Conclusiones iniciales

- El negocio **gira principalmente en torno a autos clásicos y antiguos** → posible ventaja competitiva.
- **Noviembre destaca como el mes fuerte de ventas** → investigar si es estacionalidad o campañas específicas.
- **Trenes genera poco ingreso → revisar si conviene mantener inventario.**
- **Revisar el estado de las 21 órdenes pendientes.**

Variables numericas
    -- QUANTITYORDERED
    -- SALES

variables categoricas:
    -- CITY
    -- COUNTRY
    -- CUSTOMERNAME
    -- DEALSIZE
    -- ORDERDATE
    -- PRODUCTCODE
    -- LINEPRODUCT
    -- STATE
    -- STATUS





