# Este es el README de la Guia de QFT :D

### La numeración de las versiones debe leerse de la siguiente forma:

vX.Y

### -> X = "Edición" 
La versión incorpora capítulos o secciones nuevas.

### -> Y = "Parche"
Se han arreglado fallos de la última versión.


# --------PATCH NOTES v0.1--------

- En la solución de la ecuación de dirac (sec **"Fermiones/campo espinorial"**), ahora aparece el sumatorio sobre las helicidades, era un error.

- El conmutador de el campo espinorial y los operadores de creación ($\hat b$ y $\hat d$) ahora es un ANTICONUMTADOR (sec **"Operadores de creación/Propiedades de los operadores"**).

- A todas las expansiones en serie de Taylor de la $S$-matrix les faltaba un factor $\frac{1}{2!}$, ha sido añadido y se han arreglado las expresiones que dependian de ello.

- Los espinores de la seción **"Fermiones/Propiedades de los espinores"** tienen varios cambios:
	- Las propiedades de suma de espinores (las cuatro últimas filas) tenian índices $\alpha$ y $\beta$, cuando debían ser $\alpha$ los dos.
	- La normalización de TODOS los espinores se ha cambiado, tal que $u_{new} = \sqrt{2m}\\;u_{old}$, se ha añadido un disclaimer al final de la sección

- El propagador de Dirac (**"Propagadores/Campo espinorial"**) tenia varios errores:
	- Faltaba el time ordering $\mathcal{T}\\{\\;\\}$ dentro del braket con el vacío.
	- La justificación de la notación con la matriz en el denominador tenia todos los signos cambiados.
