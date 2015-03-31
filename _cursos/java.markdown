---
layout: post
title:  "Introduccion a Java con Eclipse"
date:   2015-03-31 12:48:45
description: Curso Sobre Introducción a Java. En este curso, podrá ver una introducción al lenguaje de programación Java usando el entorno de Desarrollo Eclipse.
categories:
- blog
---
<div id="home" class="page-content wc-container">
	<p class="texto">Curso Sobre Introducción a Java. En este curso, podrá ver una introducción al lenguaje de programación Java usando el entorno de Desarrollo Eclipse.</p>
	<p class="texto">Este curso no requiere de ningún conocimiento prévio de programación Orientada a Objetos pero si es recomendable tener unas pequeñas nociones de programación estructurada.</p>
	<p class="texto">Con respecto al software a utilizar, vamos a usar la versión 1.7 del JDK de Java y el entorno Eclipse Kepler.</p>
	<div class="posts">
		<h3>Índice del Curso:</h3>
  		{% for java in site.java limit:10 %}
  			<div class="post">
    			<h3 class="post-title">
			      <a href="{{ java.url | prepend: site.baseurl | prepend: site.url }}">
			        {{ java.title }}
			      </a>
    			</h3>

    			<span class="post-date">{{ java.date | date_to_string }}</span>    			
  				<p>
	  				{{ java.description }}	
  				</p>
  				<p>
  					<a href="{{ java.url | prepend: site.baseurl | prepend: site.url }}" title="{{ java.title}}">
  						Ver Lección
					</a>
  				</p>
  			</div>
  		{% endfor %}