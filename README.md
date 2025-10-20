# Documentacion-PLATCOLDIG

#  Documentación del Proceso — Grupo 1: Introducción y Configuración de Git y GitHub

##  Descripción General

Este documento detalla el proceso seguido para la elaboración del **informe académico** sobre el tema *“Introducción y configuración de GitHub”*.  
Se utilizaron herramientas de investigación, pruebas prácticas con GitHub, y redacción colaborativa en formato Markdown antes de convertir el texto final al formato académico formal.

### Responsables
- **Grupo 1:** encargados del tema de introducción y configuración.  
- Roles internos:
  - **Investigador principal:** recopilación de fuentes oficiales. (Alfredo Montalván)
  - **Redactor:** elaboración del informe base. (Kendra Reyes)
  - **Practicante:** revisión de formato y redacción. (Alfredo Montalván)
  - **Documentador:** creación de esta guía en formato Markdown. (Andres Maradiaga)
    


##  1. Planificación del Proyecto

### Objetivo
Elaborar un informe académico completo que explique paso a paso el proceso de:
- Creación de una cuenta en GitHub  
- Instalación de Git  
- Configuración inicial de Git  
- Generación y uso de claves SSH (opcional)  
- Creación del primer repositorio  


### Herramientas utilizadas
- **GitHub:** plataforma para control de versiones y alojamiento del documento.  
- **Git:** herramienta de control de versiones local.    
- **Markdown (.md):** formato base de documentación.  
- **ChatGPT:** asistencia en redacción estructurada y verificación técnica.  
- **Fuentes de referencia:** Git Docs, GitHub Docs, Atlassian Tutorials, libro *Pro Git*.


##  2. Proceso de Elaboración

### Paso 1: Creación de la cuenta en GitHub
1. Ingresamos a [https://github.com](https://github.com).
2. Seleccionamos **Sign up**.
3. Registramos un nombre de usuario, correo electrónico y contraseña.
4. Confirmamos la cuenta mediante el correo de verificación.
5. Personalizamos el perfil para uso académico (foto, bio, etc.).

 **Tutorial de apoyo:**  
> GitHub Docs — [Getting Started with GitHub](https://docs.github.com/en/get-started/start-your-journey)

---

### Paso 2: Instalación de Git
Se realizó la instalación en distintos dispositivos según el equipo de cada integrante.

### En Windows
1. Descargamos el instalador desde ([https://git-scm.com/downloads](https://desktop.github.com/download/)).
3. Descargamos el git desde ([https://git-scm.com/downloads](https://git-scm.com/downloads/win))  
3. Ejecutamos el archivo y seguimos los pasos por defecto.

### Paso 3: Configuración básica de Git

Configuramos el nombre de usuario y correo que se asocian a los commits:

git config --global user.name "Nombre del usuario"
git config --global user.email "correo@ejemplo.com"


### Paso 4: Creación del primer repositorio

-Entramos a GitHub y seleccionamos New repository.
-Asignamos un nombre y descripción.
-Elegimos la visibilidad (public o private).
-Creamos el repositorio con un archivo README.md.

### Paso 5: Elaboración del Informe Académico

-Una vez finalizada la práctica técnica, redactamos el informe siguiendo la estructura académica:
-Introducción: importancia del control de versiones.
-Desarrollo: explicación detallada de cada paso.
-Conclusión: reflexiones sobre la utilidad de GitHub.

### 3. Resultados

Se creó y verificó correctamente una cuenta GitHub.
Git se instaló y configuró exitosamente en los distintos equipos.
Se generaron claves SSH opcionales para conexión segura.
Se creó repositorio del proyecto funcional.
Se completó el informe académico en formato formal y digital.

### 4. Conclusiones del Proceso

La documentación en formato Markdown facilita la organización y legibilidad del proceso.
Git y GitHub son herramientas esenciales para el trabajo colaborativo y la trazabilidad de proyectos.
La práctica permitió comprender la diferencia entre la configuración local (Git).
Se desarrollaron habilidades técnicas y de documentación profesional, útiles para proyectos futuros.
4. Verificamos la instalación con:
   ```bash
   git --version
