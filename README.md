# upload-node-firebase
Codigo node para subir datos json en lote a firebase mediante una clave generada por firestore.

# Pasos:

#1. Crea un directoio en local para almacenar los 3 ficheros que requieres para la app node.
Debes tener 3 ficheros para poder subir los archivos:
    1. Clave generada por firestore; esa la encuantras en el servicio Firestore Database, te diriges a Configuracion del Proyecto
    ![image](https://github.com/user-attachments/assets/4cb1e1b3-c769-45ea-9df7-eaa1cc6b82b1)
    luego a Cuentas de Servicio
    ![image](https://github.com/user-attachments/assets/8976c0bf-cbbe-4c05-96af-c821c8cf5277)
    y despues a  " Generar nueva clave privada "
    ![image](https://github.com/user-attachments/assets/d6555096-80e5-4c9f-b1e0-bfe5dbf7aaee)

#2 Organiza un directorio con 3 ficheros con los siguientes nombres:
- upload.js ** este contiene el codigo que se ejecuta para subir la data. Aca cambiaremos el nombre de la collección que desemaos subir dentro del codigo. Name Colection.
- key_service.json ** este es el fichero que contiene la clave a conectarse con firebase (se bajará con un nombre muy largo el cual cambiaremos por este nombre key_service.json
- collection.json ** este contiene toda la data a subir separado en objetos json por comas.

#3 Una ves tengamos los ficheros organizados debemos entrar por la terminal con el comando cd y nombre de la carpeta y dentro ejecutamos el comando "node upload.js"



   

