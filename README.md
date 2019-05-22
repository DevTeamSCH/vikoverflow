# VikOverflow

## Dependencies
* Docker (for Windows / MAC)


You have to create a volume, where the database data will be stored (the name has to be vikoverflow-data).
```
docker volume create --name vikoverflow-data
```

## Run
```
docker-compose up
```
This will build the images, if you run it for the first time. You can rebuild the image(s) if needed with `docker-compose build`.

API can be accessed at http://localhost:8000

App can be viewed at http://localhost:3000


## Devs
|Name|Nickname|Role|Contact|
|---|-------|-------|-----------|
|Gál Dániel|Den|project leader|[@daendev](https://github.com/daendev)|
|Márki-Zay Ferenc|Feri|developer|[@ferencmarkizay](https://github.com/ferencmarkizay)|
|Chif Gergő|Chif|frontend leader|[@chifgeri](https://github.com/chifgeri)|
|Orova Márton|Marci|developer|[@martonorova](https://github.com/martonorova)
|Prehoda Balázs|Balázs|developer|[@balazsprehoda](https://github.com/balazsprehoda)|
|Bodor Máté|Bodor|developer|[@bmate771](https://github.com/bmate711)|
|Czémán Barnabás|Cémi|developer|[@barni2000](https://github.com/barni2000)|

## Tech
* [Django](https://www.djangoproject.com/)
* [Django REST framework](http://www.django-rest-framework.org/)
* [React](https://reactjs.org/)
* [Redux](https://redux.js.org/)
* [Docker](https://www.docker.com/)
