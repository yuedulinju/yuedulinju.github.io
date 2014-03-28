{% assign author = site.authors[page.author] %}

    Author: <a href="{{ author.web }}">
    <img
      class="after"
      src="http://www.gravatar.com/avatar/{{ author.gravatar }}.png"
      alt="{{ author.display_name }}"
      width="32"
      height="32"
    >
    </a>
    <b>{{ author.display_name }}</b>
    <i>
        Github:
        <a href="https://github.com/{{ author.github }}">@{{ author.github }}</a>;
      </i>
      <i>
        <a href="{{ author.web }}">Web</a>;
      </i>
      <i>
        <a href="mailto:{{ author.email }}">{{ author.email }}</a>
      </i>
<br/>
