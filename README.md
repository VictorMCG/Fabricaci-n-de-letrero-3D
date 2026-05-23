# Fabricación de letreros 3D

Este proyecto documenta mi proceso para diseñar y fabricar letreros 3D utilizando impresión 3D multicolor con AMS.

---

# Herramientas

- Impresora 3D Bambu Lab
- AMS (Automatic Material System)
- Bambu Studio
- Filamentos PLA
  
# Link's

-[MakerLab - Image to Keychain](https://makerworld.com/es/makerlab/imageToKeychain?from=makerlab)
-[México Makers - Image to Keychain](https://www.mexicomakers.com.mx/products/pla-matte-rosa-axolote?_pos=1&_sid=0fe0920f0&_ss=r)
-[ImageColorPicker.com - Image to Keychain](https://imagecolorpicker.com/es#google_vignette)


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


<img width="879" height="729" alt="image" src="https://github.com/user-attachments/assets/8dd9efd9-e2a9-4344-ae90-5bf4b4646ff4" />


## 3. Corrección de colores en Bambu Studio
Vamos a abrir un nuevo proyecto en Bambu Studio y procederemos a cargar el archivo que acabamos de generar. Una vez importado, podremos ajustar la escala, posición y configuración de colores para preparar el modelo antes de la impresión.
Yo cometí el error de agregar el color verde cuando mi impresora solamente acepta 4 filamentos por lo que procedo a colorear las zonas que quedaron mal ya sea porque tenian algun error de colores

Antes

<img width="1341" height="1208" alt="image" src="https://github.com/user-attachments/assets/0bc9e6db-19ec-46a6-b3d0-9fbebdaa882f" />

Después 

<img width="1400" height="1066" alt="image" src="https://github.com/user-attachments/assets/becd0255-9312-4af0-9b9c-9426b8df89f6" />

Agregué un cilindro pequeño de fondo, lo que permitirá que las figuras tengan un mejor soporte y, al mismo tiempo, dará ese acabado en relieve que hace que el logo se vea más tridimensional y con un efecto 3D más atractivo.

Para evitar que la figura se mueva o se desacomode, es importante seleccionar ambos objetos y unirlos en una sola pieza. Esto también facilita ajustar la escala del logo de manera más cómoda y precisa durante el proceso de edición.


## 4. Corte y preparación

Con la herramienta de cortar podemos dividir la figura en varias partes, lo que nos permite fabricar el logo en un tamaño más grande sin exceder el área de impresión de la impresora.

En mi caso, dividiré el modelo en 4 partes para facilitar tanto la impresión como el ensamblado posterior.

-Primer corte

<img width="882" height="890" alt="image" src="https://github.com/user-attachments/assets/8aac0e15-4943-4908-bad8-94470439bb59" />

-Segundo corte 

<img width="1003" height="864" alt="image" src="https://github.com/user-attachments/assets/09068a2a-707a-4662-8088-4673de434cd0" />


## 5. Escalado
Hay que agregar 3 camas más para poder colocar cada parte del logo por separado. Con esto lograremos realizar un laminado completo del proyecto, lo que nos ayudará a calcular de manera más precisa tanto los costos de impresión como el tiempo de procesamiento.

También es importante configurar correctamente los parámetros del material, especialmente el costo del filamento que ustedes manejan, ya que esto permitirá obtener estimaciones más realistas del precio final de fabricación.
<img width="1122" height="1095" alt="image" src="https://github.com/user-attachments/assets/f280b6e9-ed57-4fc6-aa45-37792560d33a" />

Es importante que todas las piezas se escalen, para que tengan el mismo tamaño 


## 6. Armado final
<img width="900" height="1600" alt="WhatsApp Image 2026-05-23 at 3 39 35 PM" src="https://github.com/user-attachments/assets/781f5536-4be7-4ce9-b0bb-1c6fd4c180d3" />
Ese es el resultado después de la impresión, para hacer la unión de las piezas pueden utilizar cianocrilato o colaloca si viven en México es lo mismo, deben tener mucho cuidado de no manchar las piezas porque pueden quedar con un tono blanco en el diseño 

<img width="615" height="735" alt="image" src="https://github.com/user-attachments/assets/91be9ac8-13ee-4418-969c-e996bafc0148" />




# Notas

Los costos de este trabajo dependerán de varios factores, como el material utilizado, la complejidad del logotipo, la mano de obra requerida y el tiempo total de impresión. En este caso, la impresión tomó aproximadamente 24 horas, por lo que es importante considerar ese tiempo dentro del cálculo final del proyecto.

Para este trabajo, el costo aproximado fue de 200 pesos mexicanos, considerando únicamente materiales y consumo eléctrico. Esto equivale aproximadamente a 17.5 dólares, tomando como referencia un tipo de cambio de 1 USD = 17.33 MXN.

Sin embargo, aún falta integrar otros gastos importantes, como:

Mano de obra, que en un trabajo de este tipo no debería ser menor a 50 pesos.
Incremento o margen de ganancia del negocio, por ejemplo un 30%, para permitir el crecimiento y mantenimiento del emprendimiento.
Impuestos, IVA y otros gastos operativos.

Tomar en cuenta todos estos factores permitirá establecer un precio más realista y rentable para la fabricación del logotipo.
<img width="1169" height="934" alt="image" src="https://github.com/user-attachments/assets/bbf0e42a-1655-4f35-becd-b2255b13285b" />


# Estado del proyecto

Concluido 
