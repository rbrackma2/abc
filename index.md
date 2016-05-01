---
layout: home
permalink: /
image:
  feature: lawyer-image-1345x594.jpg
---

<div class="tiles">

<div class="tile">
  <h2 class="post-title">Cabinet</h2>
  <p class="post-excerpt">On est ...</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Nos specialites</h2>
  <p class="post-excerpt">Compatible with popular libraries like <a href="http://bourbon.io">Bourbon</a>, <a href="http://neat.bourbon.io/">Neat</a>, and <a href="http://github.com/octopress/octopress">Octopress</a> to help build and deploy your site with ease.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Contact</h2>
  <p>T&eacute;l. mob. : <a href="tel:+33763501488">07 63 50 14 88</a></p>
  <p>E-mail : <a href="mail:avocat@brackmann.fr">avocat@brackmann.fr</a></p>
  
  <img src="http://maps.googleapis.com/maps/api/staticmap?{% for location in page.locations %}{% if forloop.first %}center={{location}}&markers=color:blue%7C{{location}}{% else %}&markers=color:blue%7C{{location}}{% endif %}{% endfor %}&zoom={% if page.zoom %}{{page.zoom}}{% else %}13{% endif %}&size=300x200&scale=2&sensor=false&visual_refresh=true" alt="">
  
</div><!-- /.tile -->


</div><!-- /.tiles -->
