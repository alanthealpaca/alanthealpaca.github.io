---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---




{% for post in site.posts %}
<div>
<h3><a href="{{post.url}}">{{post.title}}</a></h3>
<p>{{post.preview}}<a href="{{post.url}}" style="font-size:10px"> (Read more...)</a></p>
</div>

{% endfor %}
