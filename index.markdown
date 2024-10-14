---
layout: base
---

# Welcome to My Portfolio

I’m a computer science student at the University of Pennsylvania. Check out some of my recent work:

## Projects

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}): {{ post.description }}
{% endfor %}

## About Me
Learn more about me on my [About Me page](/about/).

## Contact
You can reach me at my email [kevinkli@seas.upenn.edu](mailto:kevinkli@seas.upenn.edu) or [LinkedIn](https://www.linkedin.com/in/your-linkedin).