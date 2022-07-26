# Mkdocs Material Insider Meta and Tag index issue demo project

## Install the example

1. create a python virtual env and activate it.
1. run:
    ```bash
    MKDOCS_GITHUB_TOKEN=<your Github token to access insider repos> \
    pip install -r requirements.txt
    ```

## Run the example

1. run `mkdocs serve -f mkdocs-insider.yml`
1. navigate to tags index page and notice the pages with first and second tags are not visible but only
    third tag page is displayed in the TOC because it's the only one to have tags defined directly in the page.
1. Uncomment the Meta config in `mkdocs.yml` and wait for the site to recompile and refresh
     and go to the tags index page again. All the pages are now listed.
