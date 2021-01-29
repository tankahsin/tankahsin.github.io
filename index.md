# My Website
My Website
# Get in Touch
<ul>
<li>
<li><a href="https://github.com/{{site.tankahsin
}}>GitHub</a></li>
</ul>">GitHub</a></li>
</ul>

<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>
