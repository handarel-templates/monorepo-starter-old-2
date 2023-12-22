# monorepo-starter

## TODO:

Change the `monorepo-starter` name in:

-   `.devcontainer/devcontainer.json`
-   `package.json`
-   `pyproject.toml`
-   `project.json`

Optional: Change the email in the `SECURITY.md` file. \
Optional: Change the owner name in the `LICENSE` file.

## About this Repository

TODO: Write something about this new repository.

## Repo Structure

| Path        | Description                                            |
| ----------- | ------------------------------------------------------ |
| `docs/`     | Typst documents.                                       |
| `projects/` | Directory for all projects.                            |
| `tools/`    | Directory for locally used configurations and scripts. |

### Project Locations

| Path                  | Description                                               |
| --------------------- | --------------------------------------------------------- |
| `projects/apps/`      | Entry point for applications.                             |
| `projects/libs/`      | Location for (buildable) libraries.                       |
| `projects/notebooks/` | Location for datascience notebooks.                       |
| `projects/packages/`  | Location for publishable libraries.                       |
| `projects/scripts/`   | Location for standalone scripts.                          |
| `projects/vendors/`   | Location for customizations for third party applications. |

### Typst Documents

| Path              | Description                                             |
| ----------------- | ------------------------------------------------------- |
| `docs/assets/`    | Location for global assets like images or icons.        |
| `docs/documents/` | Location for Typst documents like reports or handbooks. |
| `docs/fonts/`     | Location for all fonts.                                 |
| `docs/utils/`     | Location for Typst specific functions or components.    |

### Tools

| Path               | Description                                          |
| ------------------ | ---------------------------------------------------- |
| `tools/ansible/`   | Ansible configurations.                              |
| `tools/scripts/`   | Locally used scripts, e.g. for publishing a package. |
| `tools/terraform/` | Terraform configurations.                            |
| `tools/vagrant/`   | Vagrant configurations.                              |
