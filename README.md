# Local WPX

Extendable, composer managed WordPress local development. Served up by [Lando](https://lando.dev/).

## Usage

This is template/boilerplate code for setting up a WordPress environment for local development, which is also flexible enough to be used in conjunction with CI/CD tooling to build packages for production, including packages like headless front-ends that run independently of WordPress whose service definitions can be added to the project's Lando configuration.

The root package configuration provides for a composer managed installation of WordPress, as well as handling the symlinking of local "wordpress-plugin" and "wordpress-theme" type packages. This allows a developer to quickly add their own plugins and themes to the development environment, as well as define any third-party plugin or theme dependencies.
