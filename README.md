# Docker-DOOM
---

1. Primero levantamos el numero de contenedores docker que queramos.Utilizamos el siguiente comando: for i in {1..2} ; do docker run -d -t ubuntu:14.04; done.

- ![Captura desde 2022-06-07 15-33-18](https://user-images.githubusercontent.com/72273897/172393482-e510836a-2299-4352-9f30-a3361c018c99.png)
2. Descargamos y descomprimimos la imagen en : https://web.archive.org/web/20160310005603/https://gideonred.com/bins/dockerdoomd.tar.gz
![Captura desde 2022-06-07 15-36-18](https://user-images.githubusercontent.com/72273897/172394170-22d1d153-4717-401c-b80e-0fe5239afc04.png)
descargar e iniciar ; https://www.realvnc.com/en/connect/download/viewer/linux/
3. Arrancamos el servico con el comando "./dockerdoomd" y guardamos el puerto que va a usar.
- ![image](https://user-images.githubusercontent.com/72273897/172394991-d32a0e14-f719-4d56-9100-cbaac2ea2f3e.png)
4. Comprobamos que funcione ,vamos a la VNC y iniciamos una nueva conexion poniendo localhost:: y justo despues el puerto, aceptamos.

- ![Captura desde 2022-06-07 15-42-23](https://user-images.githubusercontent.com/72273897/172396064-ce86fe2b-a947-457e-9d9e-89d4ebb56aa9.png)
5. Comprobamos que funciona todo y que se visualiza.
- ![Captura desde 2022-06-07 15-42-58](https://user-images.githubusercontent.com/72273897/172396069-3714d3cc-72e1-4920-9dd8-4f8b42a0a5e8.png)
