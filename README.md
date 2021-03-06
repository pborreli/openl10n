# OpenLocalization

[![Build status...](https://img.shields.io/travis/openl10n/openl10n.svg?style=flat)](http://travis-ci.org/openl10n/openl10n)
[![Code quality...](https://img.shields.io/scrutinizer/g/openl10n/openl10n.svg?style=flat)](https://scrutinizer-ci.com/g/openl10n/openl10n/)
[![License MIT](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/openl10n/openl10n/blob/master/LICENSE)
[![Packagist](http://img.shields.io/packagist/v/openl10n/openl10n.svg?style=flat)](https://packagist.org/packages/openl10n/openl10n)
[![Dependency Status](https://www.versioneye.com/user/projects/543ce4ff64e43a059e000082/badge.svg?style=flat)](https://www.versioneye.com/user/projects/543ce4ff64e43a059e000082)

OpenLocalization is a **localization management web-app** to help you translate
any of your projects. Its main goal is to provide an UX friendly tool to easily
edit and deploy your application translations.

See the [official website](http://openl10n.io/) to learn more about OpenLocalization.

## Installation

See detailled instructions on the [official documentation](http://docs.openl10n.io/page/getting-started/installation.html).

**TL;DR**: you will need [Composer](https://getcomposer.org/doc/00-intro.md#installation-nix)
to install PHP dependencies, and [NPM](https://www.npmjs.org/) + [Sass](http://sass-lang.com/install)
for the front-end part.

    # PHP dependencies
    composer install

    # Javascript dependencies
    npm install
    ./node_modules/.bin/gulp build --prod

## Deployment

[Capistrano](http://capistranorb.com/) is the recommended way to deploy the project.

Copy the `deploy.rb.dist` file and add your environment configuration.

    cp app/capistrano/stages/deploy.rb.dist app/capistrano/stages/deploy.rb

## License

OpenLocalization is released under the MIT License. See the [bundled LICENSE file](LICENSE)
for details.
