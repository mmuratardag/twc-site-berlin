<style>h1, .main-wrapper h2, h3 {text-align: left; font-weight: bold;}</style>
# {% t home.title %}
{% t home.summary %}

## {% t home.events.title %}
{% t home.events.summary %}
{% include events.html limit=4%}

## {% t home.connect.title %}
{% t home.connect.links %}

## {% t global.accessibility.title %}
{% t global.accessibility.summary %}

## {% t global.code_of_conduct.title %}
{% t global.code_of_conduct.summary %}