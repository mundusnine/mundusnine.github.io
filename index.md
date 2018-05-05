---
title: Home
layout: default
excerpt: "Home of the colorfull gamedev's"
---

<div class="bg" style="background-image: url({{'/assets/website_homepage.png' | prepend: site.baseurl }})" >
    <div class="container content typeset" style="text-align: center; position: relative; top:20%; height:10rem;">
        {% if site.logo %}{% include site-logo.html max-width="10rem" %}{% endif %}
    </div>
    <div class="flex-container-row" style=" position: relative; top: 30%;">
        <div class="box-left">
            {% include button-image.html link="/works/daemonvsdemon" position="center" width="400" height="600" text="Daemon vs Demon" image="/assets/initial_kill_w_title_2_small.gif"  %}
        </div>
        <div class="box-right" >
            {% include button-image.html link="/services/" image="/assets/services.png" position="center" width="400" height="600"  text="Services"%}
        </div>
    </div>
    {% include home-header.html %}
</div>






