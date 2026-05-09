# Primer proyecto Flask

En esta sección se preparará el entorno inicial para comenzar a trabajar con Flask de manera profesional.

El objetivo es:

- Crear un proyecto Flask
- Configurar un entorno virtual
- Instalar Flask
- Preparar la estructura inicial del proyecto

---

# Crear carpeta del proyecto

Primero se crea una carpeta para el proyecto.

Ejemplo:

```bash
mkdir flask-formulario

Entrar a la carpeta:

cd flask-formulario
Crear entorno virtual

Dentro de la carpeta del proyecto:

python -m venv venv
Explicación del comando
python -m venv venv
python

Ejecuta Python.

-m

Le dice a Python:

ejecuta un módulo
Primer venv
-m venv

Es el módulo oficial de Python para crear entornos virtuales.

Segundo venv
venv

Es el nombre de la carpeta donde se creará el entorno virtual.

Resultado

Después del comando aparecerá una carpeta:

venv/

Esa carpeta contiene:

Python aislado
pip aislado
Librerías del proyecto
Configuración del entorno
Activar entorno virtual

En Linux:

source venv/bin/activate
Cómo saber si está activo

La terminal mostrará algo similar a:

(venv)

Ejemplo:

(venv) ~/flask-formulario $

Eso significa que el entorno virtual ya está funcionando.

Instalar Flask

Con el entorno virtual activo:

pip install flask
¿Qué hace este comando?

Este comando:

Descarga Flask
Descarga dependencias necesarias
Instala Flask dentro del entorno virtual
Verificar Flask
pip show flask

Si Flask está correctamente instalado, aparecerá información como:

Nombre
Versión
Ruta de instalación
Crear archivo principal

Crear el archivo principal de Flask:

touch app.py
Idea importante

Hasta este punto todavía no existe una aplicación Flask funcional.

Solamente se preparó:

El proyecto
El entorno virtual
Flask
El archivo principal

El siguiente paso será escribir la primera aplicación Flask real.

Flujo profesional básico
Crear carpeta del proyecto
→ Crear entorno virtual
→ Activar entorno virtual
→ Instalar Flask
→ Crear archivo principal
→ Comenzar desarrollo
Estructura actual del proyecto
flask-formulario/
│
├── venv/
└── app.py
Importante para Git

La carpeta venv/ normalmente NO se sube a GitHub.

Debe agregarse al archivo .gitignore.

Ejemplo:

venv/
