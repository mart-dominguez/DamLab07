# Laboratorio 07 - React Native
##Tareas a realizar
### Instalar el proyecto
1. descargar el repositorio
   1. ```git clone https://github.com/mart-dominguez/DamLab07.git ```
1. Meterse dentro del directorio donde se instaló
   1. ```cd DamLab07 ```
1. Instalar dependencias
   1. ```npm install ```
   
### Ejecutar en el emulador
1. Levantar el emulador
   1. para levantar el emulador por linea de comando necesita configurar las variables de entorno ( siguiendo las instrucciones de aquí http://www.automationtestinghub.com/setup-android-environment-variables/).  Sino lo puede levantar con Android Studio
   1. Listar emuladores disponibles   
      1. ```emulator -list-avds```   
   1. Levantar uno de los emuladores ( https://developer.android.com/studio/run/emulator-commandline?hl=es )
      1. ```emulator -avd avd_name```   
1. Ejecutar la aplicación react native en el emulador
   1. ```npx react-native run-android```   


### Ejecutar en el disposivio

1. Simplemente apagar el emulador y conectar el dispositivo en modo desarrollo.
1. Verificar qeu el dispositivo esté conectado
   1. ```adb devices```
1. Ejecutar la aplicación react native en el dispositivo
   1. ```npx react-native run-android```   
1. Si obtiene un error que no encuentra el servidor Metro "bridge configuration isn't available" entonces realizar la siguiente configuracion ( https://facebook.github.io/react-native/docs/running-on-device#method-1-using-adb-reverse-recommended ) 
   
  
