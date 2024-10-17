"# DSS_practico_4" 



## Prueba 2: Cross-Site Scripting (XSS)

### Descripción


1. Tener Python instalado
Si no tienes Python instalado, puedes instalarlo siguiendo estos pasos:

sudo apt update
sudo apt install python3

2. Instalar la biblioteca requests
El script utiliza la biblioteca requests para realizar solicitudes HTTP. Si no la tienes instalada, puedes hacerlo con el siguiente comando:

pip3 install requests

3. Tener el código de AltoroJ

Asegúrate de tener AltoroJ ejecutándose en tu entorno.

4. Crear un archivo Python en Eclipse

5. Hacer el script 

![alt text](images/xss_codigo.png)

6. ejecutar el script y interpretar el resultado 

Caso 1: Vulnerabilidad presente

Si el script detecta la vulnerabilidad de XSS, mostrará el siguiente mensaje en la consola:

![alt text](images/xss.png)

Esto indica que la vulnerabilidad aún está presente en el sistema y el código de salida será 1.

Caso 2: Vulnerabilidad ausente

Si no se detecta la vulnerabilidad, el script mostrará este mensaje:

![alt text](images/xss_exito.png)

Esto significa que el sistema ha mitigado correctamente la vulnerabilidad de XSS y el código de salida será 0.