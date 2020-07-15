---
layout: page
title: Über uns
---

Diese Ideensammlung entsteht durch und für die Community der deutschsprachigen Java User Groups, welche im [iJUG e. V.]({{ site.ijug.web }}) organisiert ist. Der iJUG ist Mitveranstalter der [JavaLand]({{ site.javaland.web }}) und viele der Mitgliedsgruppen führen weitere Konferenzen und unzählige Veranstaltungen durch.

Feedback und Diskussionen bitte im [#javaland]({{ site.slack.javaland }}) Kanal des Slacks jvm-german ([kostenlos registrieren]({{ site.slack.register }})).

## Wer steht dahinter?

{% for author in site.author %}
###  {{ author.name }} {% if author.twitter %}([@{{ author.twitter }}](https://twitter.com/{{ author.twitter }})){% endif %}
<img src="/public/images/{{author.image}}.png" class="pic" />
{% endfor %}



## Weitere Beitragende

Vielen Dank für das Einbringen von Ideen, das Bereitstellen von Texten und das Korrekturlesen.

{% for author in site.contributor %}
###  {{ author.name }} {% if author.twitter %}([@{{ author.twitter }}](https://twitter.com/{{ author.twitter }})){% endif %}
<img src="/public/images/{{author.image}}.png" class="pic" />
{% endfor %}
