# Math typesetting using KaTex
Forked from GitbookIO/plugin-katex. Update Katex from 0.5.1 to the latest version (0.11.1).

&nbsp;
## Configuration
Use it for your book, by adding to your book.json:

```json
{
    "plugins": ["katex@git+https://github.com/Renovamen/gitbook-plugin-katex.git"]
}
```

or

```json
{
    "plugins": ["katex@git+https://gitee.com/Renovamen/gitbook-plugin-katex.git"]
}
```

then run `gitbook install`.

&nbsp;
## Usage

```
Inline math: $$\int_{-\infty}^\infty g(x) dx$$, $\int_{-\infty}^\infty g(x) dx$


Block math:

$$
\int_{-\infty}^\infty g(x) dx
$$

Or using the templating syntax:

{% block math %}\int_{-\infty}^\infty g(x) dx{% endblock %}
```

&nbsp;
### Comparison with [MathJax](https://github.com/GitbookIO/plugin-mathjax)

- Faster
- Refreshing pages manually to render formulas is not need