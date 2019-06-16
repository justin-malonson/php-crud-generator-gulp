# PHP CRUD Generator Gulp

Gulp tasks for PHP CRUD Generator - https://www.phpcrudgenerator.com

## Overview

PHP CRUD Generator is an intelligent web application that allows you to build a complete Bootstrap admin panel using a graphical user interface.

PHPCG is suitable for [any PHP MySQL project](https://www.phpcrudgenerator.com/documentation/index).

For more information, please refer to the website and documentation.

## Quick start

### Prerequisites

Node.js installed for Gulp tasks

### Installation

1. Download the latest release. or Clone the repo: git clone https://github.com/migliori/php-crud-generator-gulp.git

2. Unzip the package content to the root of your project

3. Open command prompt, navigate to your project folder

4. run npm: `npm install` to install node_modules.

## Features

### Minify and Compile Bootstrap and the Admin Panel SCSS

```javascript
gulp sass
```

Open your Terminal and run `gulp sass` to compile Bootstrap and the Admin Panel CSS from _/admin/assets/sass_ to _/admin/assets/stylesheets_

### Minify and Compile Bootstrap Javascript and Admin Panel Javascripts

```javascript
gulp scripts
```

Open your Terminal and run `gulp scripts` to compile Bootstrap Javascript and minify the Admin Panel Javascripts in _/admin/assets/javascripts_

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/migliori/php-crud-generator-gulp/tags).

## Authors

**Gilles Migliori** - _Initial work_ - [Migliori](https://github.com/migliori)

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the [LICENSE](LICENSE) file for details
