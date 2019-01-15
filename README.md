# ansible-tests

Primera prueba realizado con ansible, donde se realizan los siguientes pasos:

	- Actualizar los repositorios de paquetes del sistema
	- Comprobar que Apache2 está instalado o no, y en caso de no estar instalado, lo instala en el equipo automáticamente.
	- Cambiar el fichero index.html que viene por defecto en Apache2, por un fichero index.html para una página estática.

La comprobación se realiza accediendo a la dirección IP 10.0.0.2 y mostrará la información correspondiente a index.html
