---
layout: page
title: FAQ
permalink: /faq/
---

Recuerda no colocar los símbolos `<` y `>`, son para indicar que ahí debes reemplazar con lo que se indica.

* **¿Cómo cambiar el prefijo?** Por defecto es `!`, y se puede cambiar 
    con `@AlexisBot prefix /` si es que quieres usar `/comandos` así.
* **¿Cómo activo el starboard?** Tiene varias opciones, pero lo para partir, utiliza 
    `!starboard channel #canal` para definir el canal donde llegarán los mensajes, y con
    `!starboard count 10` para que los mensajes con 10 o más reacciones de un mismo
    emoji aparezcan en el starboard.
* **¿Cómo activo los mensajes de bienvenida y despedida?** Prueba con `!welcome` y `!goodbye`.
* **¿Cómo banear y kickear miembros?** Con `!realban @usuario/id <motivo de ban>` 
    y `!kick @usuario/id <motivo de kick>`. Si es posible, se le enviará a la persona
    un mensaje con el motivo de expulsión. Recuerda que el bot debe tener permisos para ban y kick.</li>
* **¿Cómo mutear gente?** El mute sólo le asigna un rol a los usuarios, ya sea hasta que se
    muteen temporalmente, o hasta desmutear temporalmente. Primero, crea un rol, por ejemplo "Muted", y
    luego asegúrate de que el bot podrá asignarlo. Luego, usa el comando `!mutedrole Muted`
    para definir que ese rol se utilizará para mutear gente. Ese rol deberá evitar que los users a
    mutear puedan hablar en los canales que quieras que tome efecto el mute. Por último, con
    `!mute <@user/id> 10m` para mutear a alguien por 10 minutos. Por supuesto, puedes
    utilizar otros tiempos como 1h, 2h30m, 30s, y así. Puedes no asignar un tiempo, para después desmutear
    a la persona con `!unmute <@user/id>`.
