# Instalación de Wordpress con EasyPanel

## Primer paso
1. Realiza la instalación de EasyPanel en la máquina virtual de Ubuntu y haz una captura del panel de control en la URL http://localhost:3000
![primera captura easypanel](https://user-images.githubusercontent.com/122264807/229455494-61e61266-0272-477d-837c-d0c1d49c67e8.png)

en la máquina virtual tenemos que poner lo siguiente:
sudo su
curl -sSL https://get.easypanel.io | sh

## Segundo paso
2. A partir de la plantilla de Wordpress activa el servidor web y haz una captura del panel de control de Wordpress.

2.1 Deberás añadir en la pestaña de Domain del servicio Wordpress el nombre "localhost".

2.2 Desactiva "Let's Encrypt" y accede a http://localhost para comenzar la instalación de Wordpress.

![captura 2](https://user-images.githubusercontent.com/122264807/229455934-6267bcf5-d1ef-4056-b8b5-b4ea8d6dbe44.png)

![captura 3](https://user-images.githubusercontent.com/122264807/229456713-76bd16e6-c489-4db0-93ad-fd5cb8636b81.png)

![captura 4](https://user-images.githubusercontent.com/122264807/229457257-47fa9926-f09c-4b60-9274-b74dd61a8923.png)

## Tercer paso
3. Una vez instalado Wordpress podreis acceder al blog mediante la URL "http://localhost" y al panel de control de Wordpress mediante la URL "http://localhost/wp-admin". Publica un artículo en github.com como un nuevo repositorio llamado wordpress-docs donde indiques como has instalado Wordpress. Para ello elige un tema ODS que prefieras comentando alguna noticia relacionada del area local.

![capt 5](https://user-images.githubusercontent.com/122264807/229457841-de51daba-4cef-4d51-9ae7-6633e7c3d1d3.png)












