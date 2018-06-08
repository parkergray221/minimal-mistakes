# About

Hello! Welcome to my website! I'm a 23 year old computer scientist eager to land my first job in the industry. My contact information is in the sidebar.

# Projects 

{% for item in site._projects %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}