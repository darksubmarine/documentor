# Dark Submarine's Documentor project

## Create beautiful project documentation ...

[Material][2] + [MkDocs][1], an excellent static site generator geared
towards project documentation. It is built using Google's [Material Design][2]
guidelines.

[1]: https://www.mkdocs.org
[2]: https://squidfunk.github.io/mkdocs-material/


## Quick start

Before installing MkDocs, you need to make sure you have Python and pip – the Python package manager – up and running. You can verify if you're already good to go with the following commands:

```bash
python --version
# Python 2.7.13
pip --version
# pip 9.0.1
```

Install the latest version of MkDocs and Material with `pip`:

```bash
pip install mkdocs
```

```bash
pip install mkdocs-material
```

Or one line install:

```bash
pip install --no-cache-dir -r requirements.txt
```

**Finally modify the `mkdocs.yml` with your project information and write your wonderful documentation!**


### Building static docs

Build the MkDocs static documentation running command below:

```bash
mkdocs build
```

The previous command will create a folder named `site` with the builded static documentation.

### Serve documentation

Run the `builtin` development server in order to see documentation in edit-time, useful to check each documentation change in realtime.

```bash
mkdocs serve
```
