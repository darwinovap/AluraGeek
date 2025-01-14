# Hola 👋 Bienvenido a ReseñaPlus.
# Proyecto Para AluraGeek Challenge.

## ✨ Guía de interacción ✨
El proyecto se basa en una tienda de reseñas de productos, con varias funcionalidades descritas a continuación: 

    1. Página de inicio: En esta página encontrarás una barra de navegación con el logo y los botones para abrir los cuadros emergentes de "Iniciar sesión" y "Registrarse", seguido por un carrusel de imágenes y, finalmente, el contenido de los productos, cada uno con una imagen, descripción y el precio promedio de mercado. Cada producto tiene un botón para ver detalles, donde se mostrarán las calificaciones y la opción de agregar una nueva calificación, habilitada solo para aquellos usuarios registrados que hayan iniciado sesión.

![Screenshot from 2024-11-12 01-05-05](https://github.com/user-attachments/assets/8fabfc33-602e-436f-b77f-140b2ce8d2b2)

![Screenshot from 2024-11-12 01-04-56](https://github.com/user-attachments/assets/793ee179-f530-4cb8-b631-8fb5984b99be)



    2. Mis productos: En esta sección, los usuarios que hayan iniciado sesión y deseen cargar productos, o que ya hayan cargado productos, pueden hacerlo. También pueden editar la información de los productos previamente cargados o eliminarlos si así lo desean.
    
[Screencast from 2024-11-12 00-59-50.webm](https://github.com/user-attachments/assets/692d109f-e9e5-4ee2-8162-920d26e3aa55)

    3. Calificaciones:  Estas son de vista pública y pueden ser vistas por cualquier persona sin necesidad de haber iniciado sesión. Sin embargo, cuando alguien desee agregar su reseña y calificación, deberá iniciar sesión.
    
[Screencast from 2024-11-12 00-22-18.webm](https://github.com/user-attachments/assets/330437ae-0df8-476e-8913-a567004a57de)

## ✨ Dependencias y cómo correrlo ✨

### Dependencias

    Las puedes encontrar en el package.json pero las listamos aquí para hacerte este proceso más amigable:

        ✨ Ejs ^3.1.10: Nos permite generar HTML dinámico en el lado del servidor, especialmente utilizado en el entorno de Node.js.
        ✨ Express ^4.21.1: Este framework facilita el desarrollo de aplicaciones web y APIs, proporcionándonos una estructura organizada y simplificada para manejar solicitudes y respuestas HTTP en Node.js.
        ✨Multer ^1.4.5-lts.1: Se utiliza principalmente para la carga de imágenes en el proyecto, lo que nos permite crear un entorno visualmente más amigable.
        ✨ MyQSL (^2.18.1) y MySQL 2 (^3.11.3): Se utilizan para el manejo de bases de datos.
        ✨ Nodemon ^3.1.7: Mejora la eficiencia en el flujo de trabajo durante el desarrollo.
        ✨ Cookie ^1.0.1: Gestiona las cookies de usuario para mantener sesiones y preferencias, mejorando la experiencia del usuario.
        ✨ Crypto ^1.0.1: Proporciona funcionalidades criptográficas esenciales para asegurar la información y las transacciones dentro de la aplicación.
        
### ¿Cómo correr el proyecto?
    
    1. Crear una base de datos en MySQL llamada "tienda".
    2. Asegurarse de que el puerto 5000 de localhost esté disponible.
    3. Cargar el archivo .sql llamado "tienda" en la base de datos que acabas de crear.
    4. Ejecutar nodemon en la terminal para iniciar el servidor.
    5. Navegar a http://localhost:5000/products para acceder a la aplicación.
    6. ¡Disfruta de este maravilloso programa! 

https://github.com/user-attachments/assets/809c3cf3-2e8b-4680-9b0e-d952b66f3a46

