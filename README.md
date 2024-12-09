# Nginx-Flask Docker Application 🚀

Este es un proyecto que despliega una aplicación Flask utilizando Docker y Nginx. La aplicación está configurada para tener múltiples instancias de Flask, equilibrando la carga con Nginx. ⚙️

## Requisitos 🛠️

- Docker
- Docker Compose

## Instalación 🔧

1. **Clona el repositorio**:

Si aún no lo has hecho, clona este repositorio en tu máquina local:

```bash
 git clone https://github.com/Karina1014/nginx_load_balance-Flask.git
cd nginx-flask
```
### Construye y levanta los contenedores 🚢
Usando Docker Compose, puedes construir las imágenes y levantar los contenedores de la aplicación Flask y Nginx. Asegúrate de tener Docker y Docker Compose instalados en tu máquina. 🐳

Comandos para construir y levantar los contenedores:

### Comandos para construir y levantar los contenedores:
En la raíz del proyecto, ejecuta el siguiente comando para construir las imágenes de Docker y levantar los contenedores de la aplicación Flask y Nginx:

2. **Construir las imágenes y levantar los contenedores**:
```bash
docker-compose up -d --build --scale app=3
```

![image](https://github.com/user-attachments/assets/4d511a00-5226-4957-ae1d-6f1c250009a1)

3. **Verifica que todo está funcionando**:

Puedes verificar que los contenedores están corriendo con el siguiente comando:
 ```bash
 docker ps
 ```

 ![image](https://github.com/user-attachments/assets/993c5203-abc7-4c45-9589-2ca1edc40e53)

**Accede a la aplicación:**

La aplicación debería estar accesible en tu navegador en **http://localhost (o http://127.0.0.1).**

Resultados 1:

![image](https://github.com/user-attachments/assets/64da992e-2840-42d4-907d-b1119253ea2a)

Resultados 2:

![image](https://github.com/user-attachments/assets/4b20121f-0026-49b2-a799-5f58ad120dc1)

Resultados 3:

![image](https://github.com/user-attachments/assets/8fba61d0-3eab-4d84-8dd2-1cc874e66107)





