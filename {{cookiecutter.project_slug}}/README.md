# Usage

1. Make sure there is at least one jupyter notebook (*.ipynb) inside `content/notebooks`
1. Add your logo into `content/_static/images`
1. Update the `content/conf.py` file with the link to your file
1. Run `make -j4 html` inside the content folder, this will generate the html inside `_builds`. The entrypoint is `_builds/html/index.html`
