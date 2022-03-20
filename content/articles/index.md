# Articles

<!-- markdownlint-disable MD033 -->

{{ macros_info() }}

{{ page.meta.authors | join(",") }}

{% for page in navigation.pages %}

- {{ context(page.meta) | pretty }}
{% endfor %}

{% for item in navigation.pages %}

- <li><a href="{{ fix_url(item.url) }}">{{ item.title }} - {{ item.meta.authors }}</a></li>

{% endfor %} -->
<!-- markdownlint-disable MD033 -->
