---
layout: post
title:  "Por qué participar en Programas de Bug Bounty?"
date:   2024-01-04 10:36:52 -0300
categories: opinion
---
La pregunta salía a escena en medio de una amena conversación de almuerzo. Álvaro, mi colega, que recién daba sus primeros pasos en el mundo del hacking ético, parecía sorprendido por mi respuesta: `Es una forma de tener experiencia real,
sin horarios laborales ni problemas legales`. Existen obviamente más razones que expondremos a continuación, espero que pueda servir a más de alguno que está pensando en convertirse en bounty hunter, hacker ético, pentester o security researcher.

Chile un par de décadas atrás era, sin lugar a dudas un país distinto. La sociedad no tenía instagram ni twitter o facebook, tener una conexión a internet realmente era un privilegio. Las compañías comenzaban lentamente a tener presencia en la web, consideremos que el `dominio .cl` había sido creado recién en 1997. Pasaron los años y la tecnología (como siempre) fue aumentando su crecimiento y complejidad cada vez más rápido. Las páginas web ya no eran sólo código html, ahora tenían javascript para darles funcionalidades, conexión a base de datos, aparecían frameworks especializados. Así comenzaban a aparecer vulnerabilidades, dado el poco conocimiento en desarrollo seguro de aplicaciones.

Y es que antes ni siquiera existían libros sobre seguridad informática, ni sitios web donde ejercitar el conocimiento. Tenías que preguntarle al `más computín de la clase` para que te explicara lo que era un troyano o lo que era el phishing. El hacking era visto como un arte oculto, que en general se asociaba a cibercriminales o alguna película de hollywood.

El concepto de bug bounty, léase como: `premios por encontrar fallas de seguridad informática`, no era conocido, si un investigador descubría alguna vulnerabilidad en un sitio web tenía que arriesgarse: contactar a la empresa e informar podría significar represalias legales o de otro tipo. Quizá lo mejor era reportarlo de manera anónima, para esperar que los desarrolladores parcharan el bug en un tiempo razonable. A veces sucedía, a veces `no`.

Las cosas han cambiado bastante, la comunidad de infosec es totalmente abierta. Existen los CTFs (capture the flag) que son en palabras simples `las olimpiadas
del hacking`, existe mucha literatura especializada, canales de youtube, congresos anuales e incluso cursos formales y cerficaciones. La realidad de ese investigador que encuentra vulnerabilidades en algún sitio web también es otra, hay `bug bounties`: Ahora las empresas crean programas, premiando a quienes reportan vulnerabilidades válidas a cambio de incentivos monetarios, swags (regalos) u otro tipo de recompensa, sin represalias legales: está permitido hackear siempre y cuando se cumpla con todas las reglas establecidas.

Y volvemos a la conversa del almuerzo junto a Álvaro. Comencé a explicarle por qué era buena idea esto del bug bounty: Si bien en las plataformas como [Hackthebox][hackthebox] o [TryHackme][tryhackme], puedes entrenar y aprender
sobre hacking, éstos entornos siempre son vulnerables. En la realidad no es así, nadie asegura que existan vulnerabilidades en los sistemas que estás auditando, por lo que se debe investigar con la mayor meticulosidad posible. Una de las principales diferencias entre los laboratorios y los entornos reales. No existen writeups o guías con soluciones (porque quizá no existe la vulnerabilidad)

Lo que hace evidente el siguiente punto: adquieres `experiencia real`. Incluso si
no encuentras vulnerabilidades en un comienzo, estás auditando un sistema real
que generalmente está en producción. Para alguien que quiere ser contratado como pentester junior, esto puede servir en una eventual entrevista de trabajo : qué tecnologías observaste? qué herramientas utilizaste? qué metodología ? has encontrado una vulnerabilidad por tu cuenta?

Otra razón para participar es tener la oportunidad de `proteger internet` y la infraestructura de las empresas. Compañías que quizá comparten nuestros valores. Alguna empresa o institución que admires? Ésta es una forma de ayudarles.

Y hablando de swags o bounties: Los regalos de agradecimientos van desde poleras hasta dinero. Existe la posibilidad de ganar dinero haciendo bug bounties o simplemente ser premiado de alguna forma por la labor cumplida. Aquí es importante entender las `razones personales` por las cuales se participa, pero sin lugar a dudas el dinero y las regalías pueden ser un muy buen incentivo para un gran número de investigadores.

Existen además programas VDP (Vulnerability Disclosure Programs) los cuales no ofrecen dinero, pero con ellos es posible mejorar la reputación
y ser invitado a programas exclusivos que si poseen bounties.

`Para finalizar:` si estás comenzando, no te apresures. Participa en los bounties con la idea de aprender y de profundizar tus conocimientos mientras ayudas
a las empresas con los bugs que puedan aparecer. A medida que vayas adquiriendo experiencia, irás teniendo más hallazgos válidos.

Lugares idóneo para comenzar tu aventura en el bug bounty: [Open Bug Bounty][open], [HackerOne][hackerone], [Bugcrowd][bugcrowd], [Intigrity][intigriti].

Dato adicional: busca programas no tan conocidos usando el google dork `inurl:"security policy"`.

¿Álvaro habrá entrado a algún programa? De seguro que sí.

[open]: https://www.openbugbounty.org/
[hackerone]: https://www.hackerone.com/
[bugcrowd]: https://www.bugcrowd.com/
[intigriti]: https://www.intigriti.com/
[hackthebox]: https://www.hackthebox.com/
[tryhackme]: https://tryhackme.com/
