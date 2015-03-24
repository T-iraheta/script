<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta http-equiv="content-type" content="text/html; charset=iso-8859-1">
<link rel="stylesheet" type="text/css" href="estilo_eje1.css">
	<title>ejercicio #1</title>

</head>

<header>
	<h1>ejercicio n° 1 </h1>
</header>
<body>


<section>

	<P>
		 Cree un script en php que imprima un mensaje usando 
		variables las cuales formaran una direcciOn de residencia, 
		la cual se debera separar por calle, colonia, numero de casa,
 		municipio y departamento, la salida impresa se debe de realizar con printf.
	</P>



<?php

$a='avenida san juan pablo 2°';
$b='narvaes';
$c=125;
$d='san luis talpa';
$e='la paz';


printf("direccion de recidencia  "."calle:  ".$a."  colonia:   ".$b."   n° casa:  ".$c."   municipio: ".$d."   departamento:  ".$e);

?>

</section>
</body>

</html>
