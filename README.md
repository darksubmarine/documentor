# Documentor
Documentation project based on MkDocs and Materials theme. 

This project provides a simple approach to generate nice and readable software documentation.

## How to use it?

 1. Clone this project and copy it into your prefer place. Could be a custom project to have all code and docs in the same place.
 2. Edit the file `mkdocs.yml` located into `docs` folder to setup:
    1. **Project info:** 
    ```yaml
    # Project information
    site_name: Project Documentation
    site_description: Dark Submarine documentor library
    site_author: Dark Submarine_
    site_url: https://www.darksubmarine.com/

    repo_name: 'darksubmarine/documentor'
    repo_url: 'https://github.com/darksubmarine/documentor' 
    ``` 
    2. **Customize the main navigation nav:**
    ```yaml
    # Main menu
    nav:
      - Introduction: index.md
      - Extensions:
        - Admonition: admonition.md
        - Codehilite: codehilite.md
    ```
 3. Write your documentation as Markdown format into `docs/files` folder
 4. Run the command `make docs` to see your documentatioon in the browser.
