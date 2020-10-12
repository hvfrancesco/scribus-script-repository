# Scribus Scripter API with mkdocs

Static HTML files generated by mkdocs with the Scribus Scripter API 

- Generate the markdown files and the mkdocs configuration with [export-scripter-api.py](https://github.com/aoloe/scribus-script-repository/blob/master/export-scripter-api/export-scripter-api.py).
- In the `out/` directory clone the repository with the static files:  
  `git clone https://gitlab.com/impagina/scribus-scripter-api-with-mkdocs.git site`
- Run `mkdocs`
- Commit and push the changes.

Warnings:

- `mkdocs` will delete all files in the `site/` directory before creating the new ones (so, never directly edit the `README.md` file in this repository or add other files).
- if there is a an `index.md`, mkdocs won't copy over the `README.md`. you need to manaully copy it after having built the site.