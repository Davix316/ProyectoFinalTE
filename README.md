# Proyecto Final Tópicos Especiales
##  Integrantes: Amagua Jhoel - Curipoma David
### Link del video en OneDrive: :movie_camera:
[![Watch the video](https://github.com/Davix316/ProyectoFinalTE/blob/main/images/video.PNG)](https://n9.cl/utmyk)
 
### En el presente repositorio se encuentra el código del proyecto final realizado para la materia de Tópicos Especiales:

## APP: Mi lista para comprar
```
- Creación de una APP que ayude al usuario en la creación de una lista para compras.
- El usuario podrá registrarse en la APP con un correo y contraseña.
- El usuario podrá crear listas de compras las cuales solo de registran bajo las credenciales de ese usuario.
- El usuario podrá visualuzar sus listas creadas cada que ingrese a la aplicación.
- El usuario podrá acceder a los detalles de cada lista donde podrá eliminar y editar.
- La APK de la aplicación esta firmada y desplegada en Google.
```
## Partes Principales del código :wrench:


## Interfaces principales de la APP: :iphone:
### Icono y Splash Screen
Ya que se creó y configuró un icono y un splash screen, al momento de instalar y arrancar la APP, aparecerán estas imágenes.
| **Icono**:radio_button:| **Splash Screen**:speech_balloon:| 
| ------------- | ------------- | 
|![Screenshot](icono.jfif) |![Screenshot](splash.jfif) |

| **Inicio de sesión**:bust_in_silhouette: | **Registro**:point_down: |
| :---: | :---: |
| Una vez el usuario tenga una cuenta podrá iniciar sesión con sus credenciales, es importante recordar que las credenciales son el correo y contraseña que hayan sido proporcionados en el registro. El botón de Ingresar no se habilitará hasta que los campos hayan sido llenados correctamente, tanto el tipo de texto como las credenciales correctas. | Si el usuario no tiene una cuenta, tiene que acceder a esta parte, donde se registrará con un correo y una contraseña creada en ese momento,ambos campos tienen que cumplir ciertas reglas para que el registro pueda realizarse de manera correcta. |
|![Screenshot](login.jfif)  |![Screenshot](registro.jfif) |

| **Lista de Compras** :moneybag: | **Nueva Lista**:heavy_plus_sign: | **Detalles** :memo:|
| :---        |     :---     |          :--- |
| Cuando el usuario haya ingresado a su cuenta, le aparecerá sus listas de compras, si ya las hubiese ingresado, caso contrario se muestra un mensaje que indica: Por favor crea tu primera lista, del mismo modo si el usuario tiene listas creadas anteriormente, aparecerán todas con un botón al lado derecho, para ver los detalles de dicha lista. Cada recalcar que las listas solo serán las que el usuario haya registrado y le pertenescan.| Si el usuario acaba de registrarse, tendrá que empezar creando una nueva lista con el título y productos correspondientes, entonces debe ir a la parte superior derecha y acceder al botón +, de esta manera les aparece esta interfaz en la cual pueden agregar una nueva lista. | Cuando el cliente haga clic en VER LISTA, se redirige a esta interfaz, la misma que muestra el título, los productos y dos botones, uno que sirve para guardar los cambios que el usuario pudiera hacer, y el otro para eliminar toda la lista de su listado.|
| ![Screenshot](lista.jfif) | ![Screenshot](nuevo.jfif)|![Screenshot](detalle.jfif)  |
|![Screenshot](sinlista.jfif)|



### Referencias :link:
- https://ionicthemes.com/tutorials/about/building-a-ionic-firebase-app-step-by-step 
