# GENERACION DE APK EN UN PROYECTO DE ANGULAR Y EN UN PROYECTO DE REACT

Integrantes:

Nathaly Bermeo

Christian Llumiquinga

# Proyecto de Angular

Como primer punto empezamos a trabajar en la aplicación de Angular.

Una ves concluida esta y probamos que todo funcione bien con ionic serve.

![image](https://user-images.githubusercontent.com/56648687/147866013-ff293af6-2a4f-4110-a9dd-66ac9e65069b.png)

 
Una ves que tenemos probado que funciona correctamente empezamos con la configuración de nuestro proyecto para que se trasforme en un proyecto java, el primer comando que usaremos será:

Ionic build que nos construira el proyecto en java.

Luego añadiremos la carpeta Android con ionic add cap Android.

Una ves que realizamos esto editaremos el archivo androidManifest para dar los permisos de la aplicación necesarios.

![image](https://user-images.githubusercontent.com/56648687/147866014-2018e45f-d4d2-4325-9ac4-2e95575092fb.png)


 
Finalmente abrirmos el Android estudio y generamos las apk en la parte de buid de Android estudio.

![image](https://user-images.githubusercontent.com/56648687/147866024-0bc3a59a-1445-48aa-b589-29c3f2435496.png)

![image](https://user-images.githubusercontent.com/66235614/147896633-114677f1-e22f-4b96-a6b4-efe6524c1171.png)

 
La apk y bundle generadas se guardan en la siguiente ruta:

![image](https://user-images.githubusercontent.com/66235614/147896712-db01220f-d0a7-4348-94c5-72b9cce467d2.png)

![image](https://user-images.githubusercontent.com/56648687/147866028-8e59cb2a-a501-4e69-a8c0-7d09b674f438.png)

![image](https://user-images.githubusercontent.com/66235614/147896726-dcfc1a2e-d172-4061-bfac-a944ecc8b077.png)

La aplicación funcionando seria la siguiente:

![image](https://user-images.githubusercontent.com/66235614/147896619-3b907944-d588-4bdd-aae3-39806b4c0734.png)




La aplicacion de angular está en la rama:




# Proyecto de React

Se trabaja con la aplicación previamnete elaborada llamada photo-gallery con react.

Con el comando ionic serve - lab iniciamos el proyecto en el navegador.

![image](https://user-images.githubusercontent.com/66235614/147899655-4513d0f4-4cee-48aa-930b-a0648ed042ae.png)

Para el deploy de la aplicacion photo-gallery en React ejecutamos el comando ionic build.

Se crea el proyecto en Andriod con el comando ionic cap add android, la carpeta de Andriod se crea en la raiz del proyecto.

Para copiar los proyectos nativos se ejecuta el comando  ionic cap copy

Se ejecuta el comando ionic cap sync

Una vez realizados los pasos anteriores, se abre el proyecto el Andrioid Studio con el comando ionic cap open android.

Se habilita permisos para la cámara en el archivo AndriodManifest.xlm

![image](https://user-images.githubusercontent.com/66235614/147899926-337ea56c-251c-4058-8a7a-89e0814b8563.png)

Se guarda el archivo con los permisos requeridos y se ejecuta la aplicación en Android Studio.

![image](https://user-images.githubusercontent.com/66235614/147899999-c28ff884-b6ca-4a8f-a24c-af6fac00c594.png)

Se genera la apk y bundle de la aplicación.

![image](https://user-images.githubusercontent.com/66235614/147900509-308f4971-7f37-4a8d-9693-4b9ebd4b8596.png)

![image](https://user-images.githubusercontent.com/66235614/147900601-e4a0eb7e-dada-48aa-846c-7097cc90a96f.png)

![image](https://user-images.githubusercontent.com/66235614/147900616-3ff30b31-b808-4b98-9757-0464d924dbdf.png)

![image](https://user-images.githubusercontent.com/66235614/147900634-bd3c9f7a-5e65-49ad-9632-67074bc14faa.png)

Aplicación funcionando en el celular.

![image](https://user-images.githubusercontent.com/66235614/147900772-633c8b7e-e89b-4a35-8c17-17ead942a6a0.png)


La aplicación de react está en la rama :




