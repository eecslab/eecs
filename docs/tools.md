## mkdocs usage

```bash
pip install mkdocs

pip install mkdocs-material
```

```bash
mkdocs new .
```

the structure of the new mkdocs project directory as follows

```
.
├─ docs/
│  └─ index.md
└─ mkdocs.yml
```

configure the mkdocs theme (theme: material)

```bash
site_name: My site
site_url: https://mydomain.org/mysite
theme:
  name: material
```

add mkdocs navigate

```
site_name: My Docs
nav:
  - Home: index.md
  - Tools: tools.md
theme:
  name: material
```

In `docs` directory to create `index.md` and `tools.md` markdown files

```
.
├── docs
│   ├── index.md
│   └── tools.md
├── mkdocs.yml
```

Deploy mkdocs project to github

```bash

```