# Mkdocs Material Insider Meta and Tag index issue demo project

## Run the example

1. create a python virtual env and activate it
2.
    ```bash
    export MKDOCS_GITHUB_TOKEN=<your Github token to access insider repos>
    export MKDOCS_GITHUB_USER=<your Github user name to access insider repos>
    pip install -r requirements.txt
    ```
3. run `mkdocs serve`
4. navigate to tags index and notice the pages with first and second tags are not visible but only
    third tag is displayed in the TOC beacause it's the only one to be defined directly in the page.
