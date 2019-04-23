---
title: "Alias de consola?"
subtitle: "Mejorá el flujo de trabajo utilizando este pequeño truco"
thumbnail: ""
youtube: ""
tags: ["tip", "bash", "zsh"]
published: true
---

Hoy durante mi sesión de cafe matutino y twitter, encontré un articulo escrito por [Robert Cooper](https://dev.to/robertcoopercode) en [dev.to](https://dev.to/robertcoopercode) que me pareció muy interesante para compartir.

Que son? Para que sirven? Bueno, empecemos de a poco.

Los alias son comandos personalizados que podemos utilizar en la terminal simplemente agregando unas pocas lineas a nuestro archivo de configuración _(.bashrc)_

**Linux** y **MacOS** no tendrían este problema ya que por defecto utilizan bash, aunque recomiendo utilicen [Oh my zsh!](https://ohmyz.sh/) como shell. En cambio para usuarios de **Windows** necesitarían bajar una consola como [Cmder](https://cmder.net/) que soporta bash.

Para poder crear nuestros propios alias necesitamos modificar el archivo de configuración. En **Linux** y **MacOS** lo van a poder encontrar en el home de su usuario (_cd ~/.bashrc_).

![alt text](https://i.imgur.com/Ghb3OTwl.png "Config file")

> Si utilizan **Cmder** en Windows, puede agregar un alias simplemente con el siguiente comando directo en consola.
>
> ```bash
> alias 'projects="cd ~/Documents/projects"'
> ```

Como se puede ver en la imagen, al comando **_cd ~/Documents/projects_** le asigno el alias **_projects_**. Esto me ayuda a que sin importar en la ruta que yo este parado pueda escribir el comando **_projects_** y me va a llevar directamente al destino asignado. Este ejemplo hace un simple _change directory_ pero se puede utilizar para agilizar los comandos de _Git_.

El shell que yo utilizo viene, por defecto, con algunos alias ya asignados.

![alt text](https://i.imgur.com/cpwoQl8l.png "Oh my szh! Default Aliases")

Podemos utilizar **_gaa_** para ejecutar un **_git add --all_** o **_gst_** para ejecutar un **_git status_** y poder ver que archivos se modificaron, cuales están en staging y cuales están pendientes de agregar.

Les dejo el link de la [publicación original](https://dev.to/robertcoopercode/using-aliases-to-speed-up-your-git-workflow-2f5a) para quien quiera leerlo.

Espero les sirva este pequeño tip y nos leemos la proxima!
