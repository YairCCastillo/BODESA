# BODESA
Análisis Descriptivo:
Veamos los datos
 ![image](https://github.com/user-attachments/assets/13cc4d64-5342-4224-bffe-26f75f8ced1c)

Se puede observar que tenemos 17 variables y contiene un total de 124751 datos.
Hacemos una revisión de lo que pueden significar las variables:
𝐀ñ𝐨 𝐧𝐚𝐭𝐮𝐫𝐚𝐥/𝐌𝐞𝐬: Representa el año y mes de los datos.
𝐃𝐞𝐩: Código de departamento.
𝐃𝐞𝐩𝐚𝐫𝐭𝐚𝐦𝐞𝐧𝐭𝐨: Nombre del departamento (ACC. DEPORTIVOS significa accesorios deportivos).
𝐆𝐫𝐮𝐩𝐨 𝐚𝐫𝐭í𝐜𝐮𝐥𝐨𝐬:  Identificador para un grupo específico de artículos.
𝐆𝐫𝐮𝐩𝐨 𝐚𝐫𝐭í𝐜𝐮𝐥𝐨𝐬:  Identificador adicional del grupo de productos como puede ser el nombre/tipo del producto.
𝐌𝐚𝐫𝐜𝐚: Nombre de la marca.
𝐂𝐞𝐧𝐭𝐫𝐨: Código de la tienda.
𝐓𝐢𝐞𝐧𝐝𝐚: Nombre de la tienda específica con su ubicación.
𝐅𝐨𝐫𝐦𝐚𝐭𝐨 𝐝𝐞 𝐭𝐢𝐞𝐧𝐝𝐚: Nombre de la tienda.
𝐑𝐞𝐠𝐢ó𝐧: Estado de donde se encuentra la tienda.
𝐂𝐚𝐝𝐞𝐧𝐚: Cadena de la tienda.
𝐕𝐞𝐧𝐭𝐚: Monto de ventas.
𝐕𝐭𝐚 𝐂𝐭𝐨: Costo de las ventas.
𝐔𝐭𝐢𝐥𝐢𝐝𝐚𝐝: Ganancia, calculada como la diferencia entre los ingresos de Venta y Vta Cto.
𝐈𝐧𝐯𝐞𝐧𝐭𝐚𝐫𝐢𝐨 𝐜𝐭𝐨: Costo del inventario.
𝐕𝐭𝐚 𝐩𝐳𝐚𝐬: Cantidad de piezas vendidas.
𝐈𝐧𝐯𝐞𝐧𝐭𝐚𝐫𝐢𝐨 𝐩𝐳𝐚𝐬: Cantidad de piezas en el inventario.
Primero se hará un análisis de correlación entre las variables o ver sus rangos de valores porque parece que podemos omitir algunas columnas que no nos aportan.
El primer ejemplo sería quitar la columna ‘Departamento’ y ‘Dep’, que solo tienen un valor.
Debido a que hay valores NaN en las columnas de "Venta", "Vta Cto", "Utilidad" y "Vta pzas", estos los podemos llenar con 0 porque justamente cuanto no hay datos en la variable "Vta Pzas" tampoco hay información en las variables "Venta", "Vta Cto", "Utilidad", lo cual tiene sentido ya que si no hay venta de piezas no hay ganancias.

Matriz de correlación para ver cuáles variables se están repitiendo o no están aportando información adicional
![image](https://github.com/user-attachments/assets/d79ade92-0142-46df-bdb2-898c4f1eaf82)
Se puede observar que en las categóricas hay una relación de 1, por ejemplo, Centro tiene relación de 1 con Tienda, Formato de tienda, Región y Cadena. Entonces utilizando esto se podría quitar las demás variables y solo dejar Tienda, ya que esa información no nos podría importar más información. También hay una relación perfecta entre Grupo artículos.1 y Grupo artículos.

Hacemos los pronósticos para el año 2024 para ventas y utilidades
![image](https://github.com/user-attachments/assets/ff22f5ae-ce9e-4f6e-a8f2-9255d151bc72)
![image](https://github.com/user-attachments/assets/a3881d70-31ee-470a-9df1-14fa34fb2ccf)
![image](https://github.com/user-attachments/assets/fee16580-f5c6-40ec-90cc-da37585deceb)



