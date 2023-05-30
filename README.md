# TP2_JS
 Trabajo Practico 2 JS
 Descripción del problema a resolver:

La problemática de la clase 09 consiste en construir un formulario en HTML con Bootstrap. El formulario debe contener los siguientes campos: 
    -Nombre completo, 
    -email, 
    -contraseña, 
    -repetir contraseña, 
    -edad, 
    -teléfono, 
    -dirección, 
    -ciudad, 
    -código postal y 
    -DNI. 
Además debe contar con un botón “Enviar”. 

El diseño debe ser responsive, de modo que si se visualiza el formulario desde un celular 
se deben mostrar los campos uno abajo del otro, 
pero si se ve desde un monitor de PC los campos se deben mostrar separados en dos columnas, con el botón enviar solo al final del formulario y centrado en medio de las dos columnas.

Se debe validar cada campo y mostrar un mensaje de error descriptivo abajo del campo que falló. 

Realizar las siguientes validaciones:
•	Nombre completo: Debe tener más de 6 letras y al menos un espacio entre medio.
•	Email: debe tener un formato de email válido.
•	Contraseña: Al menos 8 caracteres, formados por letras y números.
•	Edad: Número entero mayor o igual a 18.
•	Teléfono: Número de al menos 7 dígitos, no aceptar espacios, guiones ni paréntesis.
•	Dirección: Al menos 5 caracteres, con letras, números y un espacio en el medio.
•	Ciudad: Al menos 3 caracteres.
•	Código Postal: Al menos 3 caracteres.
•	DNI: Número de 7 u 8 dígitos.

La validación de cada campo se debe realizar en el evento “blur” de cada uno de los campos.

Además, si algún campo tiene un error de validación, en el evento “focus” de dicho campo debe desaparecer el mensaje porque se asume que el usuario está corrigiendo el error.

Al presionar el botón “Enviar” se debe mostrar un cartel emergente con la información cargada en el formulario en caso de que haya pasado todas las validaciones.

