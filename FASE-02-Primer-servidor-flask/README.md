# Instalación de Flask

Antes de crear aplicaciones web con Flask, primero es necesario instalar Flask en Python.

---

# ¿Qué es instalar Flask?

Flask es una librería/framework de Python.

Por lo tanto, Flask no viene incluido por defecto con Python.

Necesitamos descargarlo e instalarlo utilizando herramientas de Python.

---

# ¿Cómo se instalan paquetes en Python?

Python utiliza una herramienta llamada:

pip



pip permite instalar librerías y frameworks.

Por ejemplo:

Flask
psycopg2
requests
numpy
pandas

---

#Verificar Python

Antes de instalar Flask, es importante verificar que Python esté instalado correctamente.

En Linux:

python --version

o:

python3 --version

---

#Verificar pip

También es importante verificar pip.

pip --version

o:

pip3 --version

---

#Instalación básica de Flask

La instalación más sencilla es:

pip install flask

o en algunas distribuciones Linux:

pip3 install flask
¿Qué hace este comando?

Este comando:

Descarga Flask
Descarga dependencias necesarias
Instala Flask en Python
Verificar instalación

Después de instalar Flask, puede verificarse utilizando:

pip show flask

Esto mostrará información como:

Versión instalada
Ruta de instalación
Dependencias
Problema común


---

#Instalar Flask globalmente puede generar problemas en proyectos reales.

Por ejemplo:

Conflictos de versiones
Dependencias mezcladas
Problemas entre proyectos
Solución profesional

Utilizar:

---

#entornos virtuales

Cada proyecto tendrá sus propias librerías y versiones aisladas.

Idea importante

Aunque Flask ya puede instalarse globalmente, en proyectos reales normalmente se trabaja utilizando:

Entornos virtuales
requirements.txt
Dependencias aisladas
Próximo paso

El siguiente paso será crear un entorno virtual para trabajar Flask de manera correcta y profesional.











---
---






# Entorno virtual en Python

Un entorno virtual es un espacio aislado para instalar las librerías de un proyecto.

En Flask es muy importante usar entornos virtuales porque cada proyecto puede necesitar sus propias dependencias.

---

# ¿Por qué usar un entorno virtual?

Si instalas librerías de forma global, todos tus proyectos usarán las mismas versiones.

Eso puede causar problemas.

Ejemplo:


Proyecto A → Flask versión 3
Proyecto B → Flask versión diferente

Con un entorno virtual, cada proyecto mantiene sus propias librerías sin afectar a los demás.

#¿Qué significa venv?

Aquí hay dos cosas distintas:

python -m venv venv

Aunque se ve repetido, NO significa lo mismo.

Desglose del comando
python -m venv venv
Primer venv
-m venv

Significa:

Usa el módulo venv de Python

Es decir, le estás diciendo a Python:

Crea un entorno virtual usando la herramienta venv
Segundo venv
venv

Es el nombre de la carpeta que se va a crear.

Entonces este comando significa:

Python, usa el módulo venv para crear una carpeta llamada venv
Ejemplo con otro nombre

También podrías escribir:

python -m venv entorno

Eso significa:

Usa el módulo venv y crea una carpeta llamada entorno

Pero por convención, normalmente se usa:

venv

como nombre de carpeta.

Crear entorno virtual

Dentro de la carpeta de tu proyecto:

python -m venv venv

Si tu sistema usa python3:

python3 -m venv venv
Qué se crea después

Después del comando aparecerá una carpeta:

venv/

Esa carpeta contiene:

Python aislado
pip aislado
librerías del proyecto
configuración del entorno

No debes editar manualmente esa carpeta.

Activar entorno virtual en Linux

Para activar el entorno:

source venv/bin/activate
Cómo saber si está activo

Cuando el entorno está activo, normalmente aparece algo como:

(venv)

al inicio de la terminal.

Ejemplo:

(venv) ~/learning-flask $

Eso significa que ya estás trabajando dentro del entorno virtual.

Instalar Flask dentro del entorno

Con el entorno activo:

pip install flask

Ahora Flask queda instalado solo dentro de este proyecto.

Verificar Flask
pip show flask

Si Flask está instalado, verás información como:

Name: Flask
Version: ...
Location: ...
Desactivar entorno virtual

Cuando termines de trabajar:

deactivate

Esto te regresa al Python normal del sistema.

Flujo correcto
1. Crear carpeta del proyecto
2. Entrar a la carpeta
3. Crear entorno virtual
4. Activar entorno virtual
5. Instalar Flask
6. Trabajar en el proyecto
7. Desactivar entorno al terminar
Comandos resumidos
mkdir mi-proyecto-flask
cd mi-proyecto-flask

python -m venv venv
source venv/bin/activate

pip install flask
pip show flask

deactivate
Idea clave

El primer venv del comando es la herramienta de Python.

El segundo venv es el nombre de la carpeta creada.

python -m venv venv
          │    │
          │    └── nombre de la carpeta
          └─────── módulo de Python
Importante para Git

La carpeta venv/ normalmente NO se sube a GitHub.

Se agrega al archivo .gitignore.

Ejemplo:

venv/

Esto evita subir dependencias pesadas e innecesarias al repositorio.


























































