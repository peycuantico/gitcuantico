# Este es el README de la Guia de QFT :D

## La numeración de las versiones debe leerse de la siguiente forma:

vX.Y

###-> X = "Edición" 
La versión incorpora capítulos o secciones nuevas.

###-> Y = "Parche"
Se han arreglado fallos de la última versión.


# --------PATCH NOTES v0.1--------

1. En la solución de la ecuación de dirac (sec "Fermiones/campo espinorial"), ahora aparece el sumatorio sobre las helicidades, era un error.

2. El conmutador de el campo espinorial y los operadores de creación (b y d) ahora es un ANTICONUMTADOR (sec "Operadores de creación/Propiedades de los operadores").

3. A todas las expansiones en serie de Taylor de la S-matrix les faltaba un factor 1/2!, ha sido añadido y se han arreglado las expresiones que dependian de ello.

4. Los espinores de la seción "Fermiones/Propiedades de los espinores" tienen varios cambios:
	- Las propiedades de suma de espinores (las cuatro últimas filas) tenian índices alpha y beta, cuando debían ser alpha los dos.
	- La normalización de TODOS los espinores se ha cambiado, tal que u_new = \sqrt{2m} u_old, se ha añadido un disclaimer al final de la sección

- El propagador de Dirac ("Propagadores/Campo espinorial") tenia varios errores:
	- Faltaba el time ordering T{ } dentro del braket con el vacío.
	- La justificación de la notación con la matriz en el denominador tenia todos los signos cambiados.