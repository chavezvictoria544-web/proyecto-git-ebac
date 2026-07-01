# Proyecto Git EBAC

Este es un proyecto Java simple creado para practicar el uso de Git y GitHub.

## Descripción

El proyecto contiene una clase Java llamada Main.java, ubicada dentro del paquete:

com.ebac.moduloGit

## Objetivo

Practicar los siguientes conceptos:

- Crear un repositorio público en GitHub.
- Crear un proyecto Java sencillo.
- Usar una rama principal llamada main.
- Crear una rama adicional llamada desarrollo.
- Hacer cambios en la rama desarrollo.
- Fusionar los cambios de desarrollo con main.

## Comandos utilizados

git init  
git branch -M main  
git add .  
git commit -m "Primer commit del proyecto Java"  
git checkout -b desarrollo  
git commit -m "Agrega cambio en la rama desarrollo"  
git checkout main  
git merge desarrollo  
git push -u origin main  
git push -u origin desarrollo