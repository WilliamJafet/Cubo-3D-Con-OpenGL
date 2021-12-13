# Cubo 3D Con OpenGL

La práctica consiste en realizar un programa donde se muestra un cubo 3D.
Para ello primero se explica el código fuente del programa realizado.
En principio se realiza la importación de librerías necesarias para realizar la práctica.

![image](https://user-images.githubusercontent.com/72232712/145737475-548fceaf-e586-4506-a589-cafec081e95b.png)

El siguiente bloque de código es la declaración de variables necesarias para realizar distintas acciones.

![image](https://user-images.githubusercontent.com/72232712/145737483-8a3dbf65-4420-4a88-8412-64e4b1a4df14.png)

La función principal es importante debido a que es en esta parte donde empieza a ejecutarse el programa. En este bloque se realizan diversas configuraciones de la ventana para que se muestre al usuario.

![image](https://user-images.githubusercontent.com/72232712/145737486-b6ce6be0-9606-4cdc-80ca-d6def79436f3.png)

La función init es parte de la librería OpenGL y se utiliza para inicializar los componentes del Canvas, este es un componente en el que se va a realizar el pintado del objeto.

![image](https://user-images.githubusercontent.com/72232712/145737493-af7ff36f-73f4-41b3-9420-3df8fe530cc6.png)

En la función reshape se realizan las configuraciones necesarias para que se pueda mostrar el objeto.

![image](https://user-images.githubusercontent.com/72232712/145737495-ee30d62a-cfe5-489a-9ab4-1d18dc076f36.png)

La función display es una de las funciones más importantes porque es aquí donde se programan las instrucciones para que el programa pinte lo que le estamos indicando.
Para esta práctica se pintan los distintos cuadros que forman el cubo, para ello se tiene en cuenta las coordenadas de cada vértice del cuadrado. En total se pintan seis cuadrados para formar el cubo.

![image](https://user-images.githubusercontent.com/72232712/145737510-b39d35e1-411a-40e9-a9f6-6afcc0ce062d.png)

![image](https://user-images.githubusercontent.com/72232712/145737518-dfc7941c-a5ee-45f5-9844-06b0d9e46a55.png)

La última función por el momento no se realiza ninguna acción.

![image](https://user-images.githubusercontent.com/72232712/145737533-c579947d-a8b1-45d7-bdeb-f091c89be0b3.png)

Ahora que se ha explicado el código fuente, la siguiente parte es mostrar el resultado.
Como resultado hemos obtenido lo que se muestra en la siguiente figura. 

![image](https://user-images.githubusercontent.com/72232712/145737542-3163ef99-5db8-4ccf-be40-99b7b1313ad4.png)
