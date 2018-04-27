# MQTT 4 Autolib

Flow Node-Red pour Streamer l'api Autolib Paris.
Vous avez besoin d'un broker MQTT [Mosquitto](https://mosquitto.org/) or [Artemis](https://activemq.apache.org/artemis/)

## Build

```
npm install
```

## Configuration

Variable d'environment :

```
export BROKER_HOSTNAME=broker
export AUTOLIB_STATION=boulognebillancourt-henrimartin-2,paris-portesaintcloud-parking,boulognebillancourt-reine-12,paris-poteau-40,joinvillelepont-8mai1945-1
```

La liste des id des stations est [disponibilite sur le site API Paris](https://opendata.paris.fr/explore/dataset/autolib-disponibilite-temps-reel/)

## Run

```
npm start
```
