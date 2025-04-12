# static-website

Este repositorio contiene el contenido estático de la página web que se desplegará en un entorno Kubernetes local usando Minikube.

## Instrucciones para configurar el contenido web

### 1. Clonar el repositorio
Para comenzar, clona este repositorio en tu máquina local:

```bash
git clone https://github.com/MatiasColladoCA/static-website
cd static-website
```

### 2. Personalizar el contenido web
El contenido estático de la página web se encuentra en este directorio. Se modificaron los archivos HTML, CSS, imágenes u otros recursos.
Las buenas prácticas incluyen:
- Usa nombres descriptivos para los archivos.
- Realiza commits frecuentes con mensajes claros.
Ejemplo de commit:
```bash
git add .
git commit -m "Personalización del contenido web"
git push origin main
```


### 3. Vinculación con Kubernetes
El contenido de este repositorio será servido por un servidor web (por ejemplo, Nginx) dentro de un cluster de Kubernetes. Para configurar el entorno de Kubernetes, sigue las instrucciones en el repositorio manifiestos-k8s.


Importante : Una vez que hayas terminado con este repositorio, dirígete al README.md del repositorio manifiestos-k8s para continuar con la configuración del entorno Kubernetes.