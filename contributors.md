---
layout: default
title: Colabores de la página
Description: Personas que colaboran con el proyecto
path: contributors
---

# Contribuidores

Las rutas son mejoradas e impulsadas por los contribuidores

### Ciberseguridad de Red

<div id="contributors" class="contributors-box">
	{% for item in site.data.netsec-contributors %}
	<div class="tooltip top">
		<a href="{{ item.link }}" target="_blank"><img src="{{ item.picture }}" /></a>
		<span class="tiptext">{{ item.name }}</span>
	</div>
	{% endfor %}
</div>

### Seguridad De La Información

<div id="contributors" class="contributors-box">
 {% for item in site.data.segurinfo-contributors %}
	<div class="tooltip top">
		<a href="{{ item.link }}" target="_blank"><img src="{{ item.picture }}" /></a>
		<span class="tiptext">{{ item.name }}</span>
	</div>
	{% endfor %} 
</div>
