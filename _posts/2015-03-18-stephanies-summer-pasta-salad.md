---
layout: post
category: recipe

# The following properties are utilized by the rich-snippet partial.
# Feel free to use them in the body of the post to prevent repitition.

title: "Stephanie's Summer Pasta Salad"
description: "A light pasta salad sure to spice up any summer cookout."

image:
  url: "/assets/img/stephanie.jpg"
  alt: "Stephanie's Summer Pasta Salad"

ingredients:
  - "1/2 lb pasta"
  - "1/3 bell pepper, diced"
  - "1/3 white onion, diced"
  - "5 strips bacon, cooked & diced"
  - "6 jalepenos, pickled & diced"
  - "1/3 cup mayo"
  - "2 tbsp brown mustard"
  - "1 tsp apple cider vinegar"
  - "1 tsp olive oil"
  - "2 tsp sugar"
  - "Salt and pepper to taste"

instructions: 
  - "Boil pasta in salded water until fully cooked. Drain and rinse in cold running water until chilled."
  - "In a large mixing bowl, add onion, bell pepper, bacon, jalepenos, and cooked pasta."
  - "In a small bowl, combine mayo, brown mustard, apple cider vinegar, olive oil, sugar, salt, and pepper."
  - "Add dressing to the pasta mixture a little at a time until dressed to your liking."

yield: "Serves 4"

time:
  prep: "10min"
  total: "10min"
---

{{ page.description }}

### Ingredients
{% for item in page.ingredients %}
  - {{ item }}
{% endfor %}

### Instructions
{% for item in page.instructions %}
  - {{ item }}
{% endfor %}

{{ page.yield }}

Prep time: {{ page.time.prep }}
Total time: {{ page.time.total }}
