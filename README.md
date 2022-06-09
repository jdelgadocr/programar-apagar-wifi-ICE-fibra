# programar-apagar-wifi-ICE-fibra
Instrucciones de como programar el apagado del wifi en los routers Huawei que utiliza el ICE en Costa Rica, para serivioc de fibra óptica. No tengo certeza pero otros routers de Huawei y otras marcas pueden tener opciones similares a las descritas abajo.

Primero entramos a la direccion del router. Es el gateway en la IP asignada a nuestro celular o computadora cuando esta conectada al WiFi de la casa u oficina. Usualmente es la IP 192.168.1.1 (en mi caso es la 192.168.100.1)
![image](https://user-images.githubusercontent.com/47994550/172913076-02dee34a-9ab5-487e-94e8-7afca6f5cb28.png)

Cuando llegamos a esta página, usamos el usuario y clave. En mi caso es el de fábrica: usuario telecomadmin con la clave admintelecom

Al ingresar vamos a la seccion WLAN (red inalambrica), Apagado automático de WiFi (Automatic WiFi Shutdown), habilitamos la opción y luego ponemos la hora inicio y la hora de apagado.

![image](https://user-images.githubusercontent.com/47994550/172914348-2444dbe4-6aa8-41c6-9bc7-1fd97729b74a.png)

Hacemos click and Aplicar (Apply) y listo.

OPCIONAL: Podemos ver que hay una sección "Configuración basica de red 5G" (5G Basic Network Settings). Ahí solo tenemos que quitar el check para deshabilitar las frecuencias 5G de este router.
