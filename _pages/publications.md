---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- 
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
* means equal contribution

{% include base_path %}
-->

<!-- New style rendering if publication categories are defined -->
<!--
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
-->


<style>
    .blue-quote {
        border-left: 4px solid #ffb563; /* Orange border */
        background-color: #f8f9fa; /* Light grey background */
        color: #333; /* Dark grey text color */
        padding: 10px 10px;
        margin: 10px;
        font-style: normal;
    }
  
  .green-quote {
        border-left: 4px solid #9cc5a1; /* Orange border */
        background-color: #f8f9fa; /* Light grey background */
        color: #333; /* Dark grey text color */
        padding: 10px 10px;
        margin: 10px;
      font-style: normal;
    }
</style>



