ANALISIS DE VENTAS FICTICIAS
SET DATOS: https://www.kaggle.com/datasets/kyanyoga/sample-sales-data?resource=download

# 📖 Diccionario de Datos - Ventas

| **Nombre**          | **Tipo de dato** | **Descripción**                                                                                              | **Nombre en español**          |
|---------------------|------------------|-------------------------------------------------------------------------------------------------------------|-------------------------------|
| **ORDERNUMBER**     | int              | Número único que identifica cada transacción realizada.                                                      | Numero_Orden                  |
| **QUANTITYORDERED** | int              | Cantidad de unidades del producto solicitadas en la transacción.                                             | Cantidad_Ordenada             |
| **PRICEEACH**       | int              | Precio unitario de cada producto en la transacción.                                                          | Precio_Unitario               |
| **ORDERLINENUMBER** | int              | Número secuencial del producto dentro de la orden (1, 2, 3…) → Indica cuántos productos se compraron en esa orden. | Numero_Linea_Orden            |
| **SALES**           | int              | Monto total de la venta → se calcula como **QUANTITYORDERED × PRICEEACH**.                                   | Venta                         |
| **ORDERDATE**       | date             | Fecha en la que se realizó la transacción.                                                                   | Fecha_Orden                   |
| **STATUS**          | string           | Estado de la transacción → *Cancelled, In Process, Disputed, On Hold, Resolved, Shipped*.                    | Estado_Orden                  |
| **PRODUCTLINE**     | string           | Línea o categoría a la que pertenece el producto → *Classic Cars, Planes, Ships, Trains, Vintage Cars*.      | Categoria_Producto            |
| **MSRP**            | int              | Precio de venta sugerido por el proveedor o fabricante.                                                      | Precio_Venta_Sugerido         |
| **PRODUCTCODE**     | string           | Código único que identifica cada producto → existen 109 productos únicos en total.                           | Codigo_Producto               |
| **CUSTOMERNAME**    | string           | Nombre completo del cliente → existen 92 clientes únicos en total.                                           | Cliente                       |
| **PHONE**           | string           | Número de contacto del cliente.                                                                              | Telefono_Cliente              |
| **ADDRESSLINE1**    | string           | Dirección principal del domicilio del cliente.                                                              | Direccion_Principal_Cliente   |
| **ADDRESSLINE2**    | string           | Dirección secundaria del domicilio del cliente (si aplica).                                                 | Direccion_Secundaria_Cliente  |
| **CITY**            | string           | Ciudad de residencia del cliente → existen registros de 73 ciudades distintas.                              | Ciudad_Cliente                |
| **STATE**           | string           | Abreviatura del estado o provincia del cliente.                                                             | Estado_Cliente                |
| **POSTALCODE**      | string           | Código postal del cliente.                                                                                   | Codigo_Postal                 |
| **COUNTRY**         | string           | País de residencia del cliente.                                                                              | Pais_Cliente                  |
| **TERRITORY**       | string           | Territorio o región comercial asignada al cliente (abreviado).                                               | Territorio_Cliente            |
| **CONTACTLASTNAME** | string           | Apellido del cliente.                                                                                        | Apellido_Cliente              |
| **CONTACTFIRSTNAME**| string           | Primer nombre del cliente.                                                                                   | Nombre_Cliente                |
| **DEALSIZE**        | string           | Tamaño del pedido → *Large, Medium, Small*.                                                                 | Tamaño_Venta                  |
