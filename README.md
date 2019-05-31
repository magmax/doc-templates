This repository contains several templates to start documenting quickly.

It follows the pattern doc-as-code, by using RST and Sphinx and some plugins
like sphinx-plantuml to allow to draw images.

All templates contains comments and examples in order to be self-documented.

# Common instructions


1. Copy the desired directory with templates.
2. In the new location, start a virtual environment:

```
$ python3 -m venv venv
$ . venv/bin/activate
(venv) $
```

3. Install dependencies:

```
(venv) $ pip install -r requirements.txt
```

4. Edit the template and compile with the `make` scripts into the desired
output. Examples:

```
(venv) $ make html
(venv) $ make singlehtml
(venv) $ make latexpdf
```

# Plantuml

In order to use PlantUML, just download the jar file into your ~/bin directory
or modify the `plantuml_path` variable in the `conf.py` files.
