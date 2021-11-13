# programacion_mobil

prueba_2 antes de iniciar el programa es necesario que se instale primero el storage usando el comando siguiente:

npm install --save @ionic/storage



para lograr que el programa funcione correctamente es necesario instalar lo siguiente:
Para instalar Firebase es obligatorio tener una cuenta gmail, de esta manera se podra acceder a la base de datos

npm install firebase npm install @angular/fire firebase --save

Conectar a la base de datos:
Lo primero es ir a la pagina de firebase https://console.firebase.google.com/u/0/?hl=es,_
crear una cuenta o iniciar sesion si ya posee una.
crear unn proyecto, si desea mantiene la opcion de google analityc en caso de que no solo apriete continuar.
al crearse su proyecto debera hacer click en la opcion de web que se señala con el simbolo "</>".
asignarle nombre y registrar la app, cuando te registras vas la parte superior izquierda y seleccionas la tuerca que esta junto a "Descripción general del proyecto", se desplegara un menu donde seleccionaras configuracíon del proyecto, bajas hasta donde te aparecera tu "proyecto" y aparecera una opcion de "configuracion del SDK" del contenido que aparece solamente seleccionaremos lo siguiente:

cada config de firebase es unica y diferente.

const firebaseConfig = {
    apiKey: ........
    authDomain: .......
    projectId: ........
    storageBucket: ........
    messagingSenderId: ...........
    appId: ........
    measurementId: ..........
    };

la configuracion debe colocarse en environment y en environment.prod.ts


Herramientas Utilizadas en el proyecto

* [ionic](https://ionicframework.com) 
* [Angular](https://angular.io) 
* [Node](https://nodejs.org/es/)
* [Firebase](https://console.firebase.google.com/u/0/)


integrante: juan marquez

