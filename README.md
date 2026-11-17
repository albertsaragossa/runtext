# Runtext

*Escriu amb els peus: ruta GPX amb lletres per al rellotge.*

Web que genera un arxiu GPX amb una ruta que, vista en un mapa 2D, dibuixa el text que escriguis. La ruta s'ajusta a carrers i camins, de manera que es pot córrer o caminar de debò. Es pot importar a rellotges esportius com els Suunto.

## Com s'utilitza

1. Escriu el text (lletres A-Z i xifres 0-9, fins a 12 caràcters).
2. Indica els quilòmetres que vols fer.
3. Clica el mapa o cerca un lloc per triar el centre del dibuix. Pots arrossegar el marcador i girar el text amb la rotació.
4. Marca **Rotació automàtica** perquè l'aplicació triï l'orientació que millor encaixa amb els carrers (si no, fes servir la rotació manual). Amb **Troba millor ubicació** cerca el lloc més adequat dins del radi indicat al voltant del marcador.
5. Prem **Genera ruta**. L'aplicació ajusta la mida del text fins que la distància real s'acosta als quilòmetres demanats.
6. Prem **Baixa el GPX** i importa l'arxiu a l'app del rellotge (a Suunto, des de l'apartat de rutes).

## Publicació a GitHub Pages

Puja `index.html` i aquest `README.md` a un repositori i activa GitHub Pages a *Settings → Pages*. No cal cap servidor propi.

## Limitacions

- El dibuix queda deformat segons la xarxa de carrers de la zona: les ciutats amb quadrícula (com l'Eixample) funcionen millor que les zones amb pocs carrers.
- El desnivell acumulat i el temps (a 7:00, 6:00, 5:30 i 5:00 min/km) són estimacions orientatives. La distància final pot diferir lleugerament de la demanada (marge d'uns 8 %).
- Depèn de serveis públics gratuïts que poden tenir límits d'ús, pensats per a un ús personal.

## Crèdits tècnics

- Mapa: [OpenStreetMap](https://www.openstreetmap.org/copyright) i [Leaflet](https://leafletjs.com/).
- Rutes a peu: servidor OSRM de [FOSSGIS](https://routing.openstreetmap.de/).
- Desnivell: [Open-Meteo](https://open-meteo.com/) (dades d'elevació aproximades).
- Cerca de llocs: [Nominatim](https://nominatim.org/).

## Autoria

Albert Saragossa Alòs
