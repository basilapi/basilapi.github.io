# basilapi.github.io

Website of [BASIL](https://github.com/basilapi/basil), published at https://basilapi.github.io.

Plain static HTML and CSS, no build step. GitHub Pages serves the `main` branch from the root folder (`.nojekyll` disables Jekyll).

| Path | Content |
|---|---|
| `index.html` | Home page |
| `docs/` | Documentation: running the server, REST API, views, Java library |
| `variables/` | Specification of the SPARQL variable naming convention for API parameters |
| `ontology/ns/` | BASIL ontology (`http://basilapi.github.io/ontology/ns#`), HTML and Turtle |
| `assets/` | Stylesheet and logo |

Preview locally:

```
python3 -m http.server 8000
```

When a new BASIL version is released, update the version number in `index.html` and `docs/index.html`.
