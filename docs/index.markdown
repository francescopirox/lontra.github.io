---
layout: home
title: Lontre
permalink: /
---
<div id="home">
  <h1>Blog Posts</h1>
  <h2> Un sito LONTROGRAFICO <h2>
  <img src="https://www.acquariodicattolica.it/data/thumb_cache/_data_pagine_img_904_jpg_cr_767_500.jpg">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/02/Sea_Otter_%28Enhydra_lutris%29_%2825169790524%29_crop.jpg/800px-Sea_Otter_%28Enhydra_lutris%29_%2825169790524%29_crop.jpg"> 
  <img src="https://media.istockphoto.com/id/823913136/it/foto/lontra-europea-lutra-lutra-6-anni-ritratto-in-piedi-su-sfondo-bianco.jpg?s=612x612&w=0&k=20&c=ZFw1ct4mrbcmRhG2tasu9sqqiFy-60wEk4o6CWaEF6c="> 
  <img src="https://c8.alamy.com/compit/cxjhjk/american-lontra-di-fiume-in-piedi-lutra-canadensis-cxjhjk.jpg">   
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <form action="">
  <button type="submit">
    Visita Mr. Webmaster
  </button>  
  </form>
