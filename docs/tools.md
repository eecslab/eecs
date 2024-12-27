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

Fisrt, Upload the whole to github repository, such as `git@github.com:test/xxxx.git`
And then， execute following command

```bash
mkdocs gh-deploy
```


Now, you can access the website: `https://test.github.io/xxx`