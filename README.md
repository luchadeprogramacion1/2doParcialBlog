# 2doParcialBlog
#Avance 2do Parcial

#Profe un breve comentario del porque visualizas en este proyecto varios commits mios, es que fuimos trabamos individualmente y nos unimos para complementar lo que Maria Eugenia tenia https://github.com/maruqueta/mvcframework con lo que yo habia avanzando y unimos los trabajos, ella enviandome por wapps lo que venia avanzando ya que tuvo dificultades con la PC. Cualquier cosa quedamos atentos a tus comentarios.

#PD. perdon por lo visual, no nos dio el tiempo para poder hacerlo presentable.

#Integrantes.
#Maria Eugenia Aguiar
#Luis E. Mendoza

#Profesor.
#Gonzalo Martinez

#Creacion de BD

#CREATE DATABASE baseblog;
#CREATE TABLE `usuarios` (
#  `IdUsuario` bigint(20) UNSIGNED NOT NULL,
#  `NombreUsuario` varchar(20) NOT NULL,
#   ApellidoUsuario` varchar(30) NOT NULL,
#  `CorreoUsuario` varchar(30) NOT NULL,
#  `ContrasenaUsuario` varchar(256) NOT NULL,
# 	usuario varchar (20) NOT NULL,
#  `FotoPerfil` varchar(40) DEFAULT NULL
#) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
#
#CREATE TABLE `posteo` (
#  `IdPost` bigint(20) UNSIGNED NOT NULL,
#  `IdUsuario` bigint(20) UNSIGNED DEFAULT NULL,
#  `TituloPost` varchar(500) NOT NULL,
#  `CuerpoPost` varchar(500) NOT NULL,
#  `FechaPosteo` timestamp NOT NULL DEFAULT current_timestamp() ON UPDATE current_timestamp()
#) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
