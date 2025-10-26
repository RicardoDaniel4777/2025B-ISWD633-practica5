# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 
# COMPLETAR CON UNA CAPTURA DE PANTALLA LUEGO DE EJECUTAR EL ARCHIVO
<img width="1916" height="871" alt="image" src="https://github.com/user-attachments/assets/a94c7737-e7a9-4b57-89e0-e0efc322e191" />

## Verificamos el contenedor 
<img width="1899" height="143" alt="image" src="https://github.com/user-attachments/assets/3c60ab44-848c-4648-a5e9-94453f73c53a" />

## Verificamos con healtcheck sonarQube
<img width="1900" height="454" alt="image" src="https://github.com/user-attachments/assets/92d369a8-9962-41b2-abb2-4d0cf9a0b23f" />

## Verificamos con healtcheck postgre
<img width="1893" height="229" alt="image" src="https://github.com/user-attachments/assets/1c4d6c51-7c03-4c6a-b369-72f181329d1f" />


# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube
<img width="925" height="819" alt="image" src="https://github.com/user-attachments/assets/f2561dff-1edf-484e-bb16-775ccad38d1d" />
