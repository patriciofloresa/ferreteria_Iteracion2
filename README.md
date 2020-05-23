# Ferreteria Django

Este proyecto es para la Tesis de la universidad...

para generar el MER con la liberia de django-extension hacer lo siguiente:

```sh

--instalar los paquetes que se encuentra en nuestro requirements.txt

-- Añadir en el settings.py la siguiente app:

INSTALLED_APPS = [  
    ...
    'django_extensions',
]

```

Por ultimo correr el siguiente comando:

```sh
python3 manage.py graph_models --pygraphviz -a -g -o MER_ALL_MODELS.png
```

Para crear el gráfico se debe iniciar el siguiente comando al interior del proyecto:

```sh

-- Genera un grafico del app seleccionada (api)
$ python manage.py graph_models api -o APP_MODELS.png

-- Genera grafico de todos los modelos incluyendo los que vienen por defecto de Django
$ python3 manage.py graph_models --pygraphviz -a -g -o MER_ALL_MODELS.png

```

Para acceder a la base local usar las siguientes credenciales:

Acceso 1:

- **usuario:** admin
- **contraseña:** 1234

Acceso 2:
- **usuario:** proveedor1
- **contraseña:** Prueba12345
