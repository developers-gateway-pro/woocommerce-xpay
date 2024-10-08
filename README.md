# Xpay - Webcheckout - Woocommerce

Módulo para pagos en línea por medio de Xpay en modo Webcheckout(se redirige a la pasarela de pagos de Xpay y una vez se procesa el pedido se retorna una respuesta al woocommerce), este módulo fue desarrollado para Colombia, pero debería funcionar
en: (Argentina, Brasil, Chile, Colombia, México, Panamá, Perú)

## Traducciones

Las traducciones están en Español Colombia e Ingles, las puedes cambiar al idioma que necesites conforme al manejo de idiomas de Wordpress.

## Instalación

- Descargar el contenido de este [repositorio](https://github.com/developers-gateway-pro/woocommerce-Xpay/archive/refs/heads/main.zip).
- En el administrador de Wordpress ir a la sección de plugins y buscar el archivo descargado y añadir plugin e instalar.
  
![Texto alternativo](https://img-app-v1.s3.amazonaws.com/cap1.png)

![Texto alternativo](https://img-app-v1.s3.amazonaws.com/cap2.png)

![Texto alternativo](https://img-app-v1.s3.amazonaws.com/cap3.png)

- Activa el plugin.

![Texto alternativo](https://img-app-v1.s3.amazonaws.com/cap4.png)
  
- Entra a las configuraciones de Woocomerce y en pagos onfigura Xpay

![Texto alternativo](https://img-app-v1.s3.amazonaws.com/cap5.png)

- Gestiona el método de pago    


  Modo Pruebas: Selecciona el ambiente al cual deseas ejecutar la transacción de pagos (pruebas, producción)    
  Account ID: Id de cuenta compartido por la entidad, usada en ambiente de producción  
  Api KEY: Llave de acceso compartida por la entidad, usada en ambiente de producción   
  Account ID Test: Id de cuenta compartido por la entidad, usada en ambiente de pruebas  
  Api KEY Test: Llave de acceso compartida por la entidad, usada en ambiente de pruebas  
  Url Sanbox (Pruebas)  
  Url Producción  

![Texto alternativo](https://img-app-v1.s3.amazonaws.com/cap6.png)
  
- En la pagina de pago de wordpress (http://localhost/wordpress/index.php/finalizar-compra/), se debe garantizar que exista el Shortcode [woocommerce_checkout]:

![Texto alternativo](https://img-app-v1.s3.amazonaws.com/cap7.png)

- Luego de configurar el plugin y el Shortcode realiza una prueba con una compra y deberás visualizar el metodo de pago el cual redireccionará hacia el checkout de pagos de la pasarela:

<img width="1177" alt="image" src="https://github.com/user-attachments/assets/1d6536e5-ff9e-4081-ae1f-e1efb718bf9d">

<img width="1485" alt="cap8" src="https://github.com/user-attachments/assets/23d9f9b6-5253-4736-91f4-f082971f6cb5">


## Pruebas de compras

- Buscar generadores de códigos de creditcards o solicitar tarjetas para pruebas con 3DS.
