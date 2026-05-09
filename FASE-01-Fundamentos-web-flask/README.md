````md
# ¿Qué es Flask?

## ¿Qué es un framework web?

Python por sí solo no sabe trabajar como una aplicación web.

Python puede ejecutar scripts y programas, por ejemplo:

```python
print("Hola mundo")
````

El script se ejecuta y termina.

Sin embargo, una aplicación web necesita muchas más cosas:

* Escuchar peticiones desde un navegador
* Manejar URLs
* Responder páginas HTML
* Recibir formularios
* Mantener un servidor ejecutándose
* Procesar datos enviados por usuarios

Aquí es donde entran los frameworks web.

---

## Entonces, ¿qué es un framework web?

Un framework web es un conjunto de herramientas y estructuras que ayudan a construir aplicaciones web.

En lugar de programar todo desde cero, el framework ya proporciona funcionalidades importantes como:

* Manejo de rutas
* Servidor web
* Respuestas HTTP
* Formularios
* Templates HTML
* Organización de proyectos
* Herramientas backend

El framework permite enfocarse más en la lógica de la aplicación y menos en construir toda la infraestructura manualmente.

---

# ¿Qué es Flask?

Flask es un microframework web para Python.

Su objetivo principal es permitir crear aplicaciones web utilizando Python de manera sencilla, flexible y minimalista.

Flask conecta:

```text
Navegador web ↔ Python
```

Gracias a Flask, Python puede:

* Recibir peticiones desde un navegador
* Procesar información
* Consultar bases de datos
* Mostrar páginas HTML
* Crear sistemas web
* Construir APIs
* Manejar formularios

---

# ¿Qué significa microframework?

Microframework no significa “débil” o “limitado”.

Significa que Flask proporciona solamente lo esencial para construir aplicaciones web.

Flask intenta mantenerse ligero y flexible.

A diferencia de frameworks más grandes, Flask no obliga a trabajar de una única manera.

Esto permite:

* Mayor control del proyecto
* Comprender mejor cómo funciona el backend
* Construir arquitecturas personalizadas
* Aprender desarrollo web más profundamente

---

# ¿Qué problema resuelve Flask?

Flask resuelve el problema de crear aplicaciones web con Python.

Sin Flask, sería necesario programar manualmente:

* Servidor web
* Manejo de URLs
* Respuestas HTTP
* Conexiones web
* Formularios
* Renderizado HTML

Flask ya proporciona toda esa estructura base.

Gracias a Flask, el desarrollador puede enfocarse en:

* Lógica del negocio
* Formularios
* Bases de datos
* Sistemas internos
* APIs
* Herramientas web

---

# ¿Para qué sirve Flask?

Flask puede utilizarse para crear:

* Sitios web
* Sistemas administrativos
* Herramientas internas
* Formularios web
* APIs REST
* Dashboards
* Automatizaciones web
* Sistemas empresariales

---

# Idea importante

Flask no reemplaza Python.

Flask es una herramienta construida sobre Python para permitir crear aplicaciones web.

La lógica sigue programándose con Python.

Flask solamente proporciona la estructura web necesaria para conectar el backend con el navegador.

```
```







# Backend vs Frontend

Cuando una persona utiliza una página o sistema web, realmente está interactuando con dos partes diferentes:

- Frontend
- Backend

Ambas trabajan juntas para que una aplicación funcione correctamente.

---

# ¿Qué es el Frontend?

El frontend es la parte visual de una aplicación web.

Es todo lo que el usuario puede ver e interactuar directamente desde el navegador.

Por ejemplo:

- Botones
- Formularios
- Menús
- Texto
- Colores
- Imágenes
- Animaciones
- Diseño visual

El frontend se ejecuta principalmente en el navegador del usuario.

---

# Tecnologías comunes de frontend

Las tecnologías más utilizadas en frontend son:

- HTML
- CSS
- JavaScript

---

# Función principal del frontend

El frontend se encarga de:

- Mostrar información
- Permitir interacción con el usuario
- Capturar datos desde formularios
- Mejorar la experiencia visual

---

# ¿Qué es el Backend?

El backend es la parte lógica y funcional de una aplicación web.

Normalmente el usuario no puede verlo directamente.

El backend trabaja en el servidor y se encarga del procesamiento interno del sistema.

---

# Funciones comunes del backend

El backend puede encargarse de:

- Procesar formularios
- Validar datos
- Manejar usuarios
- Conectarse a bases de datos
- Guardar información
- Generar reportes
- Enviar correos
- Crear APIs
- Ejecutar lógica del sistema

---

# Flask pertenece principalmente al backend

Flask es una herramienta backend.

Flask trabaja principalmente con:

- Python
- Formularios
- Lógica
- Bases de datos
- PostgreSQL
- Rutas web
- Respuestas HTTP

---

# Ejemplo práctico

## Frontend

En un formulario web, el frontend sería:

- Inputs
- Botones
- Diseño visual
- Formularios HTML
- Colores y estilos

---

## Backend

El backend sería:

- Recibir los datos del formulario
- Validar información
- Guardar datos en PostgreSQL
- Generar PDFs
- Enviar correos
- Procesar lógica interna

---

# Relación entre frontend y backend

Frontend y backend trabajan juntos constantemente.

El frontend permite que el usuario interactúe con el sistema.

El backend procesa toda la información y responde al navegador.

---

# Idea importante

## Frontend
Es lo que el usuario VE.

## Backend
Es lo que el sistema HACE.

---

# Enfoque actual de aprendizaje

El enfoque principal de este aprendizaje estará orientado al backend utilizando:

- Python
- Flask
- PostgreSQL
- Linux
- Automatización
- Sistemas internos












# Cliente y servidor

una aplicación web funciona porque existen dos partes que se comunican entre si:

-Cliente
-Servidor

Esta relación es la base de casi todo el desarrollo web.

---

# ¿Qué es el Cliente?

El cliente es quien solicita la información o servicios.

En el desarrollo web, normalmente el cliente es el navegador.

por ejemplo:

-Firefox
-Chrome
-Edge
-Safari

Cuando una persona entra a una página web, el navegador actua como cliente.

---

#ejemplo

Cuando escribes una direccion en el navegador

https://ejemplo.com

El navegador está diciendo :   Quiero ver esa página

Ese mensaje se envia hacia un servidor

---

# ¿Qué es el Servidor?

El servidor es la maquina o sistema que recibe la petición del cliente y responde.

un servidor puede ser:

-Una computadora física
-Una máquina virtual
-Una VPS
-Una lap configurada com oservidor local
-Un servidor en la nube

#¿Qué hace el servidor?

-Recibe peticiones
-Procesar logica
-Consultar bases de datos
-Leer archivos
-generar respuestas
-Enviar HTML, JSON, imagenes o archivos
-Ejecutar aplicaciones backend



#Relación CLiente Servidor

Cliente → solicita algo → Servidor
Servidor → responde algo → Cliente

Ejemplo:

Navegador -> Solicita la página principal
Servidor  -> responde con HTML


## Ejemplo con Flask 

Cuando uses Flask, Flask vivirá del lado del servidor.

El flujo sería:

Navegador
→ solicita una URL
→ Flask recibe la petición
→ Flask ejecuta una función
→ Flask devuelve una respuesta
→ Navegador muestra el resultado


##Ejemplo aplicado a un formulario

Imagina tu formulario para clientes.

Cliente

El cliente sería el navegador de la persona que llena el formulario.

La persona escribe:

Nombre del negocio
Teléfono
Tipo de página
Comentarios
Servidor

El servidor recibe esa información mediante Flask.

Luego Flask podría:

Validar los datos
Generar un resumen
Guardar la información
Enviar un correo
Crear un PDF
Mostrar una página de confirmación
Importante

El cliente no ejecuta directamente la lógica del backend.

El cliente solo envía solicitudes y recibe respuestas.

La lógica importante vive del lado del servidor.

Idea clave
Cliente = quien pide
Servidor = quien procesa y responde
En este aprendizaje

Cuando trabajemos con Flask:

El navegador será el cliente
Flask será parte del servidor
Python procesará la lógica
PostgreSQL guardará datos cuando sea necesario








---
---


# Ciclo Request / Response

El ciclo request/response es uno de los conceptos más importantes del desarrollo web.

Prácticamente toda aplicación web moderna funciona siguiendo este flujo.

Flask trabaja constantemente utilizando este modelo.

---

# ¿Qué significa request?

Request significa:

petición o solicitud

Un request ocurre cuando un cliente solicita algo al servidor.

#Ejemplos de requests

Cuando un usuario:

Abre una página web
Hace clic en un enlace
Envía un formulario
Inicia sesión
Busca información
Descarga un archivo

el navegador genera una request hacia el servidor.

#¿Qué contiene una request?

Una request puede contener:

URL solicitada
Datos de formularios
Tipo de petición
Headers
Cookies
Información enviada por el cliente

---

#¿Qué significa response?

Response significa:

respuesta

Es lo que el servidor devuelve después de procesar la request.

Ejemplos de responses

El servidor puede responder con:

HTML
JSON
Imágenes
PDFs
Archivos
Mensajes de error
Confirmaciones
Datos desde una base de datos
Flujo completo

El ciclo básico es:

Cliente → Request → Servidor
Servidor → Response → Cliente

---

#Ejemplo sencillo
-Paso 1

El usuario entra a:

https://misitio.com

-Paso 2

El navegador envía una request al servidor.

La request dice algo similar a:

Quiero acceder a la página principal.

-Paso 3

Flask recibe la request.

Flask analiza:

Qué URL se solicitó
Qué función debe ejecutarse
Qué datos necesita procesar

-Paso 4

Flask ejecuta la lógica correspondiente.

Por ejemplo:

Consultar PostgreSQL
Procesar un formulario
Validar información
Generar contenido HTML

-Paso 5

Flask genera una response.

La response puede ser:

Una página HTML
Un mensaje
Datos
Un archivo

-Paso 6

El navegador recibe la response y la muestra al usuario.


---

#Ejemplo con tu formulario
Request

El cliente llena:

Nombre del negocio
Correo
Tipo de proyecto

y presiona:

Enviar

El navegador envía toda esa información al servidor.

Procesamiento

Flask recibe los datos y puede:

Validarlos
Guardarlos
Generar un PDF
Enviar un correo
Registrar información en PostgreSQL
Response

Flask responde algo como:

Gracias por completar el formulario.

El navegador muestra esa respuesta al usuario.

---

#Idea importante

Las aplicaciones web realmente funcionan como conversaciones constantes entre:

Cliente
Servidor

El cliente pide información.

El servidor procesa y responde.

Relación con Flask

Flask está diseñado precisamente para manejar:

Requests
Procesamiento backend
Responses

Todo Flask gira alrededor de este flujo.

# Idea clave
Request = el cliente pide algo
Response = el servidor responde algo







---
---




# HTTP básico

HTTP es uno de los protocolos más importantes del desarrollo web.

Prácticamente toda comunicación entre navegador y servidor ocurre utilizando HTTP.

Flask trabaja constantemente utilizando HTTP.

---

# ¿Qué es HTTP?

HTTP significa:

```text
HyperText Transfer Protocol
````

o en español:

```text
Protocolo de Transferencia de Hipertexto
```

---

# ¿Qué hace HTTP?

HTTP define las reglas de comunicación entre:

* Cliente
* Servidor

Gracias a HTTP, un navegador puede comunicarse correctamente con un servidor web.

---

# Ejemplo simple

Cuando escribes:

```text
https://google.com
```

el navegador utiliza HTTP para comunicarse con el servidor de Google.

---

# Comunicación web básica

El flujo normalmente es:

```text
Navegador
→ envía petición HTTP
→ servidor procesa
→ servidor responde mediante HTTP
→ navegador muestra resultado
```

---

# HTTP trabaja con requests y responses

HTTP organiza la comunicación utilizando:

* Requests
* Responses

---

# Métodos HTTP

HTTP utiliza diferentes métodos para indicar qué quiere hacer el cliente.

Los más importantes al iniciar son:

* GET
* POST

---

# Método GET

GET se utiliza principalmente para:

```text
obtener información
```

Ejemplos:

* Abrir una página
* Consultar información
* Ver contenido

---

# Ejemplo de GET

Cuando entras a:

```text
https://misitio.com
```

normalmente el navegador hace una request GET.

El servidor responde con la página solicitada.

---

# Método POST

POST se utiliza principalmente para:

```text
enviar información al servidor
```

Ejemplos:

* Formularios
* Login
* Registro de usuarios
* Envío de datos

---

# Ejemplo de POST

Cuando una persona llena un formulario y presiona:

```text
Enviar
```

el navegador normalmente envía una request POST.

La información viaja hacia el servidor.

---

# Diferencia importante

## GET

Se utiliza para:

* Consultar
* Leer
* Obtener información

---

## POST

Se utiliza para:

* Enviar
* Guardar
* Procesar datos

---

# HTTP Status Codes

El servidor responde utilizando códigos HTTP.

Estos códigos indican qué ocurrió con la petición.

---

# Algunos códigos importantes

## 200

```text
OK
```

La petición fue exitosa.

---

## 404

```text
Not Found
```

La página no existe.

---

## 500

```text
Internal Server Error
```

Ocurrió un error en el servidor.

---

## 403

```text
Forbidden
```

El acceso fue denegado.

---

# Relación con Flask

Flask trabaja directamente con HTTP.

Cuando uses Flask:

* Flask recibirá requests HTTP
* Flask procesará métodos GET y POST
* Flask devolverá responses HTTP

---

# Ejemplo práctico con Flask

## GET

Usuario entra a:

```text
/cliente
```

Flask devuelve una página HTML.

---

## POST

Usuario llena formulario y presiona enviar.

Flask recibe los datos enviados.

---

# Idea importante

HTTP es el lenguaje básico de comunicación entre:

* Navegador
* Servidor

Sin HTTP no existiría la comunicación web moderna.

---

# Idea clave

```text
GET = obtener información
POST = enviar información
```


















































































































