# api_residencias_web2

Rutas de la api: 

appresidencias/backend/usuarios.php 
appresidencias/backend/residencias.php 



GET

/usuarios.php

	Obtiene el listado de todos los usuarios


/usuarios.php?numeroControl=valor

	Obtiene un unico usuario buscado por numero de control


/redisencias.php
	Obtiene el listado de todos los proyectos


/residencias.php?id=valor
	
	Obtiene una unica residencia buscada por id



POST

/usuarios.php?buscarProyecto

--se envia json con numeroControl--


	Obtiene el proyecto solicitado por un usuario


/usuarios.php?solicitar

	Agrega un proyecto a un usuario
	
--se envia json con numeroControl y idResidencia--


/usuarios.php?login
	
	Valida si un usuario existe en la bd para logearse

--se envia json con numeroControl y pass--


/usuarios.php

	Se registra un nuevo usuario

--se envia json con numeroControl, pass, nombre, creditosC, creditos, servicio--



/redisencias.php

	Se registra una nueva residencia

--se envia json con nombre, duracion, lugar, descripcion--



DELETE


/usuarios.php?numeroControl

	Borra un usuario por numeroControl



/redisencias.php?id

	Borra una residencia por id




PUT



/usuarios.php

	Se actualiza un usuario

--se envia json con numeroControl, pass, nombre, creditosC, creditos, servicio--



/redisencias.php

	Se actualiza una residencia

--se envia json con id, nombre, duracion, lugar, descripcion--


