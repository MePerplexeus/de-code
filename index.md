# Home
Welcome to DE;CODE

I'm glad you are here. I plan to talk about something related to programming i hope... (:
Stick around ;)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
