# Installation

## Stable release

To install {{ cookiecutter.project_name }}, run this command in your terminal:

```sh
uv add {{ cookiecutter.pypi_package_name }}
```

Or if you prefer to use `pip`:

```sh
pip install {{ cookiecutter.pypi_package_name }}
```

## From source

The source files for {{ cookiecutter.project_name }} can be downloaded from the [Github repo](https://github.com/{{ cookiecutter.github_organization }}/{{ cookiecutter.pypi_package_name }}).

You can either clone the public repository:

```sh
git clone git://github.com/{{ cookiecutter.github_organization }}/{{ cookiecutter.pypi_package_name }}
```

Or download the [tarball](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.pypi_package_name }}/tarball/master):

```sh
curl -OJL https://github.com/{{ cookiecutter.github_organization }}/{{ cookiecutter.pypi_package_name }}/tarball/master
```

Once you have a copy of the source, you can install it with:

```sh
cd {{ cookiecutter.project_slug }}
uv pip install .
```
