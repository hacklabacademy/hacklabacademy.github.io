---
layout: post
title:  "Introduccion Arduino"
date:   2014-07-28 22:48:45
description: Curso Sobre Introducción a Arduino.
---
<div id="home" class="page-content wc-container">
	<div class="posts">
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
  						Read More
					</a>
  				</p>
  			</div>
  		{% endfor %}