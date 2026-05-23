# Fabricación de letreros 3D

Este proyecto documenta mi proceso para diseñar y fabricar letreros 3D utilizando impresión 3D multicolor con AMS.

---

# Herramientas

- Impresora 3D Bambu Lab
- AMS (Automatic Material System)
- Bambu Studio
- Filamentos PLA

---

# Proceso de fabricación

## 1. Preparación del logo
Podemos generar fácilmente un logo con ayuda de ChatGPT, pero es importante mantener el diseño lo más simple posible. El uso excesivo de degradados puede complicar la selección de colores al momento de imprimir y también dificulta el procesamiento de la imagen para obtener los tonos exactos que buscamos.

Además, es importante considerar la cantidad de colores que admite nuestro AMS. De forma estándar, el AMS puede almacenar hasta 4 filamentos, y con aditamentos externos es posible ampliar la capacidad hasta 8 colores. Por ello, un diseño más limpio y con menos variaciones de color facilita tanto la fabricación como la reproducción del logo.  <img width="1536" height="1024" alt="Logos ejemplos" src="https://github.com/user-attachments/assets/8ce02932-835e-4364-939e-7ef123a3c40a" />


## 2. Herramienta de bambu lab para generación

Una vez tengamos el logo que vamos a trabajar en mi caso yo tengo que trabajar este logo que es un ecargo
<img width="923" height="923" alt="Logo Fernanda" src="https://github.com/user-attachments/assets/be18fe1d-38da-412a-aee9-b9882f3a7a66" />


Nos vamos a dirigir a [MakerLab - Image to Keychain](https://makerworld.com/es/makerlab/imageToKeychain?from=makerlab)

Una vez dentro vamos a dar click en crear desde cero como te muestro acontinucación 
<img width="2677" height="764" alt="image" src="https://github.com/user-attachments/assets/bdfb87cb-ea06-4a19-98f7-092b156d38a2" />

A continuación, carga el logo con el que vas a trabajar. Durante el proceso aparecerá un anuncio relacionado con el procesamiento de la imagen. Es importante que prestes atención a esta etapa, ya que el contorno que elijas será la forma final de tu logo.

Por ejemplo, si seleccionas un contorno cuadrado, el logo conservará esa forma cuadrada. Esto puede complicar ajustes posteriores, ya que actualmente no es posible editar ni regresar a este apartado una vez confirmado el procesamiento.

<img width="1383" height="1014" alt="image" src="https://github.com/user-attachments/assets/5230c985-6795-46aa-91c4-531f4e1f918c" />

Podemos hacer algunas correciones de colores para facilitar el trabajo, sin embargo yo lo dejaré así, le damos en confirmar para avanzar, esto puede tardar algunos minutos según lo complejo del trabajo 

El siguiente paso va a depender del número de colores dispionibles que tiene nuestra impresora, por lo que como la mia solamente cuenta con 4 colocaré 4 

<img width="1210" height="1119" alt="image" src="https://github.com/user-attachments/assets/3026d46c-ef50-4a06-bd9c-f52623172bd3" />

Para esta etapa, y para que el logo quede lo más parecido posible al diseño que hemos creado, es necesario conocer los tonos de filamento con los que contamos.

Un método muy útil para lograrlo es descargar la imagen del color del filamento directamente desde la página del fabricante y utilizar algún software que nos permita identificar el tono exacto en formato hexadecimal (HEX). De esta manera, podemos comparar colores con mayor precisión y elegir la combinación más cercana al diseño original.

A continuación, te muestro un ejemplo:
Nos dirigimos a la pagina del provedor de materiales:

[México Makers - Image to Keychain](https://www.mexicomakers.com.mx/products/pla-matte-rosa-axolote?_pos=1&_sid=0fe0920f0&_ss=r)



<img width="1449" height="947" alt="image" src="https://github.com/user-attachments/assets/6b187deb-3638-4a3d-b664-f65f6ab076a4" />


Descargar imagen de filamento rosa ajolote del fabricante  <img width="713" height="713" alt="axolote2" src="https://github.com/user-attachments/assets/f6360279-6fc2-4bde-915c-4143345d5d6c" />

Nos dirigimos a alguna página o herramienta que permita convertir colores de una imagen a formato hexadecimal. Estas plataformas nos ayudan a identificar con precisión los tonos presentes en el filamento para poder replicarlos de la mejor manera en nuestro logo.

Te dejo este link por si te sirve:

[ImageColorPicker.com - Image to Keychain](https://imagecolorpicker.com/es#google_vignette)

En la siguiente imagen te muestro cómo identificar el tono del color. Es normal que existan ligeras variaciones entre distintas partes de la imagen, pero esto no representa un problema importante, ya que el objetivo es obtener una referencia lo más cercana posible al tono real del filamento que vamos a utilizar.


<img width="1482" height="986" alt="image" src="https://github.com/user-attachments/assets/e0f6ae55-0ff8-4fca-92a2-26c442d00d09" />

El valor hexadecimal que obtenemos lo utilizaremos en la siguiente página o herramienta para visualizar el color de manera más precisa y ver cómo se vería aplicado en el logo final. Esto nos permite aproximarnos mejor al resultado real que tendrá la impresión con los filamentos seleccionados.
<img width="2044" height="1166" alt="image" src="https://github.com/user-attachments/assets/a386c68d-fadc-482a-895a-a35853826df8" />

Como puedes ver, algunos detalles de la imagen pueden perderse durante el proceso, por lo que es necesario realizar ciertos ajustes manuales. En mi caso, eliminaré el color azul que marqué para sustituirlo por un tono negro y también corregir esos rayones.

El proceso es bastante sencillo: únicamente debes seleccionar la zona o el elemento que deseas recolorear.

Otro consejo útil es que, si no cuentas con suficientes colores disponibles —como sucede en mi caso—, puedes utilizar tonos neutros como blanco o negro para generar contraste. Posteriormente, en un postprocesado, podrás pintar esas zonas manualmente para acercarte aún más al resultado final que buscas.

<img width="754" height="610" alt="image" src="https://github.com/user-attachments/assets/3ec79a44-5d7c-4a52-b0e3-da7a2ba2b0e0" />

Después de un rato trabajando en el logo, este es el resultado final. Como puedes observar, algunos contornos en color negro deberán pintarse de forma externa durante el postprocesado para lograr un mejor acabado y mantener la apariencia original del diseño.

Algo adicional que hice fue eliminar el fondo para que ciertas partes del logo tuvieran relieve y generaran un efecto más interesante visualmente. También pude haber eliminado la parte central del diseño, pero no se me ocurrió hasta después de la fabricación. Probablemente el resultado habría quedado aún mejor y con un acabado más limpio.


<img width="1143" height="1085" alt="image" src="https://github.com/user-attachments/assets/29dddbf7-fee1-4e1d-a9fb-261d758c03ef" />





Procedemos a decargar el archivo para trabajarlo en bambu studio 

## 3. Corrección de colores en Bambu Studio

- Ajuste de perfiles
- Corrección de capas
- Verificación del AMS

![Bambu Studio](photos/bambu-studio.jpg)

---

## 4. Corte y preparación

- Ajuste de dimensiones
- Optimización del modelo
- Configuración de impresión

![Corte](photos/corte.jpg)

---

## 5. Escalado

- Ajuste de tamaño
- Verificación de proporciones
- Pruebas de impresión

![Escalado](photos/escalado.jpg)

---

## 6. Armado final

- Unión de piezas
- Limpieza
- Resultado final

![Resultado final](photos/final.jpg)

---

# Notas

Durante el proceso iré agregando:
- Fotos
- Errores comunes
- Configuraciones
- Tiempos de impresión
- Costos aproximados

---

# Estado del proyecto

🚧 En desarrollo
