# Electric Mass Hugo Theme

A Simple website theme for Hugo.

## Getting Started

There are a couple of things needed for the script to work.

### Prerequisites

Git and Hugo (extended version) needs to be installed on your local computer.

#### Hugo

Hugo installation instructions can be found
[here](https://gohugo.io/getting-started/installing/).

Make sure that you install the `extended` version of Hugo.

## Installation

To install this theme move to your Hugo site folder and run the following
command:

```shell
git clone https://github.com/electric-mass/hugo-theme themes/electric-mass
```

If you already use git for the Hugo site you can add the theme as a submodule
using the following command instead:

```shell
git submodule add git@github.com:electric-mass/hugo-theme.git themes/electric-mass
```

To update the theme, as a submodule, use the following commands:

```shell
git submodule update --remote --rebase
git add .
git commit -m "git submodule updated"
git push
```

**Note:** Take a look at the `config.toml` file on the `exanpleSite` folder of
this theme to have an ideia of how to configure your site to use it.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for more details on how
to contribute to this project.

## Versioning

This project uses [SemVer](http://semver.org/) for versioning. For the versions
available, see the [tags on this repository](https://github.com/electric-mass/hugo-theme/tags).

## Authors

* **Frederico Martins** - [fscm](https://github.com/fscm)

See also the list of [contributors](https://github.com/electric-mass/hugo-theme/contributors)
who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)
file for details
