# IonicToDoApp

## Instrucciones de uso

Dasarrollado con [Ionic](http://ionicframework.com/).

## Compilación

### Prerequisitos
0. Instalar docker

    0. docker [Docker](https://www.docker.com)

    0. docker-machine [machine](https://docs.docker.com/machine/) and [install-virtualbox](https://www.virtualbox.org/wiki/Downloads) *optional in linux* 

    0. docker-compose [compose](https://docs.docker.com/compose/install/)

    0. Using [ionic-framework](https://hub.docker.com/r/agileek/ionic-framework/~/dockerfile/)

### Generacion de APK

```
$ docker-compose run --rm --service-ports app bash
$ ionic serve
$ ionic platform add android
$ ionic resources android
$ ionic build android
```

## Comandos utiles

        ionic start --list
        ionic start myapp tabs


Copiar archivo `./todo/platforms/android/build/outputs/apk/android-debug.apk` a un movil con Andrid


## Enlaces

0. Creator 

    [Creator](https://creator.ionic.io/)

0. Ionic

    [Introducción](https://www.youtube.com/watch?v=fMr8wQ3-mbQ&list=PL70Go5StQPB9_H4wHwP9VHsE-ybF4hErE&index=2)
    [TodoApp](https://www.youtube.com/watch?v=Vob4E8UnOOY&list=PL70Go5StQPB9_H4wHwP9VHsE-ybF4hErE&index=3)

0. Ionic 2

    [Introduccion](https://www.youtube.com/watch?v=KgKo0BwHG34&list=LLwLWeRd6pR6xdbHr2Zm9Csw)
