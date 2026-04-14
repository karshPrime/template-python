
## Copier

This repository provides a [copier](https://copier.readthedocs.io/en/stable/)
template for creating Python development environments using `uv`. It offers a
consistent and reproducible setup across projects and makes it easy to apply
improvements when the template is updated.


### Prerequisites

Install the Copier command:
* **Quick option:** `uv tool install copier`
* **Documentation:** https://copier.readthedocs.io/en/stable


### Create New Project

Run the following command:

```bash
$ copier copy gh:karshPrime/template-python path/to/project --trust
```
Answer the Copier prompts to configure the project.
* **Project Description:** Optional plain‑text description of the project.
* **Library Pack:** Optional selection of libraries to include in the project.

**Note:** The `--trust` option is required because the template runs `uv` and
`git` commands.


## Project Features

* **uv-based Python workflow**: All Python tasks, including running, linting,
  formatting, and testing, are handled using uv.

* **Example application and module structure**: Includes a minimal command‑line
  entry point (main.py) and a simple module layout.

