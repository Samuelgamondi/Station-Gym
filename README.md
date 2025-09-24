Station-Gym

Integrantes:

Samuel Gamondi (samuelgamondi01@gmail.com).
Facundo Uriel Rivarola (rivarolauriel2002@gmail.com).

Tematica:

El proyecto va a ser una pagina de gimnasio donde las principales funcionalidades que se busca es:
1.Regristro y login de usuarios.
2.Reserva de horarios para entrenar.
3.Gestion de publicaciones informativas, control interno de reservas y usuarios por parte del admin.

La relaciones entre tablas serian:

Usuario es la tabla base (cliente + admin) el cual se relaciona con reserva ya que un usuario puede tener muchas reservas,
Horario definne los turnos disponibles y un horario puede estar reservado por muchos usuarios,
Reserva conecta usuarios con horarios,
y Publicacion guarda novedades creadas por el administrador.


![DER](https://github.com/user-attachments/assets/7daf37a0-6e00-4f4f-955e-4e3ceea38910)


[db_station_gym.sql](https://github.com/user-attachments/files/22516083/db_station_gym.sql)
