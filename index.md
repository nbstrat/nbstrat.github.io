---
layout: default
---
 # index md file

    {% for repo in site.github.public_repositories limit:28 %}
         {% if repo.fork != true %}
                 [fred was here  {{ repo.homepage }}{{ repo.name }} ] 
        {% endif %}
    {% endfor %}
