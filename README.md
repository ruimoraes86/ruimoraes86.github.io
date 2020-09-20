<!-- # starter-slim
1. [Generate with the same files and folders](https://github.com/rundocs/starter-slim/generate) from this repository
2. Set up your GitHub Pages to source(/)
3. Now you can view your documentation in your site -->

## site.pages

| source | link |
| ------ | ---- |
{% for page in site.pages -%}
|{{ page.path }}|[{{ page.url | relative_url }}]({{ page.url | relative_url }})|
{% endfor %}

## Documents
https://jekyll-rtd-theme.rundocs.io

## License
The theme is available as open source under the terms of the [MIT License](https://github.com/rundocs/jekyll-rtd-theme/blob/master/LICENSE)
