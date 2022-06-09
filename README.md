## Tarea 4.12. Practica5. Git. Creando ramas
En esta práctica vas a crear y configurar nuevas ramas, las mezclarás (Merge) y realizarás commits sobre ellas. Para ello usarás el flujo de trabajo GitFlow.

GitFlow fue publicado por primera vez y popularizado por Vincent Driessen en nvie. El flujo de trabajo de Gitflow define un modelo estricto de ramificación diseñado alrededor de la publicación del proyecto. Proporciona un marco sólido para gestionar proyectos más grandes.

1. Crea en este repositorio el esquema de ramas que se adjunta:
    1. Las ramas utilizadas son 
    2. Ramas de desarrollo y maestra (develop, master, main)
    3. Ramas de función (feature)
    4. Ramas de publicación (release)
2. Ramas de corrección (hotfix)
    1. El flujo general de Gitflow es el siguiente:
    2. Se crea una rama de desarrollo a partir de la maestra.
    3. Una rama de publicación se crea a partir de la de desarrollo.
    4. Las ramas de función se crean a partir de la de desarrollo.
    5. Cuando una función está completa, se fusiona en la rama de desarrollo.
    6. Cuando la rama de publicación está lista, se fusiona en la de desarrollo y la maestra.
    7. Si se detecta una incidencia en la maestra, se crea una rama de corrección a partir de la maestra.
3. Una vez que la corrección está completa, se fusiona tanto con la de desarrollo como con la maestra.

4. Adjunta un pantallazo del comando git log --oneline --decorate --graph --all
Una vez subido el repositorio CON TODAS SUS RAMAS, adjunta un pantallazo del apartado de GitHub "Insights"/"Network graph" 

![img](img/4.1.PNG))

![img](img/4.2.jpg))

Enlace: https://github.com/iesgrancapitan-eed/practica5-git--git-creando-ramas-andresfp16