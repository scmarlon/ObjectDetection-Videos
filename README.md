# Proyecto de Multiprocesos
Este proyecto fue creado en Python utilizando Yolov3.
Se realiza un análisis de archivos de vídeo. En un inicio vamos a considerar películas o vídeos con una duración igual o superior a los 60 minutos. El repositorio esta conformado por múltiples archivos. Implementaremos multiprocesamiento a nivel del repositorio y a cada archivo (multiproceso para cada archivo).

## Instalación
1. Instalar [Python 3.7.0](https://www.python.org/downloads/release/python-370/)
2. Para el uso del programa se instalan diferentes bibliotecas que se instalan entre ellas `cv2`, `numpy`, `pip` y otras que el [IDE Pycharm](https://www.jetbrains.com/es-es/pycharm/download/#section=windows) le indica y le facilita la instalación.
3. Un metodo de instalación comun es el `pip install "nombre"`
 ![image](https://user-images.githubusercontent.com/38516078/137266603-be925b19-62c4-4d0c-9248-d79e8f6bedf2.png)


4. Se requieren los archivos `yolov3.cfg` y `yolov3.weight`. Para el `yolov3.weight` se obtiene del siguiente link 

## Ejecución
La ejecución funciona de la siguiente manera:

* Se realiza la lectura del los videos, estos son procesados mediante la inteligencia de `yolov3.cfg` y `yolov3.weight` los cuales requieren conocer los objetos que se buscan, por lo tanto, se utiliza el archivo  `obj.names` el cual contiene los elementos: rifle, gun y fire.

## Pruebas
## Resultados
