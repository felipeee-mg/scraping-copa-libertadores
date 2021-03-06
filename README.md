## Web scraping de los equipos participantes de la Copa Conmebol Libertadores entre los a帽os 2010 y 2020馃弳

Programa de web scraping realizado en Python que obtiene desde la p谩gina web [transfermarkt.es](https://www.transfermarkt.es/copa-libertadores/teilnehmer/pokalwettbewerb/CLI/saison_id/2021) datos sobre los clubes de futbol participantes de la Copa Conmebol Libertadores entre las ediciones de los a帽os 2010 y 2020. Lo anterior con el objetivo de generar un dataset en formato CSV para su uso en un proyecto de t铆tulo馃帗.


### Datos extra铆dos馃捇

Los datos extra铆dos para cada equipo en cada edici贸n del torneo son los siguientes:
* __Nombre del Equipo__, indica el nombre oficial del equipo de f煤tbol.
* __A帽o de su participaci贸n__, indica la edici贸n de la competici贸n en la cual el equipo particip贸.
* __Pa铆s__, indicia el pa铆s al cual pertenece el equipo de f煤tbol.
* __Valor de mercado__, representa la suma total de la valorizaci贸n en millones de euros de los jugadores de su plantilla en el a帽o en que el equipo particip贸 de la competici贸n.
* __Promedio del valor de mercado__, representa el promedio en millones de euros del valor de mercado del equipo el a帽o en el que particip贸 de la competici贸n.
* __Promedio de edad__, representa el promedio de edad de todos los jugadores de la plantilla del equipo el a帽o en que particip贸 de la competici贸n.
* __Cantidad de jugadores en la plantilla__, representa la cantidad de jugadores inscritos por el equipo para la temporada.
* __Cantidad de jugadores extranjeros__, representa la cantidad de jugadores extranjeros inscritos por el equipo para la temporada.


### Librerias utilizadas馃摎

* BeautifulSoup4.
* Requests.
* pandas.
