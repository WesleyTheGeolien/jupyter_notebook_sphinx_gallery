# Usage

1. Make sure there is at least one jupyter notebook (*.ipynb) inside `content/notebooks`
1. Add your logo into `content/_static/images`
1. Update the `content/conf.py` file with the link to your file
1. Run `make -j4 html` inside the content folder, this will generate the html inside `_builds`. The entrypoint is `_builds/html/index.html`

# Auto Deployment
If you check this code into github there is a folder with github action to automatically deploy the updates.
For this to work make sure you enable github pages in the project settings and choose the `gh-pages` branch and `/{root}` as the source.
The Website will be availible at `https://ORG_OR_USERNAME.github.io/REPONAME`

# Acknowledgments

- This template was inspired by [Project Pythia](https://github.com/ProjectPythia/projectpythia.github.io)
- There are some dummy svg from [fontawesome](https://fontawesome.com)
