<div align="center">
	<h1><strong>Programacion I</strong></h1>
	<strong>Hecho por:</strong> Miller Alexander Quiroga Campos
</div>
<br>

<p>
La materia de Programación I es una asignatura fundamental que introduce a los estudiantes en los conceptos esenciales del pensamiento computacional. El curso abarca desde los fundamentos teóricos hasta la aplicación práctica, sentando las bases para el desarrollo de software. 
<br>

<strong>Temas Abordados:</strong> 

1. Algoritmos: El curso inicia con la definición y el diseño de algoritmos, que son la secuencia lógica de pasos para resolver un problema.  Se enfatiza la importancia de la claridad y la eficiencia en su creación.
2. Estructuras de datos: Se estudian estructuras básicas como arreglos y listas, que permiten organizar y manipular datos de manera eficiente.
3. Estructuras de control: Los estudiantes aprenden a manejar el flujo de ejecución de un programa mediante estructuras de control, incluyendo bucles (for, while) y condicionales (if/else), que son cruciales para tomar decisiones dentro del código.
4. Funciones: Un componente vital del curso es el uso de funciones para modularizar el código. Esto promueve la reutilización, facilita la lectura y reduce la complejidad de los programas.
5. Matrices: Finalmente, se introducen las matrices, que son arreglos bidimensionales, y se exploran sus aplicaciones en problemas que requieren el manejo de datos en forma de tabla o cuadrícula, como en el álgebra lineal o el procesamiento de imágenes.

Programación I no solo enseña a "escribir código", sino que desarrolla la lógica de pensamiento necesaria para abordar y solucionar problemas de manera sistemática y estructurada, preparando a los estudiantes para cursos más avanzados en su carrera de pregrado de Matemáticas Aplicada.
</p>

## __Material interactivo__

Contiene el material de clases de programación en Python hecho en Google Colab.

<div align="center">
	
| Título | Temas | Enlace |
| ------ | ------- | ------ |
| __Introducción a *Python*__ | Variables | [![Abrir PDF](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1hXwGcHaNzv4hcZWw7i6ZHc1Mn3ihibvP/view?usp=sharing) |
| __Estructura de Datos__ | Colecciones -> listas, tuplas, diccionarios, conjuntos | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/10oIlXVfklJKTDvJqe384pI721v9FsgWT/view?usp=sharing) |
| __Condicionales__ | Estructuras if-elif-else | [![Abrir PDF](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1z2czYu6GlpsqGlWk1jIqIQaBRHHQs6OC/view?usp=sharing) |
| __Bucles__ | Ciclos while | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1yPLYiuYx83GWL-UPx7kuhoKd1-7XBRRT/view?usp=sharing) |
| __Bucles__ | Ciclos for | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1hz7QBd4qnb2JbnlOo0Now64m7uHJ4SrV/view?usp=sharing) |
| __Bucles__ | Ciclos for | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1hz7QBd4qnb2JbnlOo0Now64m7uHJ4SrV/view?usp=sharing) |
| __Matrices - Numpy__ | Utilizar Numpy para Matrices | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1Burfuo4SSFjM3xpMhfs51Jxrlkr5ImW4/view?usp=sharing)|
| __Funciones__ | Funciones | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/15w9N0ApckN2DjnMGzc7Skplvug5KqpdK/view?usp=sharing) |
| __Errores y Excepciones__ | try: except | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1n7OSthD36MJNqGD-nUx8Mh_uxEaxrBh8/view?usp=drive_link)|

</div>

--- 

# Proyecto: Sistema Bancario en Python

## Descripción General

Este proyecto tiene como propósito integrar todos los conceptos vistos durante el curso de programación en Python, aplicando **funciones**, **estructuras de control**, **estructuras de datos**, **manejo de errores** y **pensamiento algorítmico**.  

El sistema simulará las operaciones básicas de un banco: inscripción de clientes, apertura de cuentas, depósitos, retiros, consultas de saldo y generación de extractos de movimientos.  

## Objetivo General

Desarrollar un sistema bancario en consola que permita gestionar clientes y sus cuentas, aplicando la programación modular y el uso correcto de funciones en Python.

## Objetivos Específicos

1. Aplicar funciones con y sin parámetros, con y sin retorno.  
2. Implementar condicionales simples y compuestas (and, or, not).  
3. Utilizar bucles `while` y `for` para el control del flujo del programa.  
4. Manejar estructuras de datos como listas, tuplas, diccionarios y conjuntos.  
5. Implementar mecanismos básicos de validación y manejo de excepciones.  
6. Promover la organización, reutilización y claridad del código mediante el uso de funciones.

---

## Requisitos Funcionales

### Desde la perspectiva del usuario

1. El usuario debe poder **registrarse** en el sistema bancario proporcionando su nombre, número de identificación y contraseña.  
2. El usuario podrá **abrir una cuenta bancaria** después de registrarse.  
3. El usuario podrá **consultar su saldo** en cualquier momento.  
4. El usuario podrá **realizar depósitos y retiros** en su cuenta.  
5. El usuario podrá **transferir dinero** a otra cuenta registrada en el sistema.  
6. El usuario podrá **consultar el historial de movimientos** (depósitos, retiros y transferencias).  
7. El usuario podrá **descargar o visualizar un extracto** con sus movimientos.  
8. El usuario podrá **cerrar sesión** y volver a ingresar con su contraseña.  

### Desde la perspectiva del equipo desarrollador

1. El sistema deberá **almacenar la información de los clientes y sus cuentas** usando estructuras de datos adecuadas (diccionarios o listas de diccionarios).  
2. Las operaciones bancarias deberán implementarse como **funciones independientes y modulares**.  
3. Se debe utilizar un **menú principal** para guiar las opciones del usuario (registrarse, iniciar sesión, salir).  
4. Cada usuario autenticado deberá tener acceso solo a **sus propias cuentas y transacciones**.  
5. El sistema debe manejar **errores comunes** (por ejemplo, intentos de retiro sin saldo suficiente, datos incorrectos, duplicados en registro, etc.).  
6. El programa deberá **ejecutarse en consola** sin uso de interfaces gráficas.  
7. El sistema deberá garantizar la **consistencia de los datos** (por ejemplo, no permitir transacciones negativas o duplicadas).  
8. Todas las funciones deberán tener un propósito claro y estar documentadas mediante comentarios.

---

## Requisitos No Funcionales

1. **Usabilidad:** El menú debe ser claro, con instrucciones fáciles de seguir.  
2. **Mantenibilidad:** El código debe estar organizado por funciones.  
3. **Legibilidad:** Se deben incluir comentarios explicativos y nombres de variables descriptivos.  
4. **Confiabilidad:** El sistema debe validar las entradas del usuario y manejar excepciones.  

---

## Funcionalidades Principales del Sistema

1. **Registro e inicio de sesión de usuarios**  
   - Registro de clientes nuevos.  
   - Validación de credenciales.  

2. **Gestión de cuentas bancarias**  
   - Apertura de cuentas (asociadas a un cliente).  
   - Consulta de saldo.  

3. **Transacciones**  
   - Depósitos.  
   - Retiros.  
   - Transferencias entre cuentas.  

4. **Historial de movimientos**  
   - Registro de operaciones (fecha, tipo, monto, saldo resultante).  
   - Generación de extractos.  

5. **Manejo de errores y validaciones**  
   - Control de datos incorrectos.  
   - Prevención de operaciones no válidas.  

---

## Recomendaciones para los Estudiantes

- Organiza el código en **bloques lógicos**: funciones para registro, transacciones, y consultas.  
- Evita repetir código; utiliza funciones para tareas repetitivas.  
- Utiliza **diccionarios** para almacenar información de usuarios y sus cuentas.  
- Implementa **bucles** para mantener el programa activo hasta que el usuario decida salir.  
- Prueba cada función de forma independiente antes de integrar todo el sistema.  

---

## Ejemplo de Flujo del Programa

1. Menú principal:  
   - Registrarse  
   - Iniciar sesión  
   - Salir  

2. Una vez autenticado:  
   - Abrir cuenta  
   - Consultar saldo  
   - Depositar dinero  
   - Retirar dinero  
   - Transferir dinero  
   - Consultar movimientos  
   - Descargar extracto  
   - Cerrar sesión  

---
---

# PROYECTO FINAL: RED ACADÉMICA UNIVERSITARIA  
**Curso:** Programación en Python  
**Profesor:** Charlie  
**Duración estimada:** 2 semanas  
**Modalidad:** Individual o en parejas  

---

## Descripción general

El propósito de este proyecto es desarrollar un **sistema en consola** que simule el funcionamiento de una **red académica universitaria**, donde los estudiantes puedan registrarse, completar su perfil, conectar con otros compañeros, crear y unirse a grupos de interés o estudio, y visualizar sus interacciones dentro de la red.

El sistema se construirá **únicamente utilizando funciones en Python**, aplicando todos los temas vistos durante el curso:

- Funciones (con, sin parámetros, con retorno, recursivas y lambda)
- Condicionales (`if`, `elif`, `else`)
- Operadores lógicos (`and`, `or`, `not`)
- Estructura `match-case`
- Bucles (`while`, `for`)
- Estructuras de datos (listas, tuplas, diccionarios, conjuntos)
- Manejo de errores y excepciones

---

## Objetivos de aprendizaje

- Aplicar los fundamentos de la **programación estructurada** y el **uso modular de funciones**.  
- Desarrollar la lógica de un sistema con **estructuras de datos compuestas y anidadas**.  
- Implementar **procesos de validación y control de errores**.  
- Simular funcionalidades reales de una red social académica mediante programación.  
- Fortalecer la capacidad de análisis y resolución de problemas con pensamiento computacional.

---

## Escenario general

Imagina que la universidad ha solicitado el desarrollo de una **Red Académica Universitaria (RAU)** que permita a los estudiantes:
- Crear un perfil personal con intereses académicos.
- Buscar y conectar con compañeros.
- Crear grupos de estudio, investigación o colaboración.
- Unirse a grupos de interés existentes.
- Publicar mensajes dentro de sus grupos.
- Consultar su lista de grupos y conexiones.
- Visualizar y guardar un reporte (extracto) de sus actividades.

Todo debe desarrollarse **sin interfaces gráficas**, únicamente con menús e interacción por consola.

---

## Requisitos funcionales

### Desde el punto de vista del usuario

1. **Registro de usuario:**  
   - El estudiante debe poder registrarse con nombre, correo institucional, carrera y contraseña.  
   - No puede registrarse dos veces con el mismo correo.  

2. **Inicio de sesión:**  
   - El sistema debe validar el correo y la contraseña.  
   - Una vez dentro, podrá acceder a las opciones del menú principal.  

3. **Gestión del perfil:**  
   - Permitir agregar intereses académicos (ejemplo: *Ciencia de Datos, Robótica, Turismo, Física*).  
   - Permitir ver o editar su perfil.  

4. **Red de contactos:**  
   - Buscar compañeros por nombre o carrera.  
   - Enviar o aceptar solicitudes de conexión.  
   - Ver la lista de contactos actuales.  

5. **Grupos de interés:**  
   - Crear grupos nuevos (de estudio, investigación o colaboración).  
   - Unirse a grupos existentes.  
   - Ver los grupos a los que pertenece.  
   - Permitir publicar mensajes o aportes dentro de un grupo.  

6. **Consultas y reportes:**  
   - Mostrar la cantidad total de grupos y conexiones del usuario.  
   - Exportar un archivo `.txt` con la información del perfil, sus intereses, grupos y conexiones.  

---

### Desde el punto de vista del desarrollador

1. El sistema debe construirse utilizando **funciones** que representen cada proceso.  
   Ejemplo:
   ```python
   def registrar_usuario(usuarios): ...
   def iniciar_sesion(usuarios): ...
   def crear_grupo(grupos): ...
   def unir_a_grupo(usuarios, grupos): ...
   ```

2. Los datos deben manejarse con diccionarios anidados y listas:
```
usuarios = {
    "correo@uni.edu": {
        "nombre": "Laura",
        "carrera": "Matemáticas Aplicadas",
        "password": "abc123",
        "intereses": ["Ciencia de Datos", "Estadística"],
        "conexiones": [],
        "grupos": []
    }
}

grupos = {
    "Grupo Ciencia de Datos": {
        "tipo": "Estudio",
        "miembros": ["correo@uni.edu", "otro@uni.edu"],
        "publicaciones": []
    }
}
```
3. Se deben emplear estructuras de control:

- Condicionales para validar datos.
- Bucles para iterar listas o menús.
- Manejo de errores con try-except en entradas numéricas o campos obligatorios.

4. Implementar al menos una función recursiva o lambda en el programa.

5. El sistema debe tener un menú principal interactivo con al menos 8 opciones.

5. El código debe estar comentado y organizado en funciones claras.

# Requisitos no funcionales

- Lenguaje: Python 3.10+
- Interacción: por consola (sin interfaz gráfica)
- Estructura del proyecto:

```
proyecto_red_academica/
├── red_academica.py
├── README.md
└── datos.txt   (opcional, para guardar registros)
```

# Sugerencia de estructura funcional

| Módulo / Función      | Descripción breve                                                 |
| --------------------- | ----------------------------------------------------------------- |
| `registrar_usuario()` | Registra un nuevo usuario en el sistema.                          |
| `iniciar_sesion()`    | Verifica credenciales y devuelve el usuario autenticado.          |
| `editar_perfil()`     | Permite agregar o modificar intereses.                            |
| `buscar_usuarios()`   | Busca usuarios por nombre o carrera.                              |
| `enviar_solicitud()`  | Envía una solicitud de conexión.                                  |
| `aceptar_solicitud()` | Acepta una solicitud pendiente.                                   |
| `crear_grupo()`       | Crea un nuevo grupo de interés o estudio.                         |
| `unirse_a_grupo()`    | Une al usuario a un grupo existente.                              |
| `publicar_mensaje()`  | Agrega mensajes dentro de un grupo.                               |
| `ver_reporte()`       | Muestra y guarda la información del usuario en un archivo `.txt`. |

# Criterios de evaluación

| Criterio                                                          | Ponderación |
| ----------------------------------------------------------------- | ----------- |
| Estructura funcional del código (uso correcto de funciones)       | 25%         |
| Uso adecuado de estructuras de datos (listas, diccionarios, etc.) | 20%         |
| Aplicación de condicionales, bucles y validaciones                | 20%         |
| Implementación de manejo de errores y modularidad                 | 15%         |
| Creatividad, documentación y presentación                         | 10%         |
| Funcionamiento general y coherencia de la simulación              | 10%         |

# Recomendaciones para el desarrollo

- Define primero las funciones básicas, antes de codificar el menú principal.
- Usa diccionarios para representar usuarios y grupos.
- Guarda los datos en memoria (no es necesario usar archivos binarios ni bases de datos).
- Asegúrate de validar entradas y prevenir errores comunes.
- Comenta tu código para hacerlo comprensible.
- Si lo deseas, puedes extender tu sistema con funciones adicionales como:
	- Sistema de mensajes privados.
	- Sistema de reputación o puntos por participación.
	- Filtrado de grupos por tipo o carrera.

# Entregables

- Archivo principal red_academica.py
- Archivo README.md con:
- Descripción del programa
- Integrantes del equipo (2 integrantes)
- Estructura de datos utilizada
- Explicación de las funciones principales
- Archivo reporte_usuario.txt (generado por el programa)
- Video corto (opcional, máximo 3 minutos) mostrando su funcionamiento.
- Sustentación de parte de los 2 integrantes al profesor y sus compañeros de clase

# Desafío adicional (opcional)

- Agrega una función que, mediante recursividad o lambda, permita:
  	 - Buscar grupos o compañeros que compartan al menos un interés común con el usuario actual.

# Nota: Comentario del profesor

“Este proyecto es la oportunidad para demostrar todo lo que aprendiste sobre lógica, estructuras de datos y funciones.
No busques hacer algo complejo, sino algo funcional, bien estructurado y con sentido lógico.
Tu red académica será tu carta de presentación como futuro desarrollador.”

# Fecha de entrega

- Semana 2 después de la última clase del módulo.

# Enviar a:

Aula virtual link de github → Actividad: Proyecto Final — Red Académica Universitaria

- Formato de entrega: .zip en aula virutal y repositorio en GitHub



### __Herramientas__

Herramientas sugeridas para el proceso de aprendizaje:

* [Google colab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index#recent=true) - Material interactivo para Python.
* [Spyder](https://www.spyder-ide.org/) - Entorno de Desarrollo Integrado para Ciencia de Datos
* [PSeInt](https://pseint.sourceforge.net/) - Entorno para trabajar Diagramas de flujo y psedocódigo
* [Raptor](https://raptor.martincarlisle.com/) - Entorno para trabajar Diagramas de flujo
* [Visual Studio Code](https://code.visualstudio.com/)- Entorno de Desarrollo Integrado para Desarrollo
* [Github](https://code.visualstudio.com/)- Entorno de Sistema de Control de versiones y trabajo colaborativo de desarrollo.
