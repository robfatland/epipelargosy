# Geosmart Use Case Jupyter Book

[![Deploy](https://github.com/geo-smart/use_case_template/actions/workflows/deploy.yaml/badge.svg)](https://github.com/geo-smart/use_case_template/actions/workflows/deploy.yaml)
[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://geo-smart.github.io/simple-template)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/geo-smart/simple-template/HEAD?labpath=book%2Fchapters)
[![GeoSMART Use Case](./book/img/use_case_badge.svg)](https://geo-smart.github.io/usecases)

## How to use this template

This repository stores a skeleton of a GeoSMART use case book.<br>

### Create a new repository from this template
1. On the top right of the page, click *Use this template* and then *Create a new repository*
2. This should take you to a new page titled *Create a new repository*
3. Double check that the dropdown menu below *Repository template* says either *geo-smart/simple-template* or *geo-smart/use_case_template*
4. Leave the box unchecked for *Include all branches*
5. For *Owner* select your github user account, or another organization to create the new repository under
6. Give your use case repository a name under *Repository name*
7. Add a short *Description*
8. Select the option for *Public*
9. Finally, click *Create repository*

### Configure your new use case repository

With your new use case repository, you can choose to clone the repository to work on your local system, or edit configuration files within the web browser.

In the `book` directory, update the `_config.yml` file with some basic information:
- `title: `
- `author: `
- `repository:` `url: `

You can leave all the other configuration options unchanged for now.

### Setup GitHub Action to build the JupyterBook

In your repository *Settings* (gear icon on top of your repository's page), go to the *Pages* section
Under the *Build and deployment* settings, click on the dropdown menu below *Source* and select *GitHub Actions*

Your JupyterBook is now configured to build and deploy following each new commit you make to the repository. Note: The file that runs the build and deploy action is located at `/.github/workflows/publish.yml` but **you do not need to make any changes to this file**.

### Add your use case content

Now that you have completed the creation, configuration, and setup steps, you can begin adding your use case content to the JupyterBook. 

* update the `environment.yml` file to include any packages that your use case code will require
* `book/intro.md` is where you can add content for your Jupyter Book's home page
* `book/chapters/` will contain markdown or Jupyter Notebook files, the main content of your use case Jupyter Book
    * This template contains placeholder Jupyter Notebook files to illustrate a recommended way to organize your content. You can edit each of these files to add your content following the suggested organization, or remove and replace the placeholder files with your own content. Be sure to update the table of contents file (`/book/_toc.yml`) to reflect any changes you make to the Jupyter Book content.

We recommend that you refer to the JupyterBook documentation on the following topics to help your organize your content:
* [Structure](https://jupyterbook.org/en/stable/structure/toc.html) and [Configure](https://jupyterbook.org/en/stable/structure/configure.html) the table of contents, `book/_toc.yml`
* [Markdown](https://jupyterbook.org/en/stable/file-types/markdown.html) and [Jupyter Notebook](https://jupyterbook.org/en/stable/file-types/notebooks.html) files for the content in `book/chapters/`
* Embeding [images and figures](https://jupyterbook.org/en/stable/content/figures.html) from `book/img/`, and writing inline [math and equations](https://jupyterbook.org/en/stable/content/math.html)
* [Links and references](https://jupyterbook.org/en/stable/content/references.html), [special content blocks](https://jupyterbook.org/en/stable/content/content-blocks.html), and more ways to [structure chunks of content](https://jupyterbook.org/en/stable/content/components.html)

