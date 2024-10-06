---
title: El Equipo | Fedired Hub
description: Una lista de los miembros del equipo de Fedired y sus roles.
permalink: /team/
layout: default
---
# Conoce al Equipo

Es necesario mucho trabajo para mantener el funcionamiento de Fedired. Ya sea moderando informes, proporcionando consejos a los moderadores, creando y editando documentación, o simplemente manteniendo las luces encendidas y las ruedas girando.

Esta página lista todos los voluntarios increíbles que mantienen este barco en funcionamiento.


## Fundador / CEO / y Dueño de Fedired

Javier Caceres es el fundador, CEO y dueño de Fedired, una red social federada que prioriza la privacidad y seguridad de sus usuarios. Como autodidacta, ha adquirido habilidades en tecnología y seguridad en su tiempo libre, trabajando en proyectos que van desde la gestión de servidores hasta la supervisión de seguridad física. Su visión es crear un espacio digital inclusivo y seguro, ofreciendo también servicios tecnológicos a organizaciones sin fines de lucro. Su compromiso con la ética digital y el servicio comunitario posiciona a Fedired como un referente en el Fediverso.


{% for member in site.data.founders %}
<div class="team-banner">
    <p class="team-title"><a target="blank" href="{{ member.link }}">{{ member.name }}</a></p>
    <img class="team-avatar" src="{{ member.avatar }}" />
    <p><b>Rol:</b> {{ member.role }}</p>
    <p>{{ member.description }}</p>
  </div>
{% endfor %}

<div style="clear: both;"></div>
