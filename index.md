---
title: Instruções para o exercício
permalink: index.html
layout: home
---

# Exercícios do GitHub Copilot

Os exercícios de início rápido a seguir foram criados para fornecer uma experiência de aprendizado prático na qual você explorará os recursos do GitHub Copilot. Cada exercício inclui um conjunto de tarefas que você pode concluir em seu ambiente de laboratório.

## Exercícios de início rápido
<hr>

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}

{% for activity in labs  %}

### [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }})
{{ activity.lab.description }}
<hr>
{% endfor %}
