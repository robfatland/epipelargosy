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
4. Leave the box *unchecked** for *Include all branches*
5. For *Owner* select your github user account, or another organization to create the new repository under
6. Give your use case repository a name under *Repository name*
7. Add a short *Description*
8. Select the option for *Public*
9. Finally, click *Create repository*

### Configure your new use case repository

With your new use case repository, you can choose to clone the repository to work on your local system, or edit configuration files within the web browser.

In the `book` directory, update the `_config.yml` file with some basic information:
- title
- author
- repository url
You can leave all the other configuration options unchanged for now.

### Set up action to build the JupyterBook

In your repository *Settings* (gear icon on top of your repository's page), go to the *Pages* section
Under the *Build and deployment* settings, click on the dropdown menu below *Source* and select *GitHub Actions*

### Add your use case content

Edit environment.yml, modify notebooks, and your JupyterBook will be published for you! 
