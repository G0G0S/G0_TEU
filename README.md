# G0_TEU

Script Todo En Uno desarrollado por G0G0S.

Este Script incluye las siguientes funcionalidades:

+ 1- Blips. (Leer mas abajo)
+ 2- Los NPC no atacan y pasan de todo.
+ 3- Anti-Spawn de algunos vehiculos. (Leer mas abajo)
+ 4- Poder apagar todas las luces artificiales de la ciudad. (Leer mas abajo)
+ 5- Zonas seguras. (Leer mas abajo)
+ 6- Spawn de NPC para venta de drogas y mercado negro. (Leer mas abajo)
+ 7- Control del vehiculo en el aire desabilitado.
+ 8- Ningun NPC suelta armas.
+ 9- Ningun vehiculo suelta armas.
+ 10- Daño con armas CAC reducido.
+ 11- Disparar conduciendo desabilitado.
+ 12- Sistema "Forzar". (Leer mas abajo)
+ 13- Animaciones de levantar y cruzar los brazos.
+ 14- Regeneracion de vida desabilitada.
+ 15- Servicios de emergencias base desabilitadas.
+ 16- Opciones del Menu de Pausa personalizadas. (Leer mas abajo)
+ 17- Todo vehiculo policial corre mas.
+ 18- Sistema de retroceso real en todas las armas de fuego.
+ 19- Control de poblacion y spawn de vehiculos aleatorios. (Leer mas abajo)
+ 20- Supresion de ruidos de ambiente.
+ 21- Limite de velocidad de cualquier entidad a 280km/h.
+ 22- Codigo necesario para el funcionamiento del Sistema de Codigos Regalo. (Leer mas abajo)
+ 23- Codigo necesario para el funcionamiento del Sistema de Logeo de todo tipo de comandos usados. (Leer mas abajo)
+ 24- Sistema de Whitelist. (Leer mas abajo)

## Descarga & Instalacion

### Usando [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx /G0G0S/G0_TEU
```

### Usando Git
```
cd resources
git clone https://github.com/G0G0S/G0_TEU
```

## Instalacion
- Añade esto a tu `server.cfg`:

```
start G0_TEU
```

**INFORMACION SOBRE ALGUNAS FUNCIONES ANTES MENCIONADAS**

1- Blips.
+ Esta funcionalidad basicamente agrega los siguientes Blips al mapa con sus respectivas cordenadas.
+ Prision x=1807.53, y=2605.59, z=45.565
+ Aeropuerto x=1721.0, y=3255.07, z=41.148
+ Aeropuerto x=2149.59, y=4817.6, z=41.268
+ Aeropuerto x=-1045.49, y=-2751.304, z=21.363
+ Comisaría de Policía x=-445.202, y=6014.36, z=31.7164
+ Comisaría de Policía x=1854.21, y=3685.51, z=34.2671
+ Hospital x=337.238, y=-1396.28, z=32.5092
+ Hospital x=1839.74, y=3672.0, z=34.2767
+ Hospital x=-243.463, y=6327.87, z=32.4262
+ Circuito x=1131.91, y=101.72, z=83.023
+ Casino x=930.71, y=41.14, z=78.513
+ Puticlub x=129.246, y=-1299.363, z=29.501
+ TequiLaLa x=-565.1, y=276.4, z=83.1
+ Bahama Mamas x=-1387.4, y=-588.6, z=30.3
+ Pearl's Seafood x=-1816.5, y=-1193.6, z=14.3
+ Galaxy Nightclub x=355.86, y=304.61, z=103.74
+ Yellow Jack Inn x=1991.06, y=3054.49, z=47.21
+ IKEA x=2747.34, y=3484.89, z=54.671

3- Anti-Spawn de algunos vehiculos.
+ Esta funcionalidad bloquea al 100% el Spawn o Generacion Aleatoria de los siguientes modelos.
+ annihilator
+ buzzard
+ buzzard2
+ cargobob
+ cargobob2
+ cargobob3
+ cargobob4
+ frogger
+ frogger2
+ maverick
+ savage
+ skylift
+ supervolito
+ supervolito2
+ swift
+ swift2
+ valkyrie
+ valkyrie2
+ volatus
+ blimp
+ blimp2
+ blimp3

4- Poder apagar todas las luces artificiales de la ciudad.
+ Esta funcionalidad se usa con el comando /luces, la cual apaga completamente todas las luces artificiales de la ciudad.

5- Zonas seguras.
+ Esta funcionalidad agrega las siguientes zonas seguras en las cuales no podras sacar armas, usar CAC ni dañar desde fuera a ningun jugador que este dentro de la zona segura.
+ x=-269.59, y=-954.94, z=30.22
+ x= 229.27, y=-775.66, z=29.74
+ x= 323.30, y=-594.32, z=42.28
+ x= -39.48, y=-1095.00, z=27.42
+ x= 241.12, y=-1378.97, z=29.50

6- Spawn de NPC para venta de drogas y mercado negro.
+ Esta funcionalidad hace Spawn de Peds como compradores de droga especializados en las siguientes zonas.
+ **Esta funcion debe de ir acompañada del script modificado por G0G0S "esx_illegal".**
+ x=277.70, y=2205.52, z=130.40
+ x=1928.55, y=-3087.33, z=-6.00
+ x=-582.33, y=-1611.24, z=26.01

12- Sistema "Forzar".
+ Esta funcionalidad agrega el Sistema de Forzar que todo el mundo conoce, simplemente usando el comando /forzar, esta integrado con el servicios de emergencias.
+ **Esta funcion debe de ir acompañada del script modificado por G0G0S "Emergency".**

16- Opciones del Menu de Pausa personalizadas.
+ Esta funcionalidad agrega al Menu de Pausa textos personalizados a las opciones que hay en el.

19- Control de poblacion y spawn de vehiculos aleatorios.
+ Esta funcionalidad te permite modificar la cantidad de Peds y Vehiculos que se generan por la calle, como el trafico de los mismos, ademas de controlar la cantidad Policias, Medicos, Taxistas y Basureros aleatorios que aparecen.
+ Tambien arregla fallos como los globos que caen del cielo.

22- Codigo necesario para el funcionamiento del Sistema de Codigos Regalo.
+ Esta funcionalidad agrega un Sistema automatizado/manual de generacion de codigos regalo, los cuales pueden contener Items o Dinero, Dinero Negro o Saldo Bancario y ademas son enviados directamente a Discord gracias a una integracion.
+ Los Codigos pueden ser generados desde Consola o Comandos dentro del juego.
+ **Esta funcion debe de ir acompañada del script modificado por G0G0S "Kyk-RedeemCodes".**

23- Codigo necesario para el funcionamiento del Sistema de Logeo de todo tipo de comandos usados.
+ Esta funcionalidad es un Sistema de LOG Completo de **CUALQUIER COMANDO** que se ejecute en el servidor, los comandos que usen cualquier tipo de rango como Admin o Usuario seran enviados directamente a Discord gracias a una integracion.
+ Notifica que comando a usado y quien hizo uso de el.
+ **Esta funcion debe de ir acompañada del siguiente fragmento de codigo, el cual debera ser implementado en cada "RegisterCommand" de tu servidor.**
```
RegisterCommand() --Para este tipo lo siguiente:

    local nombreJugador = GetPlayerName(source)
    TriggerEvent('G0_discord:comando',nombreJugador .. " A usado /comando ")
	
ESX.RegisterCommand() --Para este tipo lo siguiente:

	local idJugador = xPlayer.source
	local nombreJugador = GetPlayerName(idJugador)
    TriggerEvent('G0_discord:comando',nombreJugador .. " A usado /comando ")
```

24- Sistema de Whitelist.
+ Esta funcionalidad es un Sistema de Whitelist con opcion de Solo "Contraseña", Solo "Identificador" o "Contraseña + Identificador". Incluye los siguientes "Idetificadores":
+ Steam ID
+ Licencia FiveM
+ Xbox ID
+ Microsoft Live ID
+ Discord ID
+ IP


# ESTE SCRIPT ESTA ENCRIPTADO PARA EVITAR SU DISTRIBUCION SIN MI CONSENTIMIENTO

+ **CUALQUIER BUG O REPORTE HAGANLO EN SU CORRECTA FORMA A TRAVES DE GITHUB.**
+ **CUALQUIERA QUE QUIERA HACER USO DEL SCRIPT ESTA EN SU DERECHO, COMO EL MIO EN COMPARTIRLO CON TODOS USTEDES, CLARO ESTA QUE EN ESTE CASO ESTA PERSONALIZADO A MI GUSTO COMO POR EJEMPLO LOS BLIPS, TEXTOS Y CORDENADAS**
+ **CUALQUIERA QUE QUIERA UNA VERSION PERSONALIZADA PARA EL O INCLUSO LA VERSION LIBRE 100% DE ESTE SCRIPT, QUE SE PONGA EN CONTACTO CONMIGO EN DISCORD: "G0G0S#6778"**
