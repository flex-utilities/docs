# [Flex Documentation](https://docs.flex.gd)

[![Publish to docs.flex.gd](https://github.com/flex-utilities/docs/actions/workflows/publish.yml/badge.svg)](https://github.com/flex-utilities/docs/actions/workflows/publish.yml)

Welcome to the repository for Flex's online documentation!
Documentation is hosted at <https://docs.flex.gd> for easily viewing information about the standard on an easy-to-use and beautiful site.

## What is Flex?

Please view the README about Flex at [docs/About/what-is-flex.md](./docs/About/what-is-flex.md) or look at the entire ["About" directory](./docs/About/).

## Contributing

Please make a **PULL REQUEST** with your changes so that they can be reviewed. All pull requests are subject to the [contribution guidelines](./docs/About/contributing.md).

<details>
<summary>Previewing the documentation site</summary>

If you are working on the documentation and would like a live preview of the site, please use a Python virtual environment (venv).

```sh
python3 -m venv venv
```

After which you must install the requirements of the project using `pip`.

```sh
python3 -m pip install -r requirements.txt
```

Once all dependencies are installed, you may see a preview of your work using `mkdocs serve`.
  
</details>
