# Project Jupyter `team-compass` template

**NOTE** This repository is a work-in-progress and not ready for use yet.

## Usage

Install [cookiecutter](https://github.com/audreyr/cookiecutter):

    pip install cookiecutter

After installing cookiecutter, use team-compass-template:

    cookiecutter https://github.com/jupyter/team-compass-template.git

As team-compass-template runs, you will be asked for basic information about
your team. You will be prompted for the following information:

- `compass_repo`: your `team-compass` repository URL
- `directory_name`: the local directory your cookiecutter template will populate
- `team_name`: your name or the name of your Jupyter Subproject or Working Group

After this, you will have a directory containing a starting point for your
`team-compass`.

To set up a ReadTheDocs page, visit the [manual import page](https://readthedocs.org/dashboard/import/manual/).
Under Admin -> Advanced Settings, select "Build pull requests for this project".
Add other maintainers under Maintainers.
Once the docs build, add the RTD link to the Repo page.
