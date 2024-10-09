# Actividad Grupal: Pull Requests en GitHub

## Objetivo

El propósito de esta actividad es aprender a utilizar la funcionalidad de **pull requests** de GitHub y manejar repositorios remotos, siguiendo un flujo de trabajo que se ha vuelto cada vez más común en entornos empresariales. Al completar esta práctica, los participantes estarán mejor preparados para colaborar en proyectos utilizando el flujo de trabajo de GitHub.

## Descripción

En esta actividad, cada miembro del grupo se familiarizará con la creación de **pull requests**, la gestión de ramas y la colaboración en un entorno compartido utilizando Git y GitHub.



  ### Requisitos Previos

- Todos los participantes deben tener una cuenta en GitHub.
- Git debe estar instalado en las máquinas locales de cada miembro.

## Pasos a Seguir

### 1. Configuración Inicial

1. El administrador debe crear un nuevo repositorio en GitHub (público).
2. Los desarrolladores deben crear un Fork del repositorio del administrador.
3. Cada participante debe clonar el repositorion en local

    ```bash
        git clone <URL_del_fork>
    ```

4. Crear una nueva rama para implementar la funcionalidad:

    > Comandos:
    >
    >```bash
    >    git branch <nombre_de_la_rama>
    >```
    >
    >ó
    >
    >```bash
    >   git switch -c <nombre_de_la_rama>
    >```
    >
    >ó
    >
    >```bash
    >   git branch <nombre_de_la_rama>
    >   git switch <nombre_de_la_rama>  
    >```
    >

5. Realizar cambios y crear un commit:

    ```bash
        git add .
        git commit -m "Implementación de nueva funcionalidad"
    ```

6. Hacer push de la rama al fork:

    ```bash
        git push origin <nombre_de_la_rama>
    ```

7. Crear una pull request desde GitHub para solicitar la fusión de la nueva funcionalidad al repositorio principal.

## Participantes

| Nombre               | Usuario GitHub       | Rol                         |
|----------------------|----------------------|----------------------------|
| Sanjuan Malax-Echevarria, Kerman | @Kerman-Sanjuan            | Administrador del Repositorio |
| Guerrero Orellana, Catalina Nieves | @cata-unir            | Desarrollador                 |
| Velayos Vega, Felipe Antonio | @fvelayosricoh            | Desarrollador                 |
| Lopez, Facundo Javier | @faqlive            | Desarrollador                 |
=======

### Estructura del Ejercicio

1. **Administrador del Repositorio**: Un miembro del grupo actúa como administrador y es responsable de inicializar y gestionar el repositorio principal en GitHub.
2. **Desarrolladores**: El resto de los participantes actúan como desarrolladores, forkean el repositorio principal y trabajan en diferentes funcionalidades de forma independiente.

  filename: **ruta** al fichero que contiene la lista de palabras, una por línea
  dup: **yes|no**, yes para eliminar palabras duplicadas, no para mantener la lista

  ## Trabajo en equipo
Se ha tenido en cuenta el documento mudevops07_act1.docx (se añade en esta rama)
Felipe: Se ha añadido otro comentario más
                    ## Aporte al Readme (Cata)
* Coordinamos una meeting y trabajamos en equipo.

## Aporte al Readme (Cata)
* Coordinamos una meeting y trabajamos en equipo.