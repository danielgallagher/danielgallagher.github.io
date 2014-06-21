---
layout: page
permalink: /about/
title: About me
tagline: Minimal Mistakes, a Jekyll Theme
tags: [about, Jekyll, theme, responsive]
modified: 9-9-2014
comments: false
---


<p>More content to come. </p>
{% if site.owner.resume %}<a href="{{ site.owner.resume }}" class="author-social"><i class="fa fa-file"></i> Résumé / CV</a>{% endif %}{% if site.owner.twitter %}<a href="http://twitter.com/{{ site.owner.twitter }}" class="author-social" target="_blank"><i class="fa fa-twitter-square"></i> Twitter</a>{% endif %}{% if site.owner.facebook %}<a href="http://facebook.com/{{ site.owner.facebook }}" class="author-social" target="_blank"><i class="fa fa-facebook-square"></i> Facebook</a>{% endif %}
{% if site.owner.google_plus %}<a href="http://plus.google.com/+{{ site.owner.google_plus }}" class="author-social" target="_blank"><i class="fa fa-google-plus-square"></i> Google+</a>{% endif %}
{% if site.owner.linkedin %}<a href="http://linkedin.com/in/{{ site.owner.linkedin }}" class="author-social" target="_blank"><i class="fa fa-linkedin-square"></i> LinkedIn</a>{% endif %}
{% if site.owner.instagram %}<a href="http://instagram.com/{{ site.owner.instagram }}" class="author-social" target="_blank"><i class="fa fa-instagram"></i> Instagram</a>{% endif %}
{% if site.owner.tumblr %}<a href="http://{{ site.owner.tumblr }}.tumblr.com" class="author-social" target="_blank"><i class="fa fa-tumblr-square"></i> Tumblr</a>{% endif %}
{% if site.owner.github %}<a href="http://github.com/{{ site.owner.github }}" class="author-social" target="_blank"><i class="fa fa-github"></i> Github</a>{% endif %}
{% if site.owner.bitbucket %}<a href="http://bitbucket.org/{{ site.owner.bitbucket }}" class="author-social" target="_blank"><i class="fa fa-bitbucket"></i> Bitbucket</a>{% endif %}
{% if site.owner.stackoverflow %}<a href="http://stackoverflow.com/users/{{ site.owner.stackoverflow }}" class="author-social" target="_blank"><i class="fa fa-stack-overflow"></i> Stackoverflow</a>{% endif %}
{% if site.owner.lastfm %}<a href="http://lastfm.com/user/{{ site.owner.lastfm }}" class="author-social" target="_blank"><i class="fa fa-music"></i> Last.fm</a>{% endif %}
{% if site.owner.dribbble %}<a href="http://dribbble.com/{{ site.owner.dribbble }}" class="author-social" target="_blank"><i class="fa fa-dribbble"></i> Dribbble</a>{% endif %}
{% if site.owner.pinterest %}<a href="http://www.pinterest.com/{{ site.owner.pinterest }}" class="author-social" target="_blank"><i class="fa fa-pinterest"></i> Pinterest</a>{% endif %}
{% if site.owner.foursquare %}<a href="http://foursquare.com/{{ site.owner.foursquare }}" class="author-social" target="_blank"><i class="fa fa-foursquare"></i> Foursquare</a>{% endif %}
{% if site.owner.steam %}<a href="http://steamcommunity.com/id/{{ site.owner.steam }}" class="author-social" target="_blank"><i class="fa fa-steam-square"></i> Steam</a>{% endif %}
{% if site.owner.flickr %}<a href="http://www.flickr.com/photos/{{ site.owner.flickr }}" class="author-social" target="_blank"><i class="fa fa-flickr"></i> Flickr</a>{% endif %}
{% if site.owner.mailto %}<br/><a href="mailto:{{ site.owner.email }}" class="author-social" target="_blank"><i class="fa fa-envelope-square"></i>Email me</a>{% endif %}
{% if site.owner.pgp %}<a href="#" class="author-social" target="_blank"><i class="fa fa-lock"></i> PGP</a>{% endif %}