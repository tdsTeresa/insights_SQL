<h2>🟡 Descripción general:</h2>
<br>
Este repositorio contiene la propuesta de un modelo de base de datos diseñado para almacenar una muestra de datos con fines educativos de la empresa Reckitt.
A partir de este modelo se realizaron consultas SQL que permiten combinar diferentes tablas y obtener insights clave sobre la información disponible. 
El objetivo es facilitar la comprensión de cómo estructurar una base de datos relacional y aplicar consultas analíticas para extraer información relevante.</a>

<br><br>
<h2>⚙️Tecnologías: </h2>
<br>
    • SQL Server <br>
    • Wondershare EdrawMax <br>
<br><br>

<h2>🖇️ Fuente: </h2><br>
⭐ EBAC - Escuela británica de artes creativas y tecnología.
<br>
<br><br>
<h2>🧩 Tablas creadas:</h2
<br>
• Sales (ID_SALE, ITEM_CODE, TOTAL_UNIT_SALES, TOTAL_VALUE_SALES, SALE_DATE, ID_REGION).<br>
• Products (ITEM_CODE, ITEM_DESCRIPTION, ID_BRAND, ID_CATEGORY, ID_FORMAT).<br>
• Brands (ID_BRAND, BRAND, MANUFACTURER).<br>
• Category (ID_CATEGORY, CATEGORY).<br>
• Formats (ID_FORMAT, FORMAT_NAME, ATTR1, ATTR2, ATTR3, ID_CATEGORY, ID_SEGMENT)<br>
• Segment (ID_SEGMENT, SEGMENT).<br>
• Region (ID_REGION, REGION_NAME).<br>
<br>
<br>
<br>
<h2>📊 Actividades: </h2>
<br>
  • Creación de modelo de datos lógico y físico (base de datos relacional).
  • Importación de datos. <br>
  • Consultas a la base de datos para extraer información en un contexto empresarial. 
<br>
<br>
<h2>Diagrama Entidad - Relación</h2>
<br>
<img width="700" height="761" alt="image" src="https://github.com/tdsTeresa/insights_SQL/blob/main/images/ER.png" />
<br><br>
<h2>Consultas realizadas: </h2>
<br>
▫️Ventas por categoría<br><br>

![Ventas por categoría](images/ventas_categoria.png)
<br><br><br>
▫️Ventas por descripción del producto<br><br>
![Ventas por descripción del producto](images/ventas_producto.png)
<br><br><br>
▫️Ventas por formato de producto<br><br>
![Alta Tecnologia](images/formato.png)
<br><br><br>
▫️Ventas por región <br><br>
![Clientes que han adquirido impresoras](images/region.png)
<br><br><br>
▫️Ventas por año<br><br>
![ventas por año](images/periodos.png)
<br><br><br>
▫️Ventas por mes<br><br>
![ventas por año](images/mes.png)
<br><br><br>
<h2>🔶 Observaciones generales:</h2>
<br>
• El periodo analizado comienza en enero de 2022 y termina en julio 2023, razón por la cual el año con más ventas ha sido 2022.<br> 
• Los productos más vendidos fueron Cloralex, Vanish y Clorox, siendo Cloralex en su presentación de botella 3.750 ml la más vendida. <br>
• Los formatos más vendidos fueron líquido, gel y polvo.
<br>



