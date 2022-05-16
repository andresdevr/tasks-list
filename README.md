# Lista de tareas

La prueba se compone de una serie  de fases, cada fase añade un nivel de dificultad a partir de la anterior, es decir la fase 2 debe de ser construida a partir de la fase 1. Una vez terminada una fase será revisada de cumplir con los requerimientos, una vez pasada esta revisión, podrás continuar con la siguientes fase.

Las fases estás listadas en distintas branchs (ramas) de git, subir los avances a su rama correspondiente para ser revisadas.

## Tutorial de Git  
### Clonar repositorio  
Una vez que tengas instalado [git](https://git-scm.com/), correr el comando siguiente en una terminal para clonar este repositorio, si requieres de una mejor explicación [ve aquí](https://www.youtube.com/watch?v=XycExtQ31GE)  

```bash
git clone https://github.com/andresdevr/tasks-list.git
```
### Cambiar de branch (rama)  
Para cambiarse entre ramas, es decir entre versiones del repositio basta con correr el comando (dentro de la carpeta), si requieres de una mejor explicación [ve aquí](https://www.youtube.com/watch?v=Ti3HnLr1pBg)  


```bash
git checkout [nombre de la rama]
```


### Subir cambios al repositorio  
Para realizar la subida de los cambios hechos al repositorio, es necesario realizar los siguientes comandos, si requieres de una mejor explicación [ve aquí](https://youtu.be/UDZzVyZvv-M?t=114)  


```bash
git add .
git commit -m "Mensaje de los cambios realizados"
git push origin [nombre de la rama]
```

### Descargar cambios del repositorio  
Si estas colaborando con otra persona, es posible que esta misma también realice cambios en el repositorio, para mantener sincronizado los cambios realizados es necesario correr el siguiente comando, , si requieres de una mejor explicación [ve aquí](https://www.youtube.com/watch?v=VypqQyHPoWE)  

```bash
git pull origin [nombre de la rama]
```

## Descripción general
Se requiere una aplicación donde una persona pueda crear tareas, donde a cada una se le pueda asignar una fecha final, y marque el estatus de la tarea: pendiente, completada, expirada.

## Requerimientos
- [ ] Crear un listado de tareas. 
- [ ] Crear un layout sencillo y agradabla a la vista, inspirarse de (https://www.bootdey.com/snippets/view/bs4-todo-list)
- [ ] La aplicación debe ser el puro maquetado, es decir la página sin funcionalidad.

## Software necesario
- [git](https://git-scm.com/)
- [html](https://developer.mozilla.org/es/docs/Web/HTML)
- css (escoge alguno)
    - [bootstrap](https://getbootstrap.com/)
    - [tailwind](https://tailwindcss.com/)
    - [pure css](https://purecss.io/)
    - [bulma](https://bulma.io/)
    - [foundation](https://get.foundation/)
    - [skeleton + css puro](http://getskeleton.com/)
    - [materialize](https://materializecss.com/)

