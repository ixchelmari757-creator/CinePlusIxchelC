# CinePlusIxchelC
Aplicación básica de cobro para un cine creada en python con wxglade. Costa de 4 ventanas: inicio de sesión, taquilla, dulcería y ticket.

Ventana Inicio de Sesión(Login)
--El sistema debe de tener una pantalla de inicio de sesión.
--Para este proyecto, el inicio de sesión se hará con datos preestablecidos (por ejemplo, usuario: Ixchel y contraseña: 123). No es necesario implementar una base de datos.

Ventana Venta de Boletos(Taquilla)
--El sistema debe permitir al empleado seleccionar la película, el horario y la sala.
"IT" 14:00, 17:00, 20:00 Sala 1.
"La hermanastra malvada" 13:30, 16:30, 19:30 Sala 2.
"Superman" 15:00, 18:00, 21:00 Sala 3.
--Se debe de especificar la cantidad de boletos.
--Se debe indicar si los boletos son para adultos o para menores de edad, ya que el precio es diferente(Adultos $80, Menores de edad $70).
--Al finalizar la selección de boletos, el sistema debe de mostrar un resumen de los boletos adquiridos y calcular el subtotal de la taquilla.

Ventana Venta de Productos(Dulcería)
--Despues de la taquilla, el sistema debe preguntar si el cliente desea comprara productos de la dulcería.
--Si la respuesta es afirmativa, el sistema debe de llevar al empleado a una nueva pantalla.
--En esta pantalla, se debe mostrar tres combos preestablecidos:
"Básico" $75, Palomitas chicas + Refresco chico, imagen alusiva.
"Cuates" $130, Palomitas medianas + 2 Refrescos medianos, imagen alusiva..
"Familiar" $200, Palomitas Grandes + 2 Refrescos grandes + 1 Dulce, imagen alusiva. 
--Por cada combo, el sistema debe de mostrar el precio, el contenido y una imagen alusiva.
--También se debe permitir la venta de producctos:
Palomitas: Tamaño chico $30, mediano $50 y grande $70.
Refresco: Sabores Cola, Sprite, Manzana, en tamaño chico $25, mediano $40 y grande $60.
El empleado debe poder indicar la cantidad de cada combo o producto individual.

Ventana Resumen de Compra y Cobro(Ticket)
--Al finalizar la selección de productos de dulcería, el sistema debe mostrar una ventana de resumen.
--Esta ventana debe incluir un desglose de compra:
sección "Taquilla" con los boletos comprados y su subtotal.
sección "Dulcería" con los combos y productos individuales, y su subtotal.
--Finalmente, el sistema debe de mostrar el costo total de toda la compra (taquilla + dulcería). 
