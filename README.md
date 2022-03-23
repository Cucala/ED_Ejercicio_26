# Ejercicio 26 Interfaces y clases abstractas
## Primero DAW Semipresencial
## Entornos de desarrollo
## IES Pere Maria

**GESTI�N DE ESTUDIANTES-EMPLEADOS**

![UML ESTUDIANTES-EMPLEADOS](/assets/images/uml.png)
Observa el esquema de clases de arriba. Trata de recoger una estructura formada por trabajadores de diversas categor�as (obreros, trabajadores cualificados, becarios y jefes de departamento). Entiende este esquema como una propuesta para desarrollar la aplicaci�n basada en objetos que se especifica a continuaci�n. Tienes libertad para modificarlo de forma razonada en funci�n de tu propia interpretaci�n de la aplicaci�n, y de las necesidades que se planteen en la especificaci�n.

**ESPECIFICACI�N:**

- Todas las clases tienen un constructor que admite todos sus campos como par�metros
- Crea una clase abstracta para empleados en la que informacion () ser� un m�todo que devolver� un texto indicando:
	- para los becarios su carrera y departamento: > �Carrera: Biolog�a, Departamento: Ciencias�
	- En el caso de cualificados titulaci�n y departamento, por ejemplo: > �Titulaci�n: F�sico, Departamento: Ciencias�
	- Y en el caso de obreros su destino de trabajo y el Precio de las horas extra: > �Destino: Alicante, Precio Horas Extra: 80��
- Crea una interface para Estudiantes. Dispondr� de la especificaci�n de 3 m�todos:
	- Ex�menes: Devolver� una lista con 3 notas del estudiante, a partir de las cuales se calcular� la nota media
	- Universidad: Proporcionar� el nombre de la universidad a la que pertenece el alumno
	- NotaMedia: Calcula la media num�rica (con un decimal) de las 3 notas que disponemos del alumno.
- La aplicaci�n mostrar� una lista (emplea, por ejemplo, el control listview) con el nombre y los apellidos de los empleados y cada vez que se seleccione un elemento de la lista se rellenar�n textbox con toda la informaci�n almacenada del empleado.
- Existir� un bot�n a�adir que permitir� crear un empleado del tipo que se desee, permitiendo rellenar todos los datos que permita dicho tipo.
- Tambi�n se presentar� un bot�n eliminar para borrar el usuario seleccionado.
- Ten en cuenta toda la funcionalidad impl�cita y la usabilidad que debe presentar la aplicaci�n. Emplea todos los conocimientos que hemos ido adquiriendo para personalizar y mejorar tu aplicaci�n, por ejemplo, �podr�as utilizar alg�n men� contextual? �querr�as a�adir y controlar alguna restricci�n? �dar opciones al usuario, por ejemplo, para establecer una serie de universidades que sean las �nicas que pueda elegir?