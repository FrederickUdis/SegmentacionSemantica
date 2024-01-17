# SegmentacionSemantica
Este repositorio se centra en la implementación de algoritmos de segmentación semántica para la identificación de objetos en videos. Para lograr esto, hemos utilizado algoritmos previamente entrenados utilizando el ampliamente reconocido dataset COCO. Además, se ha hecho uso de la biblioteca nnabla de OpenCV-Python, aprovechando sus avanzadas capacidades en el procesamiento y análisis de imágenes. Este enfoque permite una detección eficiente y precisa de objetos, abriendo un amplio abanico de aplicaciones en el campo del procesamiento de video y la visión por computadora.


## Comenzando 🚀

Para obtener una copia del proyecto solo es necesario clonar al git

### Pre-requisitos 📋

Python
OpenCV-Python
nnabla (Neural Network Libraries by Sony)

## Construido con 🛠️
_las herramientas utilizadas para la creacion del proyecto son

* [PYTHON]([https://angular.io/](https://go.dev/)) - Lenguaje de Programación Utilizado
* [COLAB]((https://colab.research.google.com/?hl=es)) - Entorno de desarrollo
* [OpenCV](https://opencv.org/) - Biblioteca de Visión por Computadora
* [nnabla]((https://nnabla.org/)) - Biblioteca de Redes Neuronales de Sony



## Autores ✒️



* **Edvard Frederick Bareño** - *Trabajo Total* - [FrederickUdis](https://github.com/FrederickUdis)

 

## Evidencias
Productos:

POST /productos: Crea un nuevo producto.

![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/d9a867c3-9669-4e5b-a411-f125423e06be)


GET /productos: Obtiene la lista de productos existentes.

![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/ef9c773d-560d-4547-af8f-18622b615989)

Producto Individual:

PUT /productos/:id: Actualiza un producto existente por su ID.

![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/21d771c8-d19a-43ce-b27c-3edbe10d9745)
![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/3302f146-f3bc-4106-bd69-04234ae1217c)

DELETE /productos/:id: Elimina un producto existente por su ID.

![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/88fd10f0-1971-4567-9056-5495377a2c3d)

Consumidores:

POST /consumidores: Crea un nuevo consumidor.

![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/253a2f47-65d0-40eb-96bd-b3d99124b940)
![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/c03f3198-995c-4912-a43e-00f563086471)


GET /consumidores: Obtiene la lista de consumidores existentes.

![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/04ed9465-34aa-4cec-ad71-a18bcf8501ae)

Consumidor Individual:
PUT /consumidores/:id: Actualiza un consumidor existente por su ID.
![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/9ca50336-926d-46a8-8032-3511ba427772)
![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/947f21fa-fab3-4709-853f-1ac9fa951e6e)

Órdenes:

POST /ordenes: Crea una nueva orden.
![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/c94c7d18-8d09-4903-8fb7-62447c5dfa5e)
![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/c1a57619-6aac-4adb-8dfb-71d48cae41f7)

GET /ordenes: Obtiene la lista de órdenes existentes.
![image](https://github.com/FrederickUdis/Prueba-Oas/assets/30853509/5969a844-0151-40e3-93a4-ac36f9c59929)

# Esquema Base de datos
Diseño de Base de Datos basado en Modelos
Esquema Conceptual:
1. Consumidor
ID (Clave Primaria)
Nombre
Email (Único)
2. Orden
ID (Clave Primaria)
Consumidor_ID (Clave Externa que referencia a Consumidor)
Producto_ID (Clave Externa que referencia a Producto)
Cantidad
Total
3. Producto
ID (Clave Primaria)
Descripcion
Precio
Stock
Relaciones:
Un Consumidor puede tener muchas Ordenes pero una Orden pertenece a un único Consumidor. Esto es una relación uno a muchos entre Consumidor y Orden.

Un Producto puede estar en muchas Ordenes pero una Orden tiene un único Producto. Esto es una relación uno a muchos entre Producto y Orden.




## Expresiones de Gratitud 🎁

* Un agradecimiento especial a la Oficina Asesora de Sistemas por presentar constantes desafíos y oportunidades de crecimiento.
